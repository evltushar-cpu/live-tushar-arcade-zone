# 🕹️ Tushar's Retro Arcade

A modern, responsive, high-performance web retro arcade emulator suite powered by **EmulatorJS** and **WebAssembly**.

## 🌟 Key Features
- **Authentic Box Art**: High-resolution retro box art covers for every title.
- **Stock Market Live Ticker**: Smooth continuous scrolling ticker tape with retro styling.
- **PC Keyboard Controls**: Seamless full PC keyboard support (`Arrows` or `WASD` to move, `Z/J` = B, `X/K/Space` = A, `C/I` = X, `V/U` = Y, `Q/E` = L/R, `Enter` = Start, `Shift` = Select).
- **1-Tap D-Pad Hide/Show (PC Mode)**: Dedicated topbar button `[📱 D-PAD: ON / ⌨️ PC MODE]` (or press `H` on keyboard) to instantly hide touch buttons for clean full-screen PC play.
- **1-Tap Landscape Orientation**: Fast toggle between portrait and landscape modes with auto-viewport repositioning.
- **Multi-System WebAssembly Engines**:
  - Super Nintendo (SNES)
  - Nintendo DS (NDS dual screen)
  - Nintendo Entertainment System (NES)
  - Sega Genesis / Mega Drive (Classic SMB)
- **Universal Custom ROM Loader**: Load and play any external `.zip`, `.sfc`, `.smc`, `.nes`, `.nds`, or `.bin` file directly from your device.

---

## 🎮 Included Games
1. **Disney's Aladdin** (SNES)
2. **Ultimate Mortal Kombat 3** (SNES)
3. **Street Fighter** (SNES)
4. **Contra 4** (Nintendo DS)
5. **Contra Force** (NES)
6. **New Super Mario Bros.** (Nintendo DS)
7. **Super Mario Bros. (Classic 1:1)**

---

## ⚡ Instant Local Play
- Simply double-click **`Play-Arcade.bat`** inside this folder.
- It automatically launches a lightweight local server and opens `http://localhost:8088/index.html` in your default browser with **zero CORS restrictions and instant game loads**!

---

## 🚀 GitHub Pages Deployment
1. Create a repository on GitHub (e.g. `retro-arcade`).
2. Push all contents of this folder (`index.html`, `roms/`, `covers/`, `README.md`) to your GitHub repository.
3. In your repository on GitHub:
   - Go to **Settings** > **Pages**.
   - Under **Build and deployment** > **Branch**, select `main` (or `master`) and folder `/ (root)`.
   - Click **Save**.
4. Your arcade will be live at:
   `https://<your-username>.github.io/<repo-name>/`

---

### 👑 Credits & Ownership
- **Created & Owned by**: Tushar (Retro Arcade Master)
- **Engine**: EmulatorJS & RetroArch WebAssembly Cores
- © 2026 Tushar — All Rights Reserved.
