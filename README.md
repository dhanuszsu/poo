# 🌸 poo பூ — Hand-Tracking Flower Garden

A playful, single-page web app that lets you grow a flower garden using just your hand — no mouse, no keyboard. Point to bloom flowers, open your hand to scatter them into the breeze.

## Demo

Open `index.html` in your browser, allow camera access, and start growing flowers.

## Features

- ✋ **Hand gesture controls** powered by [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands.html)
  - Point your index finger to bloom flowers
  - Open your whole hand to scatter them
- 🌺 11 flower types — rose, sakura, daisy, tulip, lotus, peony, hibiscus, marigold, jasmine, orchid, sunflower
- 🦋 Drifting petals and butterflies
- 📦 Single self-contained HTML file — no build tools, no dependencies to install
- 🔒 Runs entirely client-side — nothing is recorded or sent anywhere

## Tech Stack

- HTML5 Canvas for rendering
- [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands.html) (loaded via CDN) for hand tracking
- Vanilla JavaScript — no frameworks

## Getting Started

### Prerequisites

- A modern browser (Chrome, Edge, or Safari recommended)
- A webcam
- HTTPS or `localhost` (required for camera access)

### Installation

```bash
git clone https://github.com/your-username/flower-garden.git
cd flower-garden
```

Then just open `index.html` in your browser — or serve it locally:

```bash
python3 -m http.server 8000
```

and visit `http://localhost:8000`.

### Usage

1. Click **turn on camera** and allow camera access
2. ☝️ Point your index finger to bloom flowers wherever it lingers
3. 🖐️ Open your hand to scatter every flower into the breeze

## Deployment

This project works great on **GitHub Pages** since it needs no backend:

1. Go to **Settings → Pages** in your repo
2. Set branch to `main`, folder to `/ (root)`
3. Your site will be live at https://github.com/dhanuszsu/poo.git
## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- [MediaPipe](https://github.com/google/mediapipe) for the hand-tracking model
- Fonts by [Google Fonts](https://fonts.google.com/) (Fredoka, Quicksand, Noto Sans Tamil)
