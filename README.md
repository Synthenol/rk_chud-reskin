# rk_chud-reskin

## **A Modern, Lightweight HUD for Everyone (Free & Open Source)**
This is a simple hud made for fun and something to post for free, it lacks features but looks nice and good for servers going for a simple look, I haven't tested this on any resolution/aspect ratio other then 1920x1080 16:9, so it may not work on other resolutions good. 

- **Supported Frameworks:** ESX, QB, QBOX, OX, Standalone (If ran on standalone hunger and thirst are disabled completey)
- **Dependencies:** ox_lib
- **Preview:** [Youtube](https://youtu.be/_WwuhDGCQig)

## **Important!!**
This was made because someone leaked a HUD from a well known server (New Leaf) and uploaded it to GitHub, claiming it as their own. I made this to give people a similar styled HUD, but built from scratch with 100% web source code, no stolen code ❌ (Since theres only has compiled code, as you cannot Server D*** React/Svelte Code). I’ve already said what needs to be said, click the image below if you want to see more.

- https://imgur.com/wGpM7Gz

## **Changelog & Enhancements (2024)**

### Visual Improvements
- Updated all status icons (Health, Armour, Hunger, Thirst, Stamina) with:
  - Custom colors for each icon (green for hunger, blue for thirst, etc.)
  - Drop shadow effect for better visibility on all backgrounds
  - Removed SVG stroke outlines for a cleaner, modern look
- Added drop shadow to percentage text for improved readability

### Features
- Added notification system using ox_lib:
  - Notifies player when health, hunger, or thirst is low
  - Fully integrated with the HUD and works with all supported frameworks

### Codebase & Build
- Refactored React/TypeScript code for modern best practices (removed unused React imports)
- Updated Vite config for ESM compatibility and Node.js type support
- Improved TypeScript configuration for better developer experience

### How to Use
- Build the frontend with `npm run build` in the `web` directory
- Deploy the build output to your FiveM resource as described in the documentation
- Restart your resource after deploying changes

## **Original Author & Credits**
- FULL credits go to [svdden](https://github.com/RealSvdden) for the original HUD inspiration and design.
- All new features, visual improvements, and code refactors by community contributors and AI assistance (2024).
