# Mini Minecraft: The Grind 2026 - SURVIVAL

> A web-based voxel survival game built with Three.js and HTML5. Explore a procedurally generated world, build defenses, loot chests, and survive against "The Glitch" entities that hunt you at night.
---
* **Watch live Demo**
(https://snehal976.github.io/Mini-Minecraft-/) 


---

## 🎮 Game Features

### 🌍 World & Exploration
* **Procedural Generation:** Experience an infinite-feeling terrain with distinct biomes: Lush Plains, Sandy Shores, Stone Mountains, and Snowy Peaks.
* **Dynamic Environment:**
    * **Landmarks:** Discover generated structures like a **Village**, a large **Lake**, and a **Waterfall**.
    * **Safe Zone:** Locate the **Blue Dome** (Safe House) where enemies cannot chase you.
* **Minimap & Radar:** Use the HUD radar to track enemies (Red dots), loot (Purple squares), and safety (Blue square).

### ⚔️ Survival & Combat
* **Health System:** Manage your **100 HP**. Taking damage triggers visual feedback and knockback.
* **The Glitch (Enemies):** Fast-moving corrupted entities.
    * *Behavior:* They roam passively but will aggressively **CHASE** if you get too close or attack them.
* **Combat:**
    * **Hand:** Basic attack (10 damage).
    * **Weapons:** Find loot crates to unlock the **Sword** (Critical Damage).
* **Permadeath:** The stakes are high. If you die, your save file is deleted and the world resets.

### 🏗️ Building & Mining
* **Voxel Interaction:** **Left Click** to mine blocks, **Right Click** to place them.
* **Block Types:** Grass, Path, Logs, Leaves, Planks, Stone, and Metal.
    * *Tip:* Metal blocks are best for building secure bases.

### 🎒 Loot & Progression
* **Treasure Hunt:** Find **6 hidden Loot Crates** scattered across the map using the guiding arrow.
* **Unique Items:**
    * ⚔️ **Blade of the Grind:** High damage output.
    * 🛡️ **Glitch Shield:** Grants 60 seconds of invincibility.
    * ❤️ **Medkits & Orbs:** Restore HP.
    * ⚡ **Speed Boots:** Temporary sprint boost.
* **Inventory System:** Press **'E'** or **'3'** to open your bag, equip blocks, and analyze your status.

### 🤖 AI Integration (Gemini)
* **Lore Generation:** The game utilizes Google's **Gemini API** to generate unique, sci-fi descriptions for the loot you discover.
* **System Analysis:** Click the **"Analyze"** button in the inventory for context-aware survival tips based on your current health, equipment, and progress.

---

## 🕹️ Controls

The game supports both **Desktop (Keyboard/Mouse)** and **Mobile (Touch)**.

### 💻 PC Controls

| Key | Action |
| :--- | :--- |
| **W, A, S, D** | Move Character |
| **Space** | Jump / Fly (Creative Mode) |
| **Mouse** | Look Around |
| **Left Click** | Mine Block / Attack Enemy |
| **Right Click** | Place Block |
| **1 - 7** | Select Hotbar Slot |
| **E** or **3** | Open/Close Inventory |
| **ESC** | Pause / Settings Menu |

### 📱 Mobile Controls
* **Joystick (Bottom Left):** Move character.
* **Screen Drag (Right Side):** Look around.
* **On-Screen Buttons:** * **MINE:** Break blocks/Attack.
    * **PLACE:** Build blocks.
    * **JUMP:** Jump.
    * **BAG:** Open Inventory.

---

## 🚀 How to Run

1.  **Download:** Save the `index.html` file to your computer.
2.  **Play:** Open the file in any modern web browser (Chrome, Edge, Firefox, Safari).
3.  **Note:** No server installation is required! The game runs entirely client-side in the browser.

---

## 🔑 Setting up AI (Optional)

To enable the dynamic AI Lore and Analysis features, you need a Google Gemini API Key.

1.  Open `index.html` in a text editor (Notepad, VS Code, etc.).
2.  Find the line near the bottom of the script section:
    ```javascript
    const apiKey = ""; // API Key injected by environment
    ```
3.  Paste your API key inside the quotes:
    ```javascript
    const apiKey = "YOUR_GEMINI_API_KEY_HERE";
    ```
4.  Save the file and refresh the game in your browser.

---

## 🛠️ Tech Stack

* **Core:** HTML5, CSS3, Vanilla JavaScript (ES6+).
* **3D Engine:** Three.js (r128) with PointerLockControls.
* **Generation:** Simplex Noise for heightmaps and biome distribution.
* **Persistence:** LocalStorage for Save/Load and Permadeath logic.
* **AI:** Google Gemini API (via REST).

---

## 📝 Survival Tips

> * **Follow the Arrow:** The arrow at the top of the screen points to the nearest unopened Treasure Chest.
> * **Build Vertical:** Enemies have trouble climbing straight up. Build a tower to stay safe.
> * **Use the Shield:** If you find the Shield loot, save it for a horde of enemies. It gives you 60 seconds of god mode.
> * **Run to Blue:** If you are being chased and have low health, run to the **Blue Dome**. It is a designated Safe Zone where enemies cannot hurt you.
