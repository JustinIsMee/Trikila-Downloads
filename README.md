# Trikila Android Downloads

[Trikila Apps — screenshots and APK downloads](https://trikila-apps.justinlloydmendoza86.chatgpt.site)

## v1.0.9 — 6 November 2026

- [Passenger APK](https://github.com/JustinIsMee/Trikila-Downloads/releases/latest/download/Trikila-Passenger.apk)
- [Driver APK](https://github.com/JustinIsMee/Trikila-Downloads/releases/latest/download/Trikila-Driver.apk)

Saved-session recovery now returns expired accounts to login while keeping trips during temporary network outages. Web apps use the current app hostname when restoring a Driver session.

Signup now asks for an email address. Forgot password sends a six-digit reset code to the email saved on your account. Codes expire after 15 minutes and are single-use. Existing registered users: open Settings → Password recovery and save your email using your current password. If you cannot access the account or inbox, contact the Trikila administrator for ownership verification. Phone remains the login identifier; signup does not send an OTP.

Install as an Update without uninstalling. Existing accounts, driver applications and trips remain. Android only; APKs do not install on iPhone.

## Permanent pilot server

https://api.trikila.com

The operator laptop and internet must remain online. In v1.0.7 or later, Pilot server settings → Find current pilot server can recover an older address.

## Verification

227 regression tests passed, plus 21 auth/recovery tests after final validation changes. The owner confirmed arrival of the approved sender-test email. APK integrity, bundled features and exclusion of the server sending key were checked. Narrow-width web signup/recovery forms were inspected. Physical Android installation and keyboard/background behavior still require device testing.

- Driver SHA-256: `4db7796f7fdf7cb9aabd229b2999ac37d8ff2311247f828b5db5ffbe7fa7ace1`
- Passenger SHA-256: `14351c4b9affc77a3e01457694d7b603d5835c6da9f0574c10e4111ba68e2c79`

This repository distributes APKs only, without account records, passwords, bookings, sending credentials or identity documents.
