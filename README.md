# Focus.ai

Pixel-art landing page for Focus.

## What changed

- Removed ChatGPT/OpenAI hosting dependencies and references.
- Removed fake-looking metrics and generic AI marketing filler.
- Rebuilt the landing as a dependency-free static site.
- Kept the pixel-art / retro-tech direction.
- Responsive layout and lightweight interactions.

## Run locally

Open `index.html` directly, or run a simple local server:

```bash
python -m http.server 8080
```

Then open `http://localhost:8080`.

## Structure

- `index.html` — page markup
- `styles.css` — visual system and responsive styles
- `app.js` — menu, reveal effects and small interactions

No OpenAI hosting configuration is included.
