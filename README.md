# Birthday Akshata — localhost rebuild

This rebuild uses the supplied deployment ZIP and the recorded interaction as the source of truth. The experience is a six-frame vertical snap-scroll reel:

1. Counting-the-years odometer → click the displayed age → canvas burn/embers/smoke/flame → real age → balloons/text burst + music.
2. Happy Birthday Akshata → 12-photo curved motion path, continuously moving, draggable, slows on hover, grayscale until hover.
3. Draggable polaroid wall.
4. Dark floating-memory scene with amber spotlight, ring, grain, doodles and photos.
5. Eight-page scrapbook reconstructed from the recovered page assets, with click/drag page turns.
6. Original iMessage-style final message, started when the section enters view.

## Run

```bash
npm install
npm run dev
```

Then open the localhost URL Vite prints (normally http://localhost:5173). Vite serves files in `public/` at the site root, which is why the recovered image/audio assets use `/assets/...` paths.

The original deployment ZIP did not include the `pipi-song.mp3` file. For local playback, the soundtrack was extracted from the supplied screen recording and placed at `public/assets/sounds/pipi-song.mp3`.
