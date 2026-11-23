# Somnus: Before the Blackout

A self-contained playable browser prototype for the 2.5D point-and-click mascot horror game. Open `index.html` in a modern browser; no build step or external assets are needed. The 1280×720 facility and guardians are drawn procedurally.

## Night progression

- **Night 1:** No guardian attacks. An incoming phone call begins after the shift starts and walks through cameras, doors, rafters, power, and later-night counters. Click **NEXT** to hear each part; press Enter/Space to advance.
- **Night 2:** Tick-Tock and **The Architect** are introduced.
- **Night 3:** Kilowatt is added.
- **Night 4:** Slumber is added.
- **Night 5:** Lady Porcelain joins; all four original guardians and The Architect are active.

The Architect's appearances start on Night 2. He distracts with a pulsing **4.85 Hz** signal and lines delivered through browser speech synthesis. The selected speech voice, pitch, and speed change between lines for an unstable, shifting-voice effect. Ground the signal by opening CAM 3 before he attacks. His jumpscare shows only a reaching hand and sleeve—**his face is never revealed**. Speech synthesis depends on browser support and available system voices; captions remain visible when audio is unavailable.

## Controls

- Click the West/East buttons to operate doors; click **LOOK UP** and then **CLOSE SHUTTER** to inspect/seal the rafters.
- Click the bottom monitor button and use the facility-map buttons to select CAM 1–4.
- Hold **CALIBRATE GENERATOR** on CAM 3. Use the deterrent pulse on CAM 4 when Slumber is mid-shaft.
- Keyboard: `Space` monitor, `A`/`D` doors, `W`/`S` look up/down, `1`–`4` select camera, `Esc` lower monitor.
- Survive until 6 AM. Each hour lasts 75 seconds; cleared shifts become more dangerous.

Gameplay state uses number/boolean variables. Audio voice playback uses the browser Web Speech API; synthesized audio varies by device/browser voices.
