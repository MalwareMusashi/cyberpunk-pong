# cyberpunk-pong 🎮 
Cyberpunk Pong Wars
A neon-soaked reimagining of the classic Pong Wars game with a cyberpunk aesthetic. Watch as two balls battle for territory in an eternal struggle between NEON and SHADOW forces, complete with glowing trails and atmospheric effects.


🌟 Features

Cyberpunk Visual Design: Neon pink and electric cyan colors against dark backgrounds
Dynamic Trail Effects: Each ball leaves a glowing trail of light as it moves
Atmospheric Effects:

Scanline CRT overlay for retro-futuristic feel
Glowing borders and shadows
Motion blur effects
Impact flashes on collision


Real-time Territory Control: Watch as the battlefield shifts between the two forces
Smooth 60 FPS Animation: Optimized for fluid gameplay
Fully Self-Contained: Single HTML file with no external dependencies (except Google Fonts)

🚀 Demo
Live Demo - https://github.com/MalwareMusashi/cyberpunk-pong

🎯 How It Works
Two balls bounce around the playing field, each representing a different faction:

NEON (Purple/Cyan): Controls the left side initially
SHADOW (Black/Pink): Controls the right side initially

When a ball hits a square controlled by the opposing team, it converts that square to its own color. The game tracks the score in real-time, showing the ongoing battle for dominance.
🛠️ Installation
Option 1: Direct Download

Download the index.html file
Open it in any modern web browser
Enjoy the game!

Option 2: Clone Repository
bashgit clone (https://github.com/MalwareMusashi/cyberpunk-pong)
cd cyberpunk-pong-wars
Then open index.html in your browser.
Option 3: GitHub Pages
Fork this repository and enable GitHub Pages in the settings to host your own version.

🎨 Customization
You can easily customize the game by modifying the color palette in the JavaScript section:
javascriptconst colorPalette = {
  NeonPink: "#ff00ff",
  ElectricCyan: "#00ffff",
  DeepPurple: "#7209b7",
  DarkVoid: "#0a0a0a",
  // Add your own colors here
};
Adjustable Parameters:

SQUARE_SIZE: Size of each territory square (default: 25)
MIN_SPEED / MAX_SPEED: Ball velocity limits (default: 5-10)
TRAIL_LENGTH: Number of trail segments (default: 20)
FRAME_RATE: Animation FPS (default: 60)

🔧 Technical Details
Pure JavaScript: No frameworks or libraries required
HTML5 Canvas: Hardware-accelerated rendering
CSS3 Effects: Gradients, shadows, and animations
Responsive Design: Adapts to different screen sizes

📦 File Structure
cyberpunk-pong/

│

├── index.html          # Complete game (HTML, CSS, and JavaScript)

└── README.md          # Documentation

🤝 Contributing
Contributions are welcome! Feel free to:

Report bugs
Suggest new features
Submit pull requests
Create your own themed versions

Ideas for Contributions:
Add sound effects and background music
Implement power-ups or special abilities
Create different visual themes
Add game modes (multiple balls, obstacles, etc.)
Implement a pause/resume feature
Add difficulty settings

🙏 Credits
Original Pong Wars concept by Nicolas Daniel
Original implementation by Koen van Gilst
Cyberpunk redesign and trail effects by m4lw4r3Mus4shi
Color palette inspiration from cyberpunk aesthetic and synthwave art

🎮 Controls
No controls needed! Sit back and watch the eternal battle unfold. The game runs automatically.

🐛 Known Issues
Performance may vary on older devices
Trail effects might cause slight performance impact on very low-end systems

📊 Browser Compatibility

Chrome 90+ ✅
Firefox 88+ ✅
Safari 14+ ✅
Edge 90+ ✅
Opera 76+ ✅

🚀 Future Enhancements

 Add cyberpunk sound effects
 Implement particle effects on collision
 Add game statistics and history
 Create multiplayer mode
 Implement save states
 Add more visual themes

Made with 💜 and ⚡ in the spirit of cyberpunk aesthetics
Play Now! | Report Issue | Star on GitHub
