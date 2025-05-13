# 🥅 Score A Goal!

A fun, interactive browser-based soccer game where you can kick the ball and control its curve to score a goal!

## 🎮 How to Play

1. **Click inside the goal** to kick the ball
2. **Move your cursor** after kicking to curve the ball's trajectory
3. Score by landing the ball in one of the five goal sections
4. Get different feedback based on whether you score or miss

## ✨ Features

- Interactive ball physics with curve control
- SVG-based animation path for smooth ball movement
- Visual feedback for goals and misses
- Responsive design that works on different screen sizes
- Simple, intuitive controls

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- SVG Animations

## 📁 Project Structure

```
.qodo/
├── index.html      # Main game HTML structure
├── style.css       # Game styling and animations
└── main.js         # Game logic and interaction handlers
```

## 🚀 Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/Sadat-Rakib/ScoreAGoal.git
   cd ScoreAGoal
   ```

2. Open `index.html` in your browser:
   ```bash
   # On macOS
   open index.html
   
   # On Linux
   xdg-open index.html
   
   # On Windows
   start index.html
   ```

3. Alternatively, use a local development server:
   ```bash
   # Using Python
   python -m http.server
   
   # Using Node.js with http-server
   npx http-server
   ```

## 🧩 How It Works

The game uses SVG animation paths to control the ball's trajectory. When you click inside the goal:

1. The ball animation begins
2. Your cursor position influences the curve of the ball's path
3. The game detects which section of the goal the ball hits (if any)
4. Success or failure message is displayed accordingly

## 🔧 Customization

You can easily customize various aspects of the game:

- Edit `style.css` to change the appearance of the game elements
- Modify animation speeds in the SVG animateMotion element
- Adjust hitbox sizes in the HTML structure
- Add additional effects or game mechanics in `main.js`

## 📱 Browser Compatibility

Tested and working in:
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## 📝 License

MIT

## 👥 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/Sadat-Rakib/ScoreAGoal/issues).

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📬 Contact

Sadat Rakib - [@Sadat-Rakib](https://github.com/Sadat-Rakib) - sadat.rakib@example.com

Project Link: [https://github.com/Sadat-Rakib/ScoreAGoal](https://github.com/Sadat-Rakib/ScoreAGoal-)
