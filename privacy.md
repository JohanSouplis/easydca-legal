# EasyDCA privacy policy

*Last updated: October 19, 2026. [Version française](confidentialite.md)*

This policy explains what data the EasyDCA Android app processes, why, where it is stored and how
to exercise your rights. It describes the app as it is: if it changes, this page will be updated
first.

## 1. Who is responsible

EasyDCA is published **by a private individual**, who is the data controller and can be reached at the address below.
Contact for any question or request: **investisseurlogique@gmail.com**.

## 2. What EasyDCA does not do

- No advertising, no sale or rental of data, no advertising profiling.
- No audience measurement tool and no advertising tracker in the app. The only third-party services
  built in are crash reporting and notification delivery (Firebase, see § 3 and § 6), with no usage
  data.
- No connection to your bank or broker: EasyDCA sees neither your accounts nor your orders.
  **All amounts are the ones you type in yourself.**
- No location, no access to your contacts, photos, microphone or camera.

## 3. Data processed

| Data | Where it comes from | What it is for |
|---|---|---|
| **Account**: e-mail address and name of your Google account, technical account id | Google sign-in | signing you in, finding your data on another phone |
| **Investment plan**: goals, target amount, horizon, allocation by asset class and asset, successive versions, reason for a change (and its free, private detail) | what you type | showing and tracking your plan, your "My journey" history |
| **DCA**: frequency, start date, share of income and/or monthly amount (optional), reminder, versions and reasons | what you type | computing your due dates and reminders |
| **Log**: validated due dates (done or not, on time or late), XP, level, streak, jokers, dated milestones | your validations | your progress, Pépite, achievements |
| **Portfolio value**: amounts you note by hand (total and, if you wish, per asset class) | what you type | the value curve and rebalancing through contributions |
| **Online** (only if you turn it on): nickname, friend code, friends and requests, blocked accounts, referral (sponsor, referees), team (name, members, invitations), encouragements, shares of your plan or DCA with chosen friends (amounts only if you tick them) | your actions in Online | friends, monthly leaderboard, team, referral |
| **Anti-abuse limits**: number of code attempts or friend requests | your actions in Online | preventing spam and random account lookups |
| **On your phone only**: session token, local copy of your data (so the app works offline), changes not yet sent, language, Pépite achievements and accessories, scheduled reminders, home screen widget data | the app | working offline, reminders and widget |
| **Crash reports** (Firebase Crashlytics): when the app crashes or hits an error, the technical trace (file and line of the code involved, error type, message stripped of e-mails, numbers, amounts and identifiers), the phone model and Android version, the app version, a random Firebase installation id | the app, automatically (released version only) | finding and fixing crashes; never your e-mail, account id, amounts or plan |
| **Notification token** (Firebase Cloud Messaging): installation id of the app for notifications, type of phone (Android), the phone's time zone, last update date | the app, after you sign in | notifying you right away (friend request, share, team invitation or news, encouragement) and, in the evening at 6 pm in your time zone, a reminder if today's due date is not validated and your reminders are on; erased when you sign out and when you delete your account |
| **Install link** (Google Play Install Referrer): the friend code contained in an invitation link | Google Play, on first launch | pre-filling your sponsor's code; it is sent to the server only if you confirm that code |

**Reminders** (day before, due day, following days, "Review in 7 days") are notifications scheduled
on your phone. In addition, the server can wake the app up through **Firebase Cloud Messaging**
(Google): the message only carries its type (for example "encouragement" or "reminder"), never a
nickname, an amount or your plan; the app then reads the news and shows the notification itself. A
background task also checks the server from time to time, as a safety net. You can turn
notifications off in Android settings, or reminders off in your DCA.

The **Pépite share card** is an image made on your phone; it only goes to the app you pick in the
Android share sheet.

## 4. Who sees what

- **Only you**: your e-mail, plan, DCA, amounts, portfolio value, reasons, log.
- **Your friends** (if Online is on): your nickname, Pépite, level and XP, your streak if you share
  it, your rank in the monthly leaderboard; your plan and/or DCA only for the friends you share them
  with, and amounts only if you tick them.
- **Your teammates**: your nickname, Pépite, level, XP, your streak if you share it, whether you did
  your DCA for the period; never your plan, DCA or any amount.
- **Nobody else**. The publisher can access the database to administer it (fix a problem, delete
  an account on request); it does not use it for anything else.

## 5. Legal bases

- **Performance of the contract** (the terms of use): account, plan, DCA, log, progress, portfolio
  value, offline operation.
- **Consent**, which you can withdraw at any time: Online (can be turned off in Online settings),
  each share (revocable), notifications (Android settings).
- **Legitimate interest**: anti-abuse limits, security of the service, crash reports (fixing app
  errors).

## 6. Where the data is and who hosts it

Server data is hosted by **Supabase** (database and authentication), region **European Union, Paris (AWS eu-west-3)**. Sign-in goes through **Google** (Google
account). Crash reports and notifications go through **Google Firebase** (Crashlytics and Cloud
Messaging, Google Ireland Limited): crash reports are kept 90 days by Firebase. These providers act
as processors. If data is transferred outside the European Union, it
is with the safeguards provided by the GDPR (the provider's standard contractual clauses). All
communication is encrypted (HTTPS).

Data is not included in the phone's Google backup: it comes back from the server when you sign in
again.

**Internal operational alerts** (legitimate interest: monitoring that the service works): the
publisher, and only the publisher, receives short alerts in a private channel of his Discord server
(new account with its sequence number, first validated contribution with your nickname if any, first
user or first team to reach a milestone, technical errors, aggregated weekly figures). They never
contain your e-mail, your amounts or your plan.

## 7. How long

- As long as your account exists, for everything the app needs.
- Team encouragements: 30 days at most; team invitations: 7 days; anti-abuse limits: about one day;
  evening reminders already sent (due date): 60 days.
- Notification token: until you sign out, delete your account, or as soon as Firebase reports it as
  stale (app uninstalled). Crash reports: 90 days at Firebase.
- When you **delete your account**, everything is erased immediately and permanently (see
  [Delete your account](account-deletion.md)). Only exception: XP your sponsor already earned thanks
  to you stays on their account, with no link to yours.
- On your phone: until you sign out, delete your account or uninstall the app.

## 8. Your rights

You can at any time **access** your data, **correct** it, **erase** it, **get a copy** of it
(portability), **object** to processing or ask for its **restriction**, and withdraw your consent.
Most of this is done in the app (edit your plan or DCA, turn Online off, revoke a share, delete
your account). For the rest, write to **investisseurlogique@gmail.com** from the
address of your Google account: answer within one month at most.

You can also lodge a complaint with your data protection authority (in France, the CNIL:
[cnil.fr](https://www.cnil.fr)).

## 9. Minimum age

EasyDCA is meant for people **18 and over**. It does not target
children.

## 10. Changes

If this policy changes significantly, the app or this page will tell you before the change applies.
