# Somnus: Before the Blackout

A self-contained playable browser prototype for the requested 2.5D point-and-click mascot horror game. Open `index.html` in a modern browser; no build step or external assets are needed. The 1280×720 facility and guardians are drawn procedurally.

## Guardian progression

- **Shift 1:** no guardian encounters.
- **Shift 2:** Tick-Tock.
- **Shift 3:** Tick-Tock and Kilowatt.
- **Shift 4:** Tick-Tock, Kilowatt, and Slumber.
- **Shift 5:** all four original guardians and The Architect.

The Architect creates pulsing 4.85 Hz signal interference and attacks if it is not grounded by opening **CAM 3** before the distraction ends. His jumpscare shows only an reaching hand and sleeve: **his face is never revealed**.

## Controls

- Click the West/East buttons to operate doors; click **LOOK UP** and then **CLOSE SHUTTER** to inspect/seal the rafters.
- Click the bottom monitor button and use the facility-map buttons to select CAM 1–4.
- Hold the **CALIBRATE GENERATOR** control on CAM 3. Use the deterrent pulse on CAM 4 when Slumber is mid-shaft.
- Keyboard: `Space` monitor, `A`/`D` doors, `W`/`S` look up/down, `1`–`4` select camera, `Esc` lower monitor.
- Survive until 6 AM. Each hour lasts 75 seconds; cleared shifts become more dangerous.

Game state is represented by number/boolean globals in the requested style. Audio is not yet included; interference is conveyed visually.
