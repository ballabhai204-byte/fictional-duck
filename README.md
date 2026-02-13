# Valentine Card Selector 💝

A beautiful Valentine's Day card selection interface that lets you choose between two different interactive Valentine experiences.

## Features

- **Card Selection Landing Page**: Choose between two uniquely styled Valentine cards
- **Animated Interface**: Floating hearts and smooth transitions
- **Two Valentine Experiences**:
  - **Card 1 (Classic Valentine)**: Interactive Yes/No buttons with playful animations, multi-language support
  - **Card 2 (Personalized Love Note)**: Growing Yes button, shrinking No button, personalized with names

## Project Structure

```
valentine-selector/
├── index.html              # Main landing page with card selection
├── card1/                  # Classic Valentine card
│   ├── index.html
│   ├── css/
│   │   └── style.css
│   ├── images/
│   │   ├── mid.gif
│   │   ├── no.gif
│   │   └── yes.gif
│   └── js/
│       └── script.js
├── card2/                  # Personalized Valentine card
│   ├── index.html
│   └── media/
│       └── VM1fcpu2bKs1e2Kdbj/
│           ├── 200w.gif
│           └── love_icon-icons.com_67808.ico
└── README.md
```

## How to Use

1. Open `index.html` in your web browser
2. You'll see two card options:
   - **Classic Valentine**: A playful card with multi-language support
   - **Personalized Love Note**: A card that can include custom names

3. Click on either card to be redirected to that Valentine experience

### Card 1 Features:
- Yes/No interactive buttons
- The "No" button changes text with each click
- The "Yes" button grows larger
- Multi-language support (English, French, Thai)
- Animated GIF responses

### Card 2 Features:
- Personalized with names (via URL parameters: `?from=YourName&to=TheirName`)
- Yes button grows when you click No
- No button shrinks when clicked
- Sweet victory message when Yes is clicked

## Running Locally

Simply open the `index.html` file in any modern web browser. No server setup required!

```bash
# Navigate to the project directory
cd valentine-selector

# Open in your default browser (macOS)
open index.html

# Or just double-click the index.html file
```

## Customization

### Card 1:
- Edit `card1/js/script.js` to customize button texts and languages
- Modify `card1/css/style.css` for styling changes
- Replace GIFs in `card1/images/` with your own

### Card 2:
- Add URL parameters to personalize: `card2/index.html?from=John&to=Jane`
- Edit inline styles in `card2/index.html` for appearance changes
- Replace the GIF in `card2/media/` folder

## Credits

- Card 1: Based on [will-you-be-my-valentine](https://github.com/Aayush-683/will-you-be-my-valentine.git)
- Card 2: Based on [Date-Valentine-Invitation](https://github.com/Shizu-ka/Date-Valentine-Invitation.git)

## License

Feel free to use these Valentine cards for personal projects! 💕
