# Signexa Player — downloads

Player downloads for [Signexa Digital](https://signexa.digital) signage, published by ProAdvance Pty Ltd.

## Windows

**[Download the latest installer](https://github.com/proadvanceit/signexa-releases/releases/latest)**

Two builds are attached to each release:

| File | Use it when |
|---|---|
| `Signexa.Player.Setup.<version>.exe` | Normal installs — installs per-user and launches at boot, full screen in kiosk mode |
| `Signexa.Player.<version>.exe` | Trying it out — portable, runs without installing |

Both executables are code-signed by **ProAdvance Pty Ltd**. If Windows SmartScreen shows a warning, choose *More info → Run anyway* — the signature is valid and reputation builds as installs accumulate.

### Setting up a screen

1. Run the installer on the PC or NUC driving the screen.
2. The player launches full screen and shows an 8-character pairing code.
3. In your Signexa dashboard, go to **Screens → Pair screen**, choose **Windows**, and enter the code.

To exit the player press **Ctrl+Shift+Q**.

## Other platforms

- **Android TV / Google TV**: install *Signexa Player* from the Google Play Store.
- **Any device with a browser**: open your Signexa player URL directly — no install needed.
- **Raspberry Pi**: provisioning scripts ship with the platform; see your dashboard's pairing dialog.

---
This repository hosts release binaries only. Signexa Digital is a product of ProAdvance Pty Ltd.
