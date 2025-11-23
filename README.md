# 🐉 D&D Encounter Manager

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

D&D Encounter Manager is a modern, browser-based combat tracking tool designed for Dungeons & Dragons 5th Edition (D&D 5e) Dungeon Masters (DM). The tool aims to simplify encounter management, monitor monster statistics, and streamline the flow of combat. It is built entirely with **Vanilla JavaScript**, featuring no external library or framework dependencies (React, Vue, etc.).

All your data is stored securely in your browser's local storage (LocalStorage), ensuring your progress is not lost when you refresh or close the page.

### You can use it from [here.](https://whydll.github.io/DND-Encounter-Manager/)

## 🚀 Key Features

* **Encounter Management:**
    * Create, rename, duplicate, or delete your encounters.
    * All encounters are listed in an organized sidebar for quick access.
* **Creature Management:**
    * Manually add or edit custom creatures with full stat blocks.
    * Delete creatures from the encounter.
* **D&D 5e API Integration:**
    * Search the official D&D 5e monster database (SRD) directly from the app.
    * Automatically import the selected monster (Goblin, Orc, Dragon, etc.) with all its statistics into your encounter.
* **Detailed Combat Tracking:**
    * Track creatures' Hit Points (HP) with a visual health bar.
    * Quick damage/healing buttons (+1, +5, -10, etc.) and a quick damage input field.
    * View detailed stats including AC, speed, ability scores (STR, DEX, CON...), traits, actions, and legendary actions.
    * **Status Effects:** Add conditions (e.g., Poisoned, Stunned, Prone) that are displayed as clear badges on the creature card.
    * Mark creatures as "dead" or "alive."
* **User-Friendly Interface:**
    * **Drag & Drop Reordering:** Reorder creature cards within the encounter list by simply dragging them to manually track initiative or placement.
    * **Collapsible Sections:** Collapse/expand creature cards to show only the name/HP or all stat block details.
    * **Multi-Theme Support:** Choose from 6 different color themes (Dark, Light, Forest, Dragon, Arcane, Dungeon).
    * **Responsive Design:** Optimized for usability on both desktop and mobile screens.
* **Data Management:**
    * **Export** all your encounter data as a single JSON file.
    * **Import** a previously exported JSON file to easily restore your data.
    * Get a **printer-friendly** output of the combat area for table use.

## 💻 Technologies Used

* **HTML5**
* **CSS3** (Includes CSS Variables for Theming, Grid, and Flexbox)
* **Vanilla JavaScript (ES6+)** (No framework or library dependencies)

## 📜 Credits

This project utilizes the fantastic open-source **[D&D 5e API](https://www.dnd5eapi.co/)** to fetch comprehensive monster data for seamless integration.

## 📄 License

This project is licensed under the [MIT License](LICENSE).
