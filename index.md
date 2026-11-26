---
title: Family Chat privacy policy
---

# Family Chat privacy policy

**Effective:** November 25, 2026

Family Chat is a private app for families: a shared chat, calendar, lists, chores, meal planner, photo album, family board, check-ins, a family map and drive history. It is made by Christopher Fennell ("I", "me") for his own family and the families they invite. This policy explains what the app collects, why, who can see it, and how to remove it.

**The short version:** what you put in the app is shared only with the members of your family (or of the chat room you post in). It is stored with Google Firebase so it can sync between phones. It is never sold, never used for advertising, and the app has no ads and no analytics; it only sends crash reports so problems can be fixed.

## What the app collects

**Your account**
- Your name and email address, from Google sign-in or the email and password you sign up with.
- Your profile photo and colour, if you choose them.

**What you share with your family**
- Chat messages, voice messages, photos, videos, files, polls, reactions and pinned messages, in the family chat and in chat rooms. The app also notes when you last read each chat, so the sender can see "Seen by".
- Calendar events, lists, chores, recipes and meal plans, family board notes and album photos.
- Links to calendars the family subscribes to (like a school calendar). Firebase downloads those calendars every few hours to show their events.

**Location (only if you turn it on)**
- **Check-ins:** when you check in, or are asked to and agree, the app shares your location and the address near it. Check-ins are deleted automatically after 30 days.
- **Share my location:** if you turn this on for a family, the app shares your current location with that family about every 5 minutes, and sooner when you move. That includes while the app is closed or not in use (background location). The latest location is kept so the family map can show where you are. Your recent path is kept for 2 days, then deleted automatically.
- **Places and automatic check-ins:** if you save places (like "Home" or "School") and turn on automatic check-ins, the app notices, even while it is closed, when you arrive at or leave them and checks in for you. Each person chooses which of these arrive/leave alerts they receive.
- **Record my drives:** if you turn this on (it needs location sharing), the app uses Android's physical activity detection to notice when you start and stop driving, and records the drive's route, distance, top speed and start and end place, even while the app is closed. A notification shows while a drive is being recorded. Drives are shared with the families you share your location with and deleted after 30 days. The activity detection itself is not stored or sent anywhere, and the app has no health or fitness features.
- **Locate requests:** a family member can ask where you are. Your phone answers only if you have turned on sharing for that family.
- **Emergency SOS:** sends your location to your family straight away.
- Before any of these start, the app explains what it will collect and who will see it. You can turn each one off at any time, in the app or in your phone's settings.

**Microphone.** Used only while you record a voice message, which is sent to the chat you record it in.

**Battery level.** Check-ins include your phone's battery level and whether it is charging. The app also tells your family when your battery drops below 10%, with your location only if you share it with them.

**Device information and crash reports.** A notification token for your phone, so it can receive notifications. If the app crashes, a crash report (what went wrong in the app, the phone model and Android version, and an anonymous account ID, but no messages or location) is sent to Firebase Crashlytics. The app does not collect your contacts, call history or advertising ID.

## Who can see it

- Your **family**: only the members of a family can see what is shared in it. In a chat room, only the people in that room can see it.
- **Me**, as the developer: only where needed to keep the app running or to help when asked, for example to delete an account.
- **Service providers** that run parts of the app:
  - **Google Firebase** (Authentication, Cloud Firestore, Cloud Storage, Cloud Functions, Cloud Messaging and Crashlytics) stores the data, signs you in, sends notifications and receives crash reports. It runs on Google servers in the United States. See [Google's privacy policy](https://policies.google.com/privacy) and [Firebase's privacy information](https://firebase.google.com/support/privacy).
  - **Google Play services** works out your location and detects driving on the phone, and Android's address lookup turns locations into addresses.
  - **OpenStreetMap** provides the map pictures. Your phone downloads them directly, so OpenStreetMap's servers see your IP address and which part of the map you're viewing, not who you are. See the [OpenStreetMap Foundation privacy policy](https://osmfoundation.org/wiki/Privacy_Policy).
  - **Websites you import recipes from**: when you import a recipe from a link, your phone downloads that page from the website.

Your information is **never sold** and **never shared for advertising**.

## Security

Everything is sent over encrypted connections (HTTPS). The data is stored encrypted by Google, and the app's server rules only let family members (and room members) read their family's information.

## How long it is kept, and deleting it

- Check-ins and drives are deleted after 30 days, and location history after 2 days.
- Everything else is kept until it is deleted. You can delete your own messages, photos, events, notes and other items in the app at any time.
- **Leaving a family** removes you from it and its chat rooms. The things you shared there stay visible to the family unless you delete them first.
- **Deleting your account:** in the app, tap your picture, then **Delete my account**. This deletes your account, profile and photo, your messages and the files in them, your album photos, check-ins, location and drives, and removes you from every family. Things you added to shared lists, the calendar, chores, recipes and the family board stay for the family. If you can't use the app, [ask for your account to be deleted](delete-account).

## Children

Family Chat is meant for people aged 13 and older, used within a family. It is not designed for or marketed to children. If you think a child under 13 is using the app, get in touch (see Contact) and their account will be deleted.

## Changes

If this policy changes, the new version will be posted on this page with a new effective date.

## Contact

Questions or requests: email the developer at the address on Family Chat's Google Play page, or [open an issue on GitHub](https://github.com/chrisdfennell/family-chat-privacy/issues).
