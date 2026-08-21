# Release history

## 1.0.6 — August 21, 2026

- Reuses one Android GATT client while the BMS is powered off.
- Reconnects immediately when the saved BMS becomes available again.
- Prevents cancelled GATT attempts from accumulating and triggering repeated beeps.
- Retries FFE1 notification setup without repeatedly sending BMS commands.
- Uses English on first launch while retaining System, Ukrainian, and Russian options.

## 1.0.5 — August 14, 2026

- Made the portrait station screen scrollable on phones with limited height.
- Prevented Android system bars from covering the header and lower cells.
- Made cell-area height adapt to battery configurations from 4S to 16S.
- Preserved the landscape full-screen layout.

## 1.0.4 — August 14, 2026

- Added system, English, Ukrainian, and Russian language selection.
- Synchronized the local web dashboard language with the application.
- Localized balancing-status descriptions.
- Added a readable web-dashboard address below the QR code.
- Preserved signing compatibility with version 1.0.3.

## 1.0.3 — August 13, 2026

- First publicly distributed signed release.
- Added JK/Jikong BMS monitoring over Bluetooth LE.
- Added the local web dashboard and Telegram data requests.
- Added portrait and landscape station layouts.
- Added automatic reconnection and Bluetooth device selection.
