# Privacy Policy — Back Button Assist

**Effective date:** March 8, 2026  
**Developer:** Morgan (Back Button Assist)

## Overview

Back Button Assist ("the app") is a Wear OS accessibility utility that remaps the hardware back-button long-press on your watch. This privacy policy explains what data the app does and does not collect.

## Data we do NOT collect

Back Button Assist does **not**:
- Collect, transmit, or sell any personal information
- Access your contacts, location, microphone, camera, or health data
- Connect to any server, API, or third-party service
- Send analytics, crash reports, or telemetry of any kind
- Read the content of any app on your device

## Data stored locally on your device

The only data the app stores is your selected app preference (the package name of the app you chose to open on long-press). This is stored in Android SharedPreferences on your device and never leaves it.

## Accessibility Service disclosure

Back Button Assist uses Android's Accessibility Service API solely to intercept hardware key events (the back button) and to perform navigation actions (Back / Home). The service does **not** read screen content, monitor typed text, capture any user input beyond the back button hardware key, or observe any other app's activity.

## Permissions

| Permission | Why it is needed |
|---|---|
| `BIND_ACCESSIBILITY_SERVICE` | Required to intercept the hardware back button key event |
| `QUERY_ALL_PACKAGES` | Required to show the list of installed apps for you to choose from |
| `VIBRATE` | Provides haptic feedback when scrolling the bezel |

## Contact

For any questions or concerns, contact the developer via the Play Store listing.
