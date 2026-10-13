# Deadlock Detection Visualizer — Banker’s Algorithm update

This package contains the Banker’s Algorithm section added to the existing DeadlockLab website.

## Live website
https://deadlock-detection.hatchable.site

## Files
- `bankers-section.html` — section markup and controls to integrate into the existing `index.html`
- `bankers.css` — styles for the responsive module
- `bankers.js` — interactive matrix editor, validation, Need/Available calculation, safety algorithm and trace
- `README.md` — integration notes

## Integrate into the original project
1. Add the navigation link `<a href="#bankers">Banker's Algorithm</a>` to the existing top navigation.
2. Insert `bankers-section.html` inside the existing `<main>` element before the footer.
3. Append `bankers.css` to the end of the existing stylesheet.
4. Append `bankers.js` to the end of the existing JavaScript file, after the existing `log()` function is defined.
5. Keep the existing simulator files and features. Do not replace the homepage.

The live project already contains this feature; these files provide the isolated module source for reuse.
