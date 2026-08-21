# Privacy policy

Last updated: August 13, 2026.

BMS Monitor does not require an account and does not send application data to
the developer. BMS telemetry and measurement history are stored locally on the
Android device. The address of the last selected BMS is stored locally for
automatic reconnection.

## Bluetooth and location

Android requires Bluetooth permissions. Some Android versions and vendor
firmware also require Location permission and the system Location switch for
complete BLE scanning. The application does not request coordinates, determine
your location, or transmit location data to the developer or a third-party server.

## Local web dashboard

The application starts an HTTP server on port 8080. It exposes telemetry to any
device that can reach the address on the same local network. There is no built-in
authentication. Use a trusted Wi-Fi network and do not expose port 8080 to the internet.

## Telegram

Telegram integration works only after the user enters a bot token and authorizes
a chat ID. The token is stored locally in application settings, and Android app
backup is disabled. Requests and responses go directly through the Telegram API
under Telegram's own privacy terms. BLE monitoring works without Telegram.

## Removing local data

Delete local settings and history through Android's **Clear storage** action or
by uninstalling the application.

Questions can be directed to the project owner:
<https://github.com/zayants/cell-scope-jk-bms>.
