# LIPSYNC STUDIO 🎭

A high-fidelity, real-time lip-syncing web application. It uses `face-api.js` to detect facial landmarks and animate various cartoon and abstract characters based on your mouth movements.

## Features
- **Real-time Face Tracking**: Uses Tiny Face Detector for performance.
- **Multiple Characters**: Cartoon Face, DJ Robot, Howling Wolf, and Wave Creature.
- **Phoneme Analysis**: Detects basic mouth shapes (A, E, O, etc.) and logs them.
- **Customizable Tuning**: Adjust sensitivity, smoothing, and thresholds.
- **Session Stats**: Track mouth open counts, peak percentage, and FPS.

## How to Run
To ensure camera access and model loading work correctly, you must run this via a local web server.

1. **Install dependencies** (optional, uses npx):
   ```bash
   npm install
   ```

2. **Start the server**:
   ```bash
   npm run dev
   ```

3. **Open in Browser**:
   Navigate to `http://localhost:3000` (or the port shown in the terminal).

## Credits
- **face-api.js**: Facial landmark detection.
- **vladmandic/face-api**: Reliable model hosting.
- **Google Fonts**: Boogaloo and Outfit.
