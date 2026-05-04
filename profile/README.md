# VimoSwim

**We build tools that help swimmers train smarter.**

VimoSwim is a sport-tech company from Krakow, Poland, focused on swimming performance technology. Our flagship product is **Vimo Swim** — a programmable tempo trainer that delivers real-time pace feedback through vibration, sound, and light.

## Vimo Swim

A wearable metronome for swimmers that fits under your swim cap and keeps you on pace — no earbuds, no distractions.

**What it does:**
- Custom interval programs (e.g. 1:30/30s → 1:45/30s → 1:50/30s)
- Triple feedback: piezo buzzer + haptic vibration + LED indicator
- Training data recording — lap count, swim time, speed
- Garmin integration via ANT+ and BLE
- OTA firmware updates via the companion app

**Free companion tools:**
- **VimoSwim Connect** — iOS/Android app for device pairing, program setup, and firmware updates
- **BeatBuddy Lens** — Desktop app for analyzing your Garmin swimming history
- **BeatBuddy Replay** — Review and analyze swim sessions after training
- **Garmin Watch Face** — Control Vimo Swim directly from your wrist

## Tech Stack

Our products are built with:

| Layer | Technology |
|-------|-----------|
| Firmware | C / nRF52840 / Zephyr RTOS |
| Backend | Python / Django / Django REST Framework |
| Website | TypeScript / Nuxt 3 / Vue |
| Mobile | Flutter (iOS & Android) |
| Wearables | Garmin Connect IQ / Apple Watch |
| Infrastructure | DigitalOcean / Docker / GitHub Actions |

## Links

- [vimoswim.com](https://vimoswim.com) — Product website
- [BeatBuddy on Garmin Connect IQ](https://apps.garmin.com/apps/4db5790f-a4c0-4520-b821-1efab35a5a68) — Watch face & data field

## Contact

Interested in collaborating, testing, or investing? Reach out at **contact@vimoswim.com**
