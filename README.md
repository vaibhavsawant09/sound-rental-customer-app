# Vaibhav Sound Rental — preview app

This is an Expo React Native preview for the customer app. It currently demonstrates the black-and-gold interface, package selection, a booking request form, and an in-memory booking list.

## Important limitations
- This preview does not yet have real customer accounts, cloud booking storage, owner notifications, payment collection, or email receipts.
- Booking requests exist only in the app's current session and are not sent to the business.
- Firebase and payment integration must be configured before using this with real customers.

## Build an Android APK
1. Install dependencies with `npm install`.
2. Link the project to the Expo project using `npx eas-cli@latest build:configure` (or `eas init`) and set the real EAS project ID in `app.json`.
3. Run `npx eas-cli@latest build --platform android --profile preview`.

An Expo account and linked GitHub repository alone do not upload source code or create an APK.
