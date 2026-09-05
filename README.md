
# 🌱 EcoGuru — Build Green. Earn Impact.

> A Minecraft-inspired environmental gamification website where real-world eco actions become missions, points, tree growth, and leaderboard progress.

## 🎮 About the Project

**EcoGuru** is an interactive web prototype designed to make environmental awareness more engaging through a Minecraft-inspired experience.

Users can explore environmental missions, submit proof of completed actions, earn Eco Points, grow their virtual tree, and compete on a leaderboard.

The project combines a **blocky Minecraft-style visual language** with modern web UI, animations, gamification, and an interactive EcoGuide/assistant experience.

## ✨ Main Features

- 🌱 **Tree Growth System** — starts with an oak sapling and progresses toward a full-grown oak tree as unique missions are completed.
- 🎯 **Environmental Missions** — Plant a Tree, Recycle Plastic, Green Commute, Save Water, Waste Wonder, and Energy Saver.
- 🏆 **Eco Leaderboard** — Minecraft-inspired ranking interface using the supplied spruce-tree visual.
- 🤖 **EcoGuide / Assistant** — guides the player through the experience and ends with a thank-you message.
- 🔐 **Player Sign-In UI** — stores the player's display name locally.
- 💾 **Local Progress Tracking** — mission completion and points are stored with browser `localStorage`; repeated submissions do not repeatedly increase progress.
- 🎨 **Minecraft-Inspired UI** — pixel typography, blocky panels, environmental backgrounds, particles, and scroll/reveal animations.
- 📱 **Responsive Layout** — the leaderboard and other sections reorganize for smaller screens.

## 🛠️ Tech Stack

| Technology | Use |
|---|---|
| **HTML5** | Page structure and components |
| **CSS3** | Styling, responsive design, animations and Minecraft-inspired UI |
| **JavaScript** | Interactions, missions, points, modals, animations and progress |
| **localStorage** | Local player and mission-progress persistence |
| **Google Fonts** | Pixel-style and modern UI typography |
| **GitHub** | Version control and repository hosting |
| **GitHub Pages / Vercel** | Suitable deployment options for this static project |

No frontend framework or build system is required.

## 🤖 Use of AI

AI was used as a **development and design assistant** during the creation of EcoGuru.

### AI assistance included

- Brainstorming the EcoGuru concept and gamification system
- Planning the Minecraft-inspired UI and page structure
- Generating and refining HTML, CSS, and JavaScript
- Debugging layout and JavaScript issues
- Improving responsive layouts
- Implementing the tree-growth and leaderboard concepts
- Refining animation and interaction logic
- Developing the EcoGuide/assistant experience
- Preparing documentation

AI was **not treated as a replacement for development**. Generated ideas and code were reviewed, modified, integrated, and tested to match the project's requirements.

### AI Tool

**ChatGPT (GPT-5.6 Luna)** was used for coding assistance, debugging, UI planning, feature implementation, and documentation.

## 🧰 Other Tools

- **HTML / CSS / JavaScript** — core development
- **Visual Studio Code** — development/editing environment
- **Browser Developer Tools** — testing and debugging
- **User-provided Minecraft tree and sapling images** — visual assets
- **Google Fonts** — typography
- **GitHub** — repository management and hosting
- **Vercel / GitHub Pages** — possible static deployment platforms

## 📁 Project Structure

```text
EcoGuru-Minecraft/
├── index.html
├── README.md
└── assets/
    ├── oak-sapling.png
    ├── oak-tree-grown.png
    ├── spruce-tree.jpg
    ├── minecraft/
    │   └── textures/
    │       └── block/
    │           ├── spruce_leaves.png
    │           └── spruce_log.png
    └── img/
        └── newScreenshots/
            └── unbound3_cherryRainbow.jpg
```

## 🚀 Run Locally

No installation or build process is required.

1. Download or clone the repository.
2. Open the project folder.
3. Open `index.html` in a modern browser.

For development, **VS Code + Live Server** or another local static server is recommended.

## 🌐 Deploy on GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html`, `README.md`, and the complete `assets` folder.
3. Open **Settings → Pages**.
4. Select the branch containing the project.
5. Select the root folder (`/`).
6. Save and open the generated GitHub Pages URL.

## ⚠️ Important Notes

- This is a **static frontend prototype** and does not currently use a server-side database.
- Player progress is stored locally in the browser.
- Clearing browser site data can remove locally stored progress.
- Third-party/user-provided assets should be used according to their respective licenses or permissions.
- **Minecraft** and related trademarks/assets belong to their respective owners. EcoGuru is an independent Minecraft-inspired educational/demo project and is not affiliated with or endorsed by Mojang or Microsoft.

## 🎯 Future Improvements

- 👤 Real user accounts and authentication
- ☁️ Cloud-based progress saving
- 🏆 Live global leaderboard
- 🌍 More environmental missions
- 📊 Environmental impact statistics
- 🎖️ Achievements and badges
- 🗺️ Interactive eco-world/map
- 🔔 Notifications and reminders
- 🌐 Multi-language support
- 🤖 More advanced AI-powered EcoGuide

## 🙌 Acknowledgement

EcoGuru was built as a learning and prototype project combining **web development, environmental awareness, gamification, Minecraft-inspired design, and AI-assisted development**.

> 🌱 **Small actions. Bigger impact. Build a greener world.**

### Thank you for checking out EcoGuru! 💚

## 📜 License

This repository is intended as a project/demo showcase. Before redistributing any third-party assets, verify and follow their respective licenses and usage permissions.
