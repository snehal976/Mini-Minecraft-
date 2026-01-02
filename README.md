# Mini-Minecraft-
A web-based voxel survival game built with Three.js and HTML5. Explore a procedurally generated world, build defenses, loot chests, and survive against "The Glitch" entities that hunt you at night.
Mini Minecraft: The Grind 2026 - SURVIVAL

A web-based voxel survival game built with Three.js and HTML5. Explore a procedurally generated world, build defenses, loot chests, and survive against "The Glitch" entities that hunt you at night.

🎮 Game Features

🌍 World & Exploration

Procedural Generation: Infinite-feeling terrain with distinct biomes: Lush Plains, Sandy Shores, Stone Mountains, and Snowy Peaks.

Dynamic Day/Night Cycle: The world transitions from day to night.

Day: Safe. Enemies roam passively.

Night: Dangerous. Enemies hunt you down.

Landmarks: Discover a generated Village, a large Lake, and a Waterfall.

Safe Zone: A blue-shielded area where enemies cannot chase you.

⚔️ Survival & Combat

Health System: Manage your 100 HP. Taking damage knocks you back.

The Glitch (Zombies): Fast-moving enemies.

Behavior: Roam during the day, Chase at night.

Combat: Attack with your hand (10 dmg) or find a Sword (40 dmg).

Permadeath: If you die, your save file is deleted and the world resets.

🏗️ Building & Mining

Voxel Interaction: Mine blocks with Left Click, Place blocks with Right Click.

Block Types: Grass, Path, Logs, Leaves, Planks, Stone, and Metal (great for secure bases).

Physics: Blocks snap to the grid. You cannot build inside yourself.

🎒 Loot & Progression

Treasure Hunt: Find 6 hidden Loot Crates scattered across the map.

Unique Items:

Sword: High damage.

Shield: 60 seconds of invincibility.

Medkits: Restore HP.

Speed Boots: Temporary sprint boost.

Inventory System: Press 'E' to view your stats and select blocks.

🤖 AI Integration (Gemini)

Lore Generation: The game uses Google's Gemini API to generate unique, sci-fi descriptions for loot you find.

System Analysis: An "Analyze" button in the inventory gives you context-aware survival tips based on your current health and equipment.

🕹️ Controls

PC (Keyboard & Mouse)

Key

Action

W, A, S, D

Move

Space

Jump

Mouse

Look Around

Left Click

Mine / Attack

Right Click

Place Block

1 - 6

Select Hotbar Slot

E

Open/Close Inventory

ESC

Pause / Settings Menu

Mobile (Touch)

Joystick: Move (Bottom Left)

Screen Drag: Look Around (Right side)

Buttons: Mine, Place, Jump, Bag (Inventory)

🚀 How to Run

Download: Save the index.html file to your computer.

Play: Open the file in any modern web browser (Chrome, Edge, Firefox, Safari).

Note: No server installation is required. It runs entirely in the browser.

🔑 Setting up AI (Optional)

To enable the AI Lore and Analysis features, you need a Google Gemini API Key.

Open index.html in a text editor (Notepad, VS Code, etc.).

Find the line near the bottom of the script:

const apiKey = ""; // API Key injected by environment


Paste your API key inside the quotes:

const apiKey = "YOUR_GEMINI_API_KEY_HERE";


Save and refresh the game.

🛠️ Tech Stack

Core: HTML5, CSS3, Vanilla JavaScript (ES6+).

3D Engine: Three.js (r128).

Generation: Simplex Noise for heightmaps and biome distribution.

Persistence: LocalStorage for Save/Load and Permadeath logic.

AI: Google Gemini API (via REST).

📝 Tips for Survival

Day 1 Priority: Find wood (Logs) and dirt/stone to build a shelter before the sun sets.

The High Ground: Enemies have trouble climbing vertical cliffs. Build towers to stay safe.

Metal Blocks: Use Metal blocks for your walls; they look cool and fit the sci-fi theme.

The Village: The village terrain is flat and good for building, but don't get trapped in a house with a Zombie!

Safe Zone: If you are being overwhelmed, run to the Blue Dome. Enemies will lose interest immediately.
