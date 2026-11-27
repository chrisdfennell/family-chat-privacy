---
title: Family Chat privacy policy
---

# Family Chat privacy policy

**Effective:** November 26, 2026

Family Chat is a private app for families: a shared chat, calendar, lists, chores, reminders, meal planner, photo album, family board, check-ins, a family map, trip sharing and drive history. It is made by Christopher Fennell ("I", "me") for his own family and the families they invite. This policy explains what the app collects, why, who can see it, and how to remove it.

**The short version:** what you put in the app is shared only with the members of your family (or of the chat room you post in, or the person you send a reminder to). It is stored with Google Firebase so it can sync between phones. It is never sold, never used for advertising, and the app has no ads and no analytics; it only sends crash reports so problems can be fixed.

## What the app collects

**Your account**
- Your name and email address, from Google sign-in or the email and password you sign up with.
- Your profile photo and colour, if you choose them.

**What you share with your family**
- Chat messages, voice messages, photos, videos, files, polls, reactions and pinned messages, in the family chat and in chat rooms. The app also notes when you last read each chat, so the sender can see "Seen by".
- Calendar events (including which ones count down on the Home screen), lists, chores, recipes and meal plans, family board notes and album photos.
- **Reminders** you set for yourself or someone else in the family: only you and that person can see them. They are deleted automatically a week after they are due.
- Links to calendars the family subscribes to (like a school calendar). Firebase downloads those calendars every few hours to show their events.
- A **weekly summary** on Sunday evening (the family's drives, most visited place and reminders done) is worked out by the app's server from what the family already shares; nothing extra is collected for it.

**Location (only if you turn it on)**
- **Check-ins:** when you check in, or are asked to and agree, the app shares your location and the address near it. Check-ins are deleted automatically after 30 days.
- **Share my location:** if you turn this on for a family, the app shares your current location with that family about every 5 minutes, and sooner when you move. That includes while the app is closed or not in use (background location). The latest location is kept so the family map can show where you are, and your path is kept for 30 days so the family can see where you've been, day by day; then it is deleted automatically. Your family is told if you turn sharing off, if your phone stops sending updates for several hours (for example because it ran out of battery), and when it is back.
- **Place alerts:** if you save places (like "Home" or "School") and turn on place alerts, the app notices, even while it is closed, when you arrive at or leave them and checks in for you. Each person chooses which of these arrive/leave alerts they receive. A family member can also ask to be told if you are not at a saved place by a set time ("Not there yet" alerts); the server checks this from your place alerts and shared location.
- **Share my trip:** if you start sharing a trip, the app shares your progress towards the place you chose and your estimated arrival time while the app is in use, with a notification showing the whole time. It stops when you arrive, when you stop it, or after 4 hours, and the trip is deleted after 2 days.
- **Record my drives:** if you turn this on (it needs location sharing), the app uses Android's physical activity detection to notice when you start and stop driving, and records the drive's route, distance, top speed, start and end place, and a driving report (hard braking, fast starts, time over 80 mph, and how long the phone was unlocked while moving), even while the app is closed. A notification shows while a drive is being recorded. Drives are shared with the families you share your location with and deleted after 30 days. Family members can also ask to be told when you are driving faster than a speed they choose (speed alerts). The activity detection itself is not stored or sent anywhere, and the app has no health or fitness features.
- **Crash detection:** while a drive is being recorded, the app uses the phone's motion sensor to notice a likely crash. Nothing from the motion sensor is stored or sent. If it notices one, it asks if you are OK; if you don't answer within 30 seconds, or you ask for help, your family is alerted with your location.
- **Locate requests:** a family member can ask where you are. Your phone answers only if you have turned on sharing for that family.
- **Emergency SOS:** sends your location to your family straight away.
- Before any of these start, the app explains what it will collect and who will see it. You can turn each one off at any time, in the app or in your phone's settings.

**Emergency contacts outside the app.** You can save up to five people who don't use Family Chat. Their names and numbers are kept on your phone only and are never uploaded. After an SOS or a crash alert, the app opens your text messaging app with a message and your location for them; you choose whether to send it. If you pick them from your phone's contacts, the app reads only the one contact you pick.

**Microphone.** Used only while you record a voice message, which is sent to the chat you record it in.

**Battery level.** Check-ins and your shared location include your phone's battery level and whether it is charging. The app also tells your family when your battery drops below 10%, with your location only if you share it with them.

**Device information and crash reports.** A notification token for your phone, so it can receive notifications. If the app crashes, a crash report (what went wrong in the app, the phone model and Android version, and an anonymous account ID, but no messages or location) is sent to Firebase Crashlytics. The app does not upload your contacts, call history or advertising ID.

## Who can see it

- Your **family**: only the members of a family can see what is shared in it. In a chat room, only the people in that room can see it. A reminder is seen only by the person who set it and the person it is for.
- **Me**, as the developer: only where needed to keep the app running or to help when asked, for example to delete an account.
- **Service providers** that run parts of the app:
  - **Google Firebase** (Authentication, Cloud Firestore, Cloud Storage, Cloud Functions, Cloud Messaging and Crashlytics) stores the data, signs you in, sends notifications and receives crash reports. It runs on Google servers in the United States. See [Google's privacy policy](https://policies.google.com/privacy) and [Firebase's privacy information](https://firebase.google.com/support/privacy).
  - **Google Play services** works out your location and detects driving on the phone, and Android's address lookup turns locations into addresses.
  - **OpenStreetMap** provides the map pictures. Your phone downloads them directly, so OpenStreetMap's servers see your IP address and which part of the map you're viewing, not who you are. See the [OpenStreetMap Foundation privacy policy](https://osmfoundation.org/wiki/Privacy_Policy).
  - **Websites you import recipes from**: when you import a recipe from a link, your phone downloads that page from the website.
  - **GIF sites**: when a chat message contains a GIF link (for example from Tenor or GIPHY), your phone downloads the GIF from that site to show it, so that site sees your IP address.

Your information is **never sold** and **never shared for advertising**.

## Security

Everything is sent over encrypted connections (HTTPS). The data is stored encrypted by Google, and the app's server rules only let family members (and room members) read their family's information.

## How long it is kept, and deleting it

- Check-ins, drives and location history are deleted after 30 days, shared trips after 2 days, and reminders a week after they are due.
- Everything else is kept until it is deleted. You can delete your own messages, photos, events, notes and other items in the app at any time.
- **Leaving a family** removes you from it and its chat rooms. The things you shared there stay visible to the family unless you delete them first.
- **Deleting your account:** in the app, tap your picture, then **Delete my account**. This deletes your account, profile and photo, your messages and the files in them, your album photos, check-ins, location, location history, trips, drives, reminders and alerts, and removes you from every family. Things you added to shared lists, the calendar, chores, recipes and the family board stay for the family. If you can't use the app, [ask for your account to be deleted](delete-account).

## Children

Family Chat is meant for people aged 13 and older, used within a family. It is not designed for or marketed to children. If you think a child under 13 is using the app, get in touch (see Contact) and their account will be deleted.

## Changes

If this policy changes, the new version will be posted on this page with a new effective date.

## Contact

Questions or requests: email the developer at the address on Family Chat's Google Play page, or [open an issue on GitHub](https://github.com/chrisdfennell/family-chat-privacy/issues).
