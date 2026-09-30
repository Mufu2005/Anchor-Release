<div align="center">

# ANCHOR

### A home for your thoughts, plans, and everyday life.

Journal your days. Organize your tasks. Understand your spending.  
Keep the things that matter together.

**Android · Personal Organization · Dark Interface**

[Download Anchor](https://github.com/Mufu2005/Anchor/releases/latest) · [Release History](https://github.com/Mufu2005/Anchor/releases) · [Report an Issue](https://github.com/Mufu2005/Anchor/issues)

</div>

---

## Meet Anchor

Life rarely stays in one category. Your thoughts, responsibilities, routines, spending, and favorite recipes all have a place in your day.

Anchor brings them together in a personal app designed around a consistent dark interface, warm orange accents, and straightforward interactions.

Use it for a quick thought, a weekly plan, a clearer budget, or a recipe you want to make again.

> This repository provides public documentation and Android releases. Anchor’s application source code is not distributed here.

---

## A Look Inside

> **Screenshot space**
>
> Add a wide promotional image or a collection of app screens here.

| Home | Journal | Tasks & Habits |
|:---:|:---:|:---:|
| Screenshot coming soon | Screenshot coming soon | Screenshot coming soon |

| Budget & Savings | Recipe Book | Settings |
|:---:|:---:|:---:|
| Screenshot coming soon | Screenshot coming soon | Screenshot coming soon |

---

## What You Can Do

### Journal

Give your thoughts a place to live.

- Create, edit, and delete journal entries.
- Add titles and categories to organize your writing.
- Copy an entry’s text when you need it elsewhere.
- Export your journal as readable plain text.
- Share individual entries through the journal sharing flow.

Journal titles and contents are encrypted by the app before cloud storage.

### Tasks, Habits & Timetable

Make room for the things you want to get done.

- Keep track of tasks and responsibilities.
- Record habits and everyday routines.
- Organize scheduled activities through the timetable.
- Use Quick Add to reach creation screens faster.

### Budget & Expenses

Keep a clearer record of where your money goes.

- Record income and expenses.
- Organize spending by category.
- Set a monthly budget.
- Review category totals and payment methods.
- Choose cash or a saved card when recording an expense.
- Edit and remove records when plans change.

The current budget implementation uses **PKR**.

### Accounts & Cards

Keep payment references organized alongside your budget.

- Add accounts and their linked cards.
- Select saved cards when recording expenses.
- Identify cards using their bank, brand, and last four digits.
- Archive accounts and cards when they are no longer in use.

Anchor records the transactions you enter. It does not connect to your bank, initiate payments, or automatically import bank transactions.

### Savings

Keep savings visible alongside everyday spending.

- Use a general savings wallet.
- Mark an eligible account as a savings account.
- Record money added to or withdrawn from savings.
- Review savings activity and recorded balances.

Eligible new expenses paid through a card linked to a savings account also update its recorded savings balance.

Savings balances are records maintained inside Anchor, not live bank balances.

### Recipe Book

Keep favorite meals easy to find and follow.

- Save recipes with ingredients and instructions.
- Include optional ingredients and optional steps.
- Choose US or metric units.
- Build shopping lists from recipe ingredients.
- Follow a dedicated cooking screen.
- Use supported voice controls and spoken instructions.
- Set cooking timers with Android notifications.

Voice features depend on device support and microphone permission. Timer alerts depend on notification and alarm permissions, along with Android’s background restrictions.

### Personal Preferences

Make everyday interactions feel right for you.

- Choose Off, Subtle, or Full app haptics.
- Choose biometric-only unlocking or allow device credentials where supported.
- Clear supported cached content through Settings.
- Access account, support, and privacy information.

---

## Download & Install

Anchor is distributed as an Android APK through GitHub Releases.

1. Open the [latest release](https://github.com/Mufu2005/Anchor/releases/latest).
2. Expand **Assets** if needed.
3. Download the file ending in **`.apk`**.
4. Open the downloaded file on your Android device.
5. If Android asks, allow installation from the browser or file manager you used.
6. Follow the installation prompts and open Anchor.

> Download the **APK attachment**.
>
> GitHub’s automatic **Source code (zip)** and **Source code (tar.gz)** archives are repository snapshots, not installable Android apps.

Only install APKs from the official release page linked in this README.

---

## Getting Started

### 1. Verify Your Email

Follow the email verification flow to connect your account.

If a code does not arrive, check your spam folder, confirm the email address, and wait before requesting another code.

### 2. Set Up Your Account

Complete the account setup shown in the app.

Keep your encryption key somewhere safe. You may need it when signing in on another device or recovering access to encrypted information.

### 3. Choose Your Unlock Preference

Open Settings and select the supported unlock method you prefer:

- **Biometrics only:** fingerprint or face authentication supported by your device.
- **Device authentication:** allows supported device PIN, password, or pattern fallback.

Available methods depend on your device and its security settings.

### 4. Start With One Useful Action

Write a journal entry, add a task, record an expense, or save a recipe.

You can explore the other sections whenever you need them.

---

## Updating Anchor

1. Open the [release history](https://github.com/Mufu2005/Anchor/releases).
2. Read the notes for the version you want to install.
3. Download its APK.
4. Install it over your existing copy when Android permits the update.

Keep your encryption key safe before changing devices or reinstalling.

> If Android rejects an update, do not immediately uninstall your existing app. Check the release notes and contact support first, especially if you have locally stored information.

Previous published releases remain available through the release history.

---

## Privacy & Security

Anchor includes email verification, encrypted journal content, and supported device authentication.

A few important distinctions:

- Journal encryption does not mean every kind of app data is encrypted in the same way.
- Device authentication protects access through the app; it does not replace your encryption key.
- Exported plain-text journals are readable by anyone who can access those files.
- Journal sharing gives the recipient access to the entry you choose to share.
- Account and card records are for personal tracking, not payment processing.

Read the in-app **Privacy** and **Terms** pages for additional information.

Never post passwords, verification codes, encryption keys, private journal text, or financial details in public GitHub issues.

---

## Permissions

Anchor requests permissions for features that need them.

| Permission or capability | Purpose |
|---|---|
| Internet access | Email verification, cloud data, and online features |
| Camera | Scanning journal sharing QR codes |
| Microphone | Recipe voice commands |
| Notifications | Supported reminders and cooking timer alerts |
| Alarms | Cooking timer scheduling on supported Android versions |
| Device authentication | Fingerprint, face, or supported device credential checks |

Some features may be unavailable when their required permissions are denied.

---

## Connectivity & Current Limitations

Anchor uses online services for email verification and cloud operations. Do not assume every feature supports offline editing or synchronization.

Current limitations include:

- Full backup and restore across all modules is still being improved.
- Backup and restore should not yet be treated as a complete recovery solution.
- Background recipe timer notifications are implemented for Android.
- Force-stopping the app or restricting background activity can affect timer delivery.
- Voice recognition and biometric availability vary by device.
- Account deletion requests require processing; submitting a request does not immediately delete an account.

Consult individual release notes for version-specific fixes and limitations.

---

## Troubleshooting

### I cannot install the download

Confirm that you downloaded an `.apk` file rather than one of GitHub’s source archives.

Check that your browser or file manager is allowed to install apps, and that your device has sufficient storage.

### Android says the app cannot be updated

The installed app and downloaded APK may have different signing identities, or the downloaded version may be older.

Keep the existing app installed while checking the release details or contacting support.

### My verification email has not arrived

Check your email address and spam folder. Wait before requesting another code, and use the latest code you receive.

### My data is not loading

Check your internet connection and confirm you are signed in to the correct account.

Avoid clearing app storage or uninstalling as a first troubleshooting step.

### Voice controls are not responding

Check microphone permission and your device’s speech recognition settings. Some speech services require an internet connection.

### A cooking timer did not notify me

Check notification permission, alarm access, and Android battery restrictions.

Force-stopping Anchor can prevent scheduled alerts from working as expected.

---

## Support & Feedback

For account-related help, use **Support inside Anchor**.

For reproducible bugs or feature suggestions, use [GitHub Issues](https://github.com/Mufu2005/Anchor/issues).

When reporting a bug, include:

- Anchor version.
- Device model and Android version.
- Steps to reproduce the problem.
- What you expected to happen.
- What actually happened.
- A screenshot or recording with private information removed.

Please keep each report focused on one issue.

---

## Releases

Each release can include:

- An installable Android APK.
- New features and improvements.
- Bug fixes.
- Known limitations.
- Installation or migration notes when needed.

Browse the [complete release history](https://github.com/Mufu2005/Anchor/releases) to find available versions.

---

<div align="center">

**ANCHOR**

A little more space for everyday life.

[Download](https://github.com/Mufu2005/Anchor/releases/latest) · [Releases](https://github.com/Mufu2005/Anchor/releases) · [Feedback](https://github.com/Mufu2005/Anchor/issues)

</div>
