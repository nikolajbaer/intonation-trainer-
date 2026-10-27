# Intonation Trainer

A single-page violin intonation trainer. It listens on the microphone, detects the dominant pitch (YIN), and draws your pitch as a scrolling line against a target, in cents.

- **Nearest note** follows whatever you play; **Fixed note** holds one target (G/D/A/E buttons or semitone stepper).
- In-tune tolerance ±5–20¢, A4 reference 415 or 440–443 Hz.
- No build step and no dependencies. Nothing is recorded or sent anywhere.

## Run it

Open `index.html` in Chrome, Firefox or Safari, or serve it over HTTPS (for example GitHub Pages) to use it on a phone. Browsers only grant microphone access on HTTPS or local pages.
