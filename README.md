# nyan-army-web

Small Nyan Cat + rainbow animation moving from left to right over a full-page blue background, with a longer fading trail and animated original sparkle-style stars.

## Run locally

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.


Extra page: `http://localhost:8000/nyancat.html` (multiple cats in opposite directions).

Vertical test page: `http://localhost:8000/nyancat-vertical.html` (cat moves top-to-bottom with rainbow from feet).
Combined test page: `http://localhost:8000/nyancat-combined.html` (horizontal + vertical cats with stars).
Collision test page: `http://localhost:8000/nyancat-collision.html` (multiple cats colliding with walls and each other).
Collision diagonal trail test: `http://localhost:8000/nyancat-collision-diagonal.html` (ping-pong bounce with diagonal tail).
