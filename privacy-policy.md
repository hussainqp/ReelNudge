# Reel Nudge Privacy Policy

Last updated: 2026-10-20

Reel Nudge ("the app") helps you notice how many short videos you scroll through and gives you a gentle reminder. This policy explains what the app looks at and what it stores. The short version: everything the app stores stays on your phone, and the app itself sends nothing anywhere. The only information the developer ever receives is an email you choose to send from the Help screen. The Terms of Service, on the same screen as this policy, cover the rest.

## What the app looks at

Reel Nudge uses Android's Accessibility Service API. When you turn the service on, it looks at what is on screen (layout and labels) only in these three apps:

- Instagram (com.instagram.android)
- YouTube (com.google.android.youtube)
- Facebook (com.facebook.katana)

It does this to recognise short-video feeds (Reels, Shorts, and similar) and to count each video you move through. The service is configured by Android to receive events only from those three apps. The on-screen information is examined in memory at the moment it is needed to recognise a feed and a swipe. Text on screen in those apps, including anything visible there, may be examined in memory to recognise the Reels/Shorts screen, but it is never saved, logged or sent (only the app name, a running count and the names of Reel Nudge's own screens are written to the device log). The app does not use the Accessibility Service for anything other than counting videos in those apps and showing its own counter and reminders on top of them. When you tap "Back to work" on a reminder, the app asks Android to go to your home screen (a global action); it performs no taps, swipes or gestures inside other apps. After you leave a feed, the app briefly checks which app is in the foreground (its package name only, in memory) so it can hide its counter or reminder; it reads no content from other apps.

The counter and reminders are drawn using an accessibility overlay. The app does not request the "draw over other apps" permission.

## What the app stores

The following is stored on your device only, in the app's private storage:

- Daily count: the number of short videos counted today, the split of that count per app (Instagram, YouTube, Facebook), and the date it applies to.
- Reel history: for each day, how many short videos were counted in each hour of the day and how many per app (Instagram, YouTube, Facebook). It contains counts only, never what you watched. It is kept on your device for up to 365 days; older days are deleted automatically. It is never sent anywhere. The Progress screen shows it.
- Reminder interval: how often a reminder appears (every X videos, default 10; Pro users can choose from 3 to 50).
- App settings: which of the three apps you chose to watch, and whether onboarding and the battery-settings step are done.
- Onboarding answers: your answers to the optional questions at the start (roughly how much time you spend on short videos each day, a rough monthly income range you picked (optional estimate input), and why you usually scroll) and the goals you picked (for example Work or Better Sleep). Only the range you picked is kept, never an exact amount. They are used only on your device, to show your estimate and an optional line in reminders such as "How about getting back to work?". They are never sent anywhere.
- Counter position and size: where you last dragged the on-screen counter badge, and the size you chose for it (small, medium or large).
- Reminder rotation: which built-in quotes have not been shown yet, so quotes do not repeat until all have been shown.
- Pro status: a single "Pro unlocked" yes/no flag, so the app knows whether you bought Reel Nudge Pro.
- Notification settings: which of the three notifications below are on, and the date each one was last shown (so each appears at most once a day).

## Notifications

With your permission (asked on Android 13 and later, and optional), the app can show three notifications, each of which you can turn off in the app's Settings screen: an alert when its accessibility service is off and it has stopped counting, a daily recap of today's count, and a weekly recap of this week's count. These notifications are generated on your device from the counts stored there. Nothing is sent anywhere to create them: there is no server and no push messaging.

## Home-screen widget

If you add the optional Reel Nudge widget to your home screen, it shows today's count from the data stored on your device (keeping only the date it was last drawn for); it sends nothing anywhere.

## In-app purchase

Reel Nudge offers one optional in-app purchase, a one-time "Pro" unlock that lets you choose your own reminder interval and see your full progress history (past days and the weekly view). Purchases are processed entirely by Google Play, under Google's terms and privacy policy. The app talks to the Google Play Store app on your phone to show the price, start the purchase and check whether you own Pro. The app never sees or receives your payment details, name, email address or any other account information; it only learns whether Pro is owned, and stores the "Pro unlocked" flag above. What "lifetime" means is explained in the Terms of Service. There is no account or login, and nothing is sent to us.

## What is not collected

The app collects no personal data. No data is collected by the developer: the app does not collect, share, sell or transmit any data. The app itself has no servers and sends nothing. The INTERNET permission is present only because Google Play's billing library requires it; that library may send diagnostic data to Google, governed by Google's privacy policy. Purchases go through the Google Play Store app, not through Reel Nudge. The app has no ads, no analytics or crash-reporting service of its own, and no accounts.

## Retention and deletion

The stored data above remains on your phone until you clear the app's storage or uninstall the app, which deletes it. Reel history is also deleted automatically once it is more than 365 days old. You can turn the Accessibility Service off at any time in Android Settings > Accessibility, which stops the app from looking at the screen.

## Contacting us

The Help screen (the "Help" button on Home, or "Help" under the button on the Pro screen) lets you report something broken, share an idea or rate the app. If you choose to email us from Help, your email app sends the message and any diagnostics or screenshot you chose to attach. We use it only to answer you and fix the problem. We keep support emails for up to 12 months and then delete them, and we never share them. To have yours deleted sooner, email us and ask. Reel Nudge itself sends nothing: it opens your own email app with the message ready, and you decide whether to send it.

- Diagnostics (optional, on by default for issue reports, and you can untick it): the app version, your device model and Android version, whether the accessibility service is on, whether you have Pro, your reminder interval, which apps you watch, whether notifications are allowed, today's count, and the app's own recent log lines (app names, counts, Reel Nudge screen names, the app version and your device model; never what was on screen). The file starts with a note asking you to review it before sending.
- Screenshot (optional, on by default for issue reports, and you can untick it): a picture of the Reel Nudge screen you were on when you tapped Help. It is taken only inside Reel Nudge, never of other apps.
- Both are written to the app's private cache only when you tap "Write the email", shared only with the email app you pick, and deleted automatically after a day. The screenshot is otherwise kept only in memory while Help is open.
- "I love this app" opens the Reel Nudge page in the Play Store.

## Children

The app is not directed at children and collects no data from anyone.

## Changes

If this policy changes, the updated version and date will be posted at this page's address.

## Contact

Developer: Hussain

Questions: hussain.poonawala163@gmail.com
