# Monochrome Windows Rice for UltraWide

Custom tiling window manager and status bar setup for my ultrawide Windows machine, built primarily with **Komorebi** and **YASB**.

> [Linux Mint + i3 configuration (Non UW)](https://github.com/jhuynh226/Monochrome-Dots-i3)

---

## Preview
![Demo Gif](./Screenshots/demo.gif)
![Full Terminal View](./Screenshots/Full%20Screen%20Terminal%20Photo.png)
![Media Browsing](./Screenshots/Media%20Browsing.png)
![Terminal + VSCode](./Screenshots/Terminal%20+%20VsCode.png)

---

## Tools Used
- **[Komorebi](https://github.com/LGUG2Z/komorebi)** — Tiling window manager for Windows  
- **[YASB](https://github.com/amnweb/yasb)** — Yet Another Status Bar  
- **[Fastfetch](https://github.com/fastfetch-cli/fastfetch)** — System information fetcher  
- **[Cava](https://github.com/karlstav/cava)** — Audio visualizer for terminal + yasb

---

## Installation
1. Install the tools via winget or github

2. Clone this repository: 
   ```powershell
   git clone https://github.com/jhuynh226/Monochrome-Windows-Rice.git

3. Each tool should have its own configuration directory under username/.config
      - Komorebi config files are stored in user profile by default (not inside .config)

5. Place respective config files from git clone into each tool's directory

---

## Notes
- If the weather widget isn't working in Yasb replace the api key
- For the right side modules in Yasb I have labels commented out that use icons instead of descriptors
- Replace the file path for source in FastFetch with path to your txt file
