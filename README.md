# Trikila Android Downloads

Official pilot-testing downloads for Trikila Passenger and Driver.

## Download v1.0.3

- [Passenger APK](https://github.com/JustinIsMee/Trikila-Downloads/releases/latest/download/Trikila-Passenger.apk)
- [Driver APK](https://github.com/JustinIsMee/Trikila-Downloads/releases/latest/download/Trikila-Driver.apk)

## Current pilot server

Updated October 28, 2026:

https://adventures-misc-soma-interview.trycloudflare.com

**Open Pilot server settings before login and enter the address above.** Cloudflare expired the previous address while these APKs were building. Existing installations can also retain the old saved address. This temporary server address can change; the operator updates it here. The laptop/server must be online for login, booking and tracking.

Browser testing: [Passenger](https://adventures-misc-soma-interview.trycloudflare.com/passenger) · [Driver](https://adventures-misc-soma-interview.trycloudflare.com/driver).

## Install

1. Open this page in Chrome on your Android phone.
2. Download the correct app above.
3. Open the APK and allow installation from your browser if Android asks.
4. Install, or choose Update if you already have Trikila. Do not uninstall first.
5. Set the current Pilot server address, then log in. Allow location access when needed; drivers should enable Precise Location.

Android only. These APKs cannot be installed on iPhones. Pilot builds are still being tested.

## Profile picture updates

Driver: Settings > Account & profile > Change profile picture. Finish any active trip, choose a portrait and submit for admin photo review. This does not resubmit or pause the driver application. Passengers see the approved photo after driver acceptance; the previous approved photo stays visible while a replacement is pending.

This repository distributes APKs only. It does not contain user accounts, passwords, bookings, identity documents or application source code. Actual phone installation, image-picker behavior, GPS and background notifications still require device testing.

## Verification

TypeScript passed. Full backend suite: 206 tests passed. APK ZIP integrity and feature bundle checks passed on October 28, 2026. SHA-256:

- Driver v1.0.3: `4afd383d1bfac84d808c947e6eb97367dc3c7ddf71b70777ad936f8c53ae8dd2`
- Passenger v1.0.3: `1572fae32e343e4ef8940b8dc0c82960287c8f3acdcc7faf8708be3bcd296ab3`
