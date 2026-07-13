# HelloRoam — Global eSIM Travel Data App 🌍📱

> React Native app that lets travelers buy prepaid eSIM data plans for **190+ countries in 22 languages** — no physical SIM, activate by scanning a QR code. Live on iOS + Android with a 5/5 App Store rating.

![Platform](https://img.shields.io/badge/Platform-iOS%20%7C%20Android-lightgrey)
![Coverage](https://img.shields.io/badge/Coverage-190%2B_countries-0D96F6)
![Languages](https://img.shields.io/badge/Localized-22_languages-brightgreen)
![Rating](https://img.shields.io/badge/App_Store-5%2F5-brightgreen)

> ℹ️ **Case study** of production work built under NDA. It describes what the product does and the engineering problems I worked on — using only publicly available information (App Store / Play Store listings and the public website). **No proprietary source code or confidential data is included.**

---

## 📖 Overview

**HelloRoam** is a digital eSIM provider that lets international travelers buy prepaid mobile data plans and connect instantly on arrival — replacing expensive carrier roaming and airport SIM hunts. Users buy a plan online, scan a QR code, and connect to local carrier networks across the globe.

- 🌐 **190+ countries** of coverage across 199+ carrier networks
- 🗣️ **22 languages** — full localization for a global traveler audience
- 📲 Live on **iOS + Android** · **5/5 App Store rating**
- 💳 In-app plan purchase, QR-based eSIM activation, dual-SIM support, hotspot sharing

---

## 👨‍💻 My Role

**Lead React Native Engineer**

I worked on the cross-platform mobile app, delivering the traveler-facing experience end to end: plan discovery, purchase, eSIM activation, and full multi-language localization across iOS and Android.

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Mobile | React Native, Expo, TypeScript |
| Navigation | React Navigation |
| State | Redux / Zustand |
| Localization | i18n across **22 languages** |
| Backend / API | Node.js · REST |
| Activation | eSIM / GSMA SGP.22 QR provisioning |

<!-- Zouraiz: review this stack table — I inferred it from your profile's listed skills. Correct any line that isn't exact. -->

---

## 🧩 Engineering Highlights

- **eSIM QR activation flow** — implemented the purchase → provisioning → QR/manual activation journey aligned with GSMA SGP.22 standards, with clear error and retry states for a non-technical, global audience.
- **Localization at scale (22 languages)** — architected the i18n layer so copy, currencies, and date/number formats adapt per locale from a single codebase — no per-language builds.
- **Multi-country plan selection UX** — designed selection for single-country, regional, and multi-region plans across 190+ countries without overwhelming the user.
- **Reliable global payments** — handled in-app purchase flows, edge cases, and receipts/refunds for unactivated eSIMs across many markets.

---

## 📸 Screenshots

_Add public App Store / Play Store screenshots here (safe to use — they're already public)._

<!-- Create a docs/ folder, drop images in, and reference them like: -->
<!-- ![Onboarding](docs/shot1.png) -->

---

## 🔗 Links

- 🌐 Website: https://helloroam.com
- 🍎 App Store: _add link_
- 🤖 Google Play: _add link_

---

*Built as Lead React Native Engineer. Case study only — no confidential code or data is shared, in accordance with NDA.*
