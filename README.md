# Smart Environment Simulator (App 1)

Software-only IoT practical simulator combining:
- Practical 1: sensor connectivity concepts, represented through simulated temperature and humidity
- Practical 2: obstacle detection with simulated LED and buzzer indicators

## Files
- `index.html`: responsive app interface and simulation logic
- `manifest.json`: installable PWA metadata
- `sw.js`: basic offline cache
- `icons/app-icon.svg`: app icon

## Free deployment on GitHub Pages
1. Create a free GitHub account if needed.
2. Create a new public repository named `smart-environment-simulator`.
3. Upload all files and folders from this project ZIP. Keep `index.html`, `manifest.json`, and `sw.js` at the repository root.
4. In repository Settings → Pages, select Deploy from a branch → `main` → `/ (root)` → Save.
5. Wait for the published site link shown in Settings → Pages.
6. Open that HTTPS link in Chrome on Android. Use Chrome's menu → Install app or Add to Home screen (the exact wording can vary).

This is a simulation only. It does not connect to physical sensors or control actual LEDs/buzzers.
