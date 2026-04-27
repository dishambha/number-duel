# Number Duel 🎮

A two-player number guessing game built with vanilla HTML, CSS, and JavaScript. Players secretly choose a number and take turns guessing each other's secret to win!

## 🎯 Game Overview

**Number Duel** is an interactive web-based game where:
- Two players each choose a secret number (2-8 digits)
- Players take turns guessing each other's number
- Feedback is provided for each guess:
  - 🟢 **Green**: Right digit in the right position
  - 🟡 **Amber**: Right digit in the wrong position
- First player to guess the exact number wins!

## ✨ Features

- 🎨 **Modern UI** - Dark theme with gradient accents and smooth animations
- 📱 **Responsive Design** - Works on desktop, tablet, and mobile devices
- 👥 **Customizable Players** - Set custom names for both players
- 🔢 **Flexible Digits** - Choose between 2-8 digit numbers
- 🎉 **Victory Celebration** - Confetti animation on win
- 🔐 **Privacy** - Numbers are hidden with password-style inputs
- 📊 **Guess History** - Visual log of all guesses with color-coded feedback

## 🚀 Quick Start

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/dishambha/number-duel.git
cd number-duel
```

2. Open the game in your browser:
   - Simply double-click `index.html`, or
   - Use a local server (recommended):
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Python 2
   python -m SimpleHTTPServer 8000
   
   # Using Node.js (with http-server)
   npx http-server -p 8000
   ```

3. Navigate to `http://localhost:8000` in your browser

## 💻 Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS variables, Grid, and Flexbox
- **JavaScript (ES6+)** - Game logic and interactivity
- **No Dependencies** - Pure vanilla implementation

## 📋 How to Play

1. **Setup** - Enter player names and choose the number of digits
2. **Choose Secrets** - Each player secretly enters their number (shown as dots)
3. **Handoff** - Pass the device between players before each turn
4. **Guess** - Players take turns guessing the opponent's number
5. **Victory** - First to guess correctly wins!

### Game Rules

- ✦ Both players secretly choose a number with no leading zeros
- ✦ Duplicates (like 1122) are allowed
- ✦ Take turns guessing each other's number
- ✦ Feedback shows correct digits and positions
- ✦ First to guess the exact number wins

## 🎨 Customization

Edit the CSS variables in the `<style>` tag to customize the theme:

```css
:root {
  --bg: #0a0a0f;              /* Background color */
  --accent: #7c6dfa;          /* Primary accent */
  --accent2: #fa6d9a;         /* Secondary accent */
  --green: #4ade80;           /* Correct position color */
  --amber: #fbbf24;           /* Wrong position color */
  /* ... and more */
}
```

## 🌐 Deployment

### Deploy to Render

1. **Create a Render account** at [render.com](https://render.com)

2. **Connect your GitHub repository**:
   - Sign up with GitHub
   - Create a new Web Service
   - Connect your `number-duel` repository

3. **Configure the service**:
   - **Environment**: Select "Static Site" or "Node"
   - **Build Command**: (leave empty for static, or use the provided server)
   - **Start Command**: 
     - For Static Site: Leave empty (Render will auto-detect)
     - For Node.js: `node server.js` (if using the optional server file)
   - **Publish directory**: Leave empty (root directory)

4. **Deploy**:
   - Click "Create Web Service"
   - Render will automatically deploy your site

### Deploy to Other Platforms

**Vercel:**
```bash
npm install -g vercel
vercel
```

**GitHub Pages:**
1. Push code to GitHub
2. Go to repository Settings → Pages
3. Select "Deploy from a branch" → main branch
4. Your site will be available at `https://dishambha.github.io/number-duel`

**Netlify:**
1. Drag and drop the project folder to Netlify
2. Or connect GitHub repository for auto-deploy

## 📁 File Structure

```
number-duel/
├── index.html          # Complete single-file game
└── README.md           # This file
```

## 🎮 Game Screenshots

The game features five distinct screens:
- **Setup Screen** - Player configuration and game settings
- **Pick Screen** - Secret number selection for each player
- **Handoff Screen** - Transition screen between players
- **Game Screen** - Guessing interface with live feedback
- **Winner Screen** - Victory celebration and final reveal

## 🤝 Contributing

Feel free to fork this project and submit pull requests for improvements!

## 📝 License

This project is open source and available under the MIT License.

## 🔗 Links

- **GitHub**: [github.com/dishambha/number-duel](https://github.com/dishambha/number-duel)
- **Live Demo**: [number-duel.onrender.com](https://number-duel.onrender.com) *(deploy yours here!)*

## 💡 Tips & Tricks

- **Strategic Guessing**: Start with common patterns like 1111, 1234, or 5555
- **Remember Feedback**: Use hints from previous guesses to narrow down possibilities
- **Time It**: Play casually or compete for speed!

---

Enjoy your Number Duel! 🎯⚔️
