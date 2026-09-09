# SenseKit

> **Turn your phone into a whole-body health lab.**

SenseKit is a phone-first multimodal health screening platform that uses the sensors already available on a smartphone to provide accessible, private, and personalized health screening.

Instead of requiring specialized hardware for every screening, SenseKit explores how far a regular smartphone can go using its **camera, microphone, speaker, accelerometer, gyroscope, screen, and on-device computation**.

The platform currently combines four independent screening modules into one unified experience:

- 🚶 **MotionSense** — movement, gait, balance, symmetry, and fatigue
- 🎤 **SpeakSense** — speech characteristics and voice assistance
- 👂 **HearSense** — hearing and noise-based screening
- 👁️ **VisionSense** — visual acuity, color vision, and Amsler-grid screening

> ⚠️ **Disclaimer:** SenseKit is an experimental health-screening prototype and is **not a medical device or a diagnostic system**. Results are intended for screening and educational purposes only.

---

## 🚀 Live Demo

### 🌐 Web App
**[Launch SenseKit](https://sense-kit-v1.vercel.app/)**

### 🎥 Demo Video
**[Watch the SenseKit Demo on YouTube](https://www.youtube.com/watch?v=B0VEYU5kzb0)**

---

## 💡 The Idea

Healthcare screening often depends on specialized equipment, clinical environments, or expensive hardware.

But modern smartphones already contain a surprisingly large collection of sensors.

SenseKit asks:

> **How much useful health information can we extract from hardware that people already carry?**

The project explores this idea by turning common smartphone sensors into lightweight screening tools.

The important design principle is that SenseKit does not treat the four modules as unrelated demos.

They all follow the same underlying product loop:

```text
┌──────────────┐
│     SENSE    │
│              │
│ Phone sensor │
└──────┬───────┘
       ↓
┌──────────────┐
│   BASELINE   │
│              │
│ Personal     │
│ reference    │
└──────┬───────┘
       ↓
┌──────────────┐
│    COACH     │
│              │
│ Interpret +  │
│ guide        │
└──────┬───────┘
       ↓
┌──────────────┐
│     ACT      │
│              │
│ Reports +    │
│ next steps   │
└──────────────┘
