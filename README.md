# Trikila Android Downloads

Official pilot-testing downloads for Trikila Passenger and Driver.

## Download Android apps

- [Passenger APK v1.0.3](https://github.com/JustinIsMee/Trikila-Downloads/releases/latest/download/Trikila-Passenger.apk)
- [Driver APK v1.0.4](https://github.com/JustinIsMee/Trikila-Downloads/releases/latest/download/Trikila-Driver.apk)

## Current pilot server

Updated October 29, 2026:

https://marie-advisors-referrals-fossil.trycloudflare.com

**Open Pilot server settings before login and enter the address above.** Cloudflare expired the previous address while these APKs were building. Existing installations can also retain the old saved address. This temporary server address can change; the operator updates it here. The laptop/server must be online for login, booking and tracking.

Browser testing: [Passenger](https://marie-advisors-referrals-fossil.trycloudflare.com/passenger) · [Driver](https://marie-advisors-referrals-fossil.trycloudflare.com/driver).

## Install

1. Open this page in Chrome on your Android phone.
2. Download the correct app above.
3. Open the APK and allow installation from your browser if Android asks.
4. Install, or choose Update if you already have Trikila. Do not uninstall first.
5. Set the current Pilot server address, then log in. Allow location access when needed; drivers should enable Precise Location.

Android only. These APKs cannot be installed on iPhones. Pilot builds are still being tested.

## Driver trips & earnings

Driver v1.0.4: Home and Settings > Trips & earnings show Today / All time completed trips and net after app commission. The breakdown shows recorded cash, tips included and actual charged commission. Fuel is not deducted. Demo and marked pilot-test bookings are excluded. Passenger remains v1.0.3.

## Profile picture updates

Driver: Settings > Account & profile > Change profile picture. Finish any active trip, choose a portrait and submit for admin photo review. This does not resubmit or pause the driver application. Passengers see the approved photo after driver acceptance; the previous approved photo stays visible while a replacement is pending.

This repository distributes APKs only. It does not contain user accounts, passwords, bookings, identity documents or application source code. Actual phone installation, image-picker behavior, GPS and background notifications still require device testing.

## Verification

TypeScript passed. Full backend suite: 210 tests passed. APK ZIP integrity and feature bundle checks passed on October 29, 2026. SHA-256:

- Driver v1.0.4: `696c97abdb7d369237e5c81e585eb5b501a296211e5bcec3b2f020bcd9e0a860`
- Passenger v1.0.3: `1572fae32e343e4ef8940b8dc0c82960287c8f3acdcc7faf8708be3bcd296ab3`
