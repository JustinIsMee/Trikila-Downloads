# Trikila Android Downloads

Browse the app previews and download both Android apps at [Trikila Apps](https://trikila-apps.quietchair19.chatgpt.site).

## Download v1.0.5 — 31 October 2026

- [Passenger APK v1.0.5](https://github.com/JustinIsMee/Trikila-Downloads/releases/latest/download/Trikila-Passenger.apk)
- [Driver APK v1.0.5](https://github.com/JustinIsMee/Trikila-Downloads/releases/latest/download/Trikila-Driver.apk)

Both apps have a simplified public login with the development-account shortcut removed. Existing accounts and trip records remain. Normal cellphone login, signup and password recovery are available.

## Current pilot server

https://losses-reads-individuals-paperbacks.trycloudflare.com

Before login, use Pilot server settings if your installation has an older address. The operator's laptop and internet must remain online for login, bookings and tracking. Temporary pilot addresses may change; ask the operator for the current address if connection fails.

## Install or update

1. Open this page on Android and download the matching app.
2. Open the APK; allow installation from your browser if Android requests it.
3. Choose Update if already installed. Do not uninstall first.
4. Verify the Pilot server address, sign in and allow location when needed.

Android only. These APKs do not install on iPhone. Physical-device installation, GPS, photo picking and background notification behavior still need device testing.

## Verification

TypeScript and existing demo-login backend regression test passed. Both revised web login screens and retained account sign-in were checked in an isolated demo database. ZIP integrity and removal of the public development-login shortcut were verified in both APK bundles.

- Driver v1.0.5 SHA-256: `4d6147f2962fdf8561574c978e687e1c8596e83256d8d8ecf499b2e67851bd50`
- Passenger v1.0.5 SHA-256: `3a1017b20e51c078ce34636aca44766f26e6dd7c33dbbb44d29e7700e2e2eda5`

This repository distributes APKs only. It contains no user accounts, passwords, bookings or identity documents.
