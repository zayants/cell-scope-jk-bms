# Security policy

## Reporting a vulnerability

Do not post bot tokens, signing keys, MAC addresses, or other sensitive data in
a public issue. Use a private
[GitHub Security Advisory](https://github.com/zayants/cell-scope-jk-bms/security/advisories/new).

Include the application version, Android version, BMS model, reproduction steps,
and impact. Share secrets or complete logs only after coordinating privately.

## Security model

- The local web server listens on port 8080 and is reachable from the local network.
- The web dashboard currently has no built-in authentication.
- Its HTTP API provides read-only telemetry through `GET` and `HEAD` requests.
- Do not expose port 8080 to the public internet.
- Telegram bot tokens are supplied by the user and must not appear in issues or logs.
- The application does not change BMS protection settings or MOSFET states.
- The local Android interface can enable or disable balancing.

Public security fixes are released after a safe update is prepared. Only the
latest version in GitHub Releases is considered supported.
