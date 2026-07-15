# SeaWorld Dosage Calculators PWA v10

Key fixes:
- Uses the current CYA selector's selectedIndex directly.
- CYA calculations refresh on change, input, blur, keyup, touchend, focus, pageshow, and polling.
- Current CYA and selected pool persist in localStorage.
- Visible footer shows Build v10.
- Service worker uses network-first loading for HTML to prevent stale calculator code.
- Cache name updated to seaworld-dosage-v10.

After uploading:
1. Open the GitHub Pages URL in Safari.
2. Confirm the footer says Build v10.
3. Refresh once if needed.
4. Remove and re-add the Home Screen shortcut if it still shows an older build.
