# Privacy Policy – HissaHop: Split Trip Expenses

Last updated: 16 October 2026
Developer: Avik Dutta (avik.duttars@gmail.com)

HissaHop: Split Trip Expenses ("the app") helps groups split travel expenses. This policy explains what data the app handles.

## Data stored on your device
Trips, members, expenses, categories, settlements, receipt photos and settings are stored **only on your phone** (in the app's local database). The developer cannot see this data. Uninstalling the app removes it.

## Optional cloud sync
Cloud sync is **off unless you choose to use it**. If you create a cloud account and turn on sync for a trip:
- Your **email address** and a password (handled by Firebase Authentication; the app never sees or stores the password in readable form) are used to sign you in.
- The trip's **name, dates, members, categories, expenses and settlements** are uploaded to Google Firebase (Cloud Firestore) so that people you invite can see the same trip.
- If the trip uses the optional **admin approval** feature, the changes other members propose (a new or edited expense, or changed trip details) are stored in the cloud as a pending request until the admin approves or rejects it. Approved requests become normal trip data; the request is then removed. Requests are visible only to the person who sent them and to the admin.
- Notes and the **names and phone numbers** you type into an expense's contacts (for example a driver or hotel) are part of the expense, so they are uploaded too and visible to people in that trip.
- Photos (receipts, contact photos, trip cover) are **not** uploaded.
- People you invite with a code can see that trip's data and the email addresses of the other trip members.

Data is processed by Google LLC as a service provider (Firebase). See https://firebase.google.com/support/privacy.

## Permissions the app may ask for
- **Contacts:** only when you tap to save a person (such as a driver or hotel) from an expense to your phone's address book. The app writes the new contact; it does not read, upload or browse your existing contacts. Android lists this under one "Contacts" permission that covers both reading and writing.
- **Camera / photos:** only when you choose to attach a receipt or profile photo. Images are processed on the device.
- **Location:** only when you tap "detect location" on an expense. The coordinates may be sent to OpenStreetMap Nominatim to turn them into a place name.
- **Internet:** for optional cloud sync, exchange rates and place search.

## Other network requests
- Exchange rates are fetched from open.er-api.com (only the currency codes are sent).
- Place search and reverse geocoding use OpenStreetMap Nominatim (the text you search for or your coordinates are sent).

The app contains **no advertising and no analytics or tracking SDKs**, and does not sell or share your data.

## Exports and backups
Excel and JSON files you export are saved to your phone's Documents folder. You decide where to share them.

## Deleting your data
- **Local data:** delete trips inside the app, or uninstall the app.
- **Cloud data and account:** open the cloud icon in the app header → *Delete my cloud account*. This permanently deletes your account, the cloud trips you created, and your membership in trips shared with you. You can also request deletion by emailing avik.duttars@gmail.com from your account email.

## Children
The app is not directed at children under 13 and does not knowingly collect their data.

## Changes
If this policy changes, the updated version will be published at the same address with a new date.

## Contact
avik.duttars@gmail.com
