# Katama Engineering

Software engineering studio building native mobile tooling and open-source
libraries. We ship small, well-documented packages that do one thing well.

🌐 [katamaengineering.com](https://katamaengineering.com) · ✉️ [info@katamaengineering.com](mailto:info@katamaengineering.com)

---

## Open source

Native **Capacitor** plugins for iOS: the pieces WKWebView can't do on its own,
built to mirror the conventions of the official Capacitor plugins so they drop
straight into an existing app.

### 📍 [capacitor-plugin-apple-maps](https://github.com/katamaengineering/capacitor-plugin-apple-maps)

Renders a native **Apple Maps (MapKit)** view on iOS, with an `AppleMap` API
deliberately mirroring [`@capacitor/google-maps`](https://github.com/ionic-team/capacitor-plugins/tree/main/google-maps) (camera, markers,
clustering, shape overlays, and place search) so an app can route **iOS to Apple
Maps** and **Android/web to Google Maps** behind one thin abstraction. No API key,
no external dependencies.

[![npm](https://img.shields.io/npm/v/capacitor-plugin-apple-maps.svg?label=npm)](https://www.npmjs.com/package/capacitor-plugin-apple-maps)
![Swift](https://img.shields.io/badge/Swift-iOS%2015%2B-orange.svg)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

### 🔊 [capacitor-plugin-system-volume](https://github.com/katamaengineering/capacitor-plugin-system-volume)

Overlays a native, stylable **system-volume slider** (`MPVolumeView`) on iOS.
Because it's Apple's own control, dragging it sets the OS output volume and the
**hardware volume buttons stay in sync**, something a custom
`<input type="range">` can't do inside WKWebView.

[![npm](https://img.shields.io/npm/v/capacitor-plugin-system-volume.svg?label=npm)](https://www.npmjs.com/package/capacitor-plugin-system-volume)
![TypeScript](https://img.shields.io/badge/TypeScript-iOS-blue.svg)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

<sub>Katama Engineering LLC · South Carolina, USA</sub>
