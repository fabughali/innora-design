# Innora Design - Web Deployment

This repository contains **only the built web files** for the Innora Design Flutter web application.

## 🚀 Deployment Status

- ✅ **Built web files only** - No source code
- ✅ **gh-pages branch** - Single branch deployment
- ✅ **GitHub Pages ready** - Configured for live deployment

## 📁 Repository Contents

This repository contains only the output from `flutter build web`:
- `index.html` - Main HTML file
- `main.dart.js` - Compiled Flutter application
- `assets/` - Application assets and images
- `canvaskit/` - Canvas rendering engine
- `icons/` - App icons and favicon
- `manifest.json` - Web app manifest

## 🌐 Live Site

**URL:** https://fabughali.github.io/innora-design/

## 🔧 Deployment

To redeploy:
1. Build locally: `flutter build web --release --base-href /innora-design/`
2. Copy `build/web` contents to this repository
3. Commit and push to `gh-pages` branch

## 📝 Note

**Source code is not included** in this repository. This is a deployment-only repository containing only the built web assets.
