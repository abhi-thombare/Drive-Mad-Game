Drive Mad Game (HTML • CSS • JavaScript)

A browser-based remake of the popular Drive Mad game, built using simple HTML, CSS and JavaScript. It includes 60+ levels, smooth physics, keyboard controls and a clean menu system. No libraries or engines required — everything runs directly in the browser.

📌 Overview

This project recreates the classic Drive Mad experience with custom code. The menu includes all levels, and each level loads instantly inside the same page. Gameplay focuses on careful acceleration, balance and timing as you drive across bridges, ramps and shifting platforms.

You can add more levels or modify the physics easily because the codebase is small and readable.

🎮 Features

Full multi-level menu (1 to 64 levels)

Clean UI for level selection

On-screen controls for mobile users

Keyboard support for desktop

Smooth physics animation

Restart, next-level and main menu buttons

Simple HTML / CSS / JS project structure

Works offline in any modern browser

🖼️ Screenshots
Menu

The level menu shows all levels in a grid.
Players can scroll and pick any stage.

Gameplay

Levels include ramps, bridges, obstacles, and physics elements.

Level Completed Screen

A snapshot card appears when you finish a level, along with options to go back, restart, or continue.



🧩 Project Structure
📁 Drive-Mad-Game
│
├── index.html          # Main UI + level menu + canvas
├── style.css           # UI, layout and animations
├── script.js           # Game logic, physics, controls
├── levels/             # Level data and configurations
└── assets/             # Images, icons, sounds (optional)


If your structure is different, you can adjust the names.

▶️ How to Run

You don’t need any server or installation.

Option 1 — Open directly

Just double-click index.html.

Option 2 — Localhost (optional)
python -m http.server 8000


Open http://localhost:8000.

Option 3 — GitHub Pages

Upload the project to GitHub

Settings → Pages → Select branch → Save

Your game will be available online.

⌨️ Controls
Desktop

Accelerate: Up Arrow / W

Brake / Reverse: Down Arrow / S

Tilt Left: Left Arrow / A

Tilt Right: Right Arrow / D

Pause: P

Mobile (if enabled)

On-screen UI buttons for forward, backward, left and right

🛠️ Customization
Editing levels

All level data is stored in the levels/ folder.
You can:

change platform sizes

modify vehicle speed

set custom backgrounds

add new obstacles

UI customization

Edit style.css to tweak:

button styles

colors

menu layout

🙌 Contributing

Feel free to open issues or pull requests if you want to improve the game.
Ideas include:

adding sound effects

improving physics

adding more levels

adding a timer or score system
