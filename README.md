# Gift-Box-for-Gamer-buds
Happy womens day to all of you old ladies

a fun project made with HTML,CSS

Sure thing—here’s a README you can copy-paste that walks through your JavaScript logic in a casual, developer-friendly way:

---

#  Click to Unwrap – Present Surprise

An interactive little toy: click the present enough times to "unwrap" it while snow falls all around, and watch the URL get taken over by a garden of emojis 🌼🌸🌻.

## 🔧 How it works

### The Present
- You have to click the `.present` element _multiple times_ (18 total) to trigger the surprise.
- Every click adds to an internal counter, updates a `--count` CSS variable, and triggers a short animation.
- Once the count threshold is reached, the `.open` class is added to visually “open” the gift.

### Snowflakes on Canvas
- Renders animated snow using a `<canvas>` element and a `Snowflake` class.
- Snowflakes get random position, size, angle, and speed.
- If they drift off-screen, they respawn at the top with a fresh random setup.
- Stays responsive with window resizing and pauses when the tab loses focus.

### Emoji Trail in URL
- A rotating array of flower and plant emojis animates endlessly via `window.location.hash`.
- Purely whimsical. Because why not?

## Dev Notes
- Snow updates are handled via `requestAnimationFrame` for smooth animation.
- Canvas redraws each frame; snowflakes are updated and rendered independently.
- You can tweak `countsNeeded` at the top to change how many clicks are required.

## Files
- `index.html` – contains the present and canvas elements.
- `style.css` – handles present animation, visuals, and custom properties.
- `script.js` – where all the JS magic lives.

---
