---
layout: default
title: Account & Data Deletion — Fraud Call Center Tycoon
permalink: /data-deletion/
---

# Account & Data Deletion — Fraud Call Center Tycoon

**Effective date:** 2026-07-12
**Publisher:** FCCT Studio
**Contact:** [fcct.support@gmail.com](mailto:fcct.support@gmail.com)
**App package:** `com.fcctstudio.callcentertycoon`

Every FCCT player has a Firebase account — either a linked one (Email or Google) or an anonymous account created automatically on first launch. In every case, you have the right to delete that account and its associated data at any time. This page explains **what gets deleted, how to request deletion, and how long it takes**.

## 1. Fastest path — delete in the app

1. Open FCCT.
2. Tap the ⚙ **Settings** button.
3. Scroll to the **Account** section.
4. Tap **🗑 Delete my account**.
5. Type **DELETE** to confirm.

Your account and its data are removed immediately. You will be signed out and returned to the login screen.

Anonymous accounts (players who never signed in with Email or Google) can be deleted through the same in-app path — the underlying Firebase anonymous uid, its cloud save, and its telemetry are erased identically. If for any reason the account button is unavailable, you can also tap **Danger Zone → Restart game from scratch** to wipe all local state, or uninstall the app.

## 2. Alternative — email request

If you cannot access the app (for example, you uninstalled it, lost the device, or the in-app option is unavailable):

Send an email to **[fcct.support@gmail.com](mailto:fcct.support@gmail.com)** from the address you used to sign up (or Google account address used for Google Sign-In) with the subject line:

> **Delete my FCCT account**

Include:

- The email address linked to your FCCT account.
- (Optional) your in-game display name.

We will verify identity by confirming the request comes from the linked email address, then delete your account. If verification fails (for example, the email address isn't linked to any account), we will reply explaining why and, if applicable, ask for a follow-up detail.

**Service level:** we act on verified requests within **7 days** and complete deletion within **30 days** of receipt.

## 3. What gets deleted

| Data | Where it lives | Deleted |
|---|---|---|
| Firebase Auth account (uid, email, hashed password if any) | Google Firebase Auth | Immediately |
| Cloud save (in-game progress, cash, workers, upgrades) | Firestore `users/{uid}/save/latest` | Immediately |
| Local save on this device | On-device file `save.json` | Immediately (in-app path) |
| Local account metadata on this device | On-device file `account.json` | Immediately (in-app path) |

## 4. What is retained (and why)

Some data may be retained temporarily even after account deletion. We keep it only for the limited purposes and retention windows below, and we delete, aggregate, or anonymize account-linked records where technically feasible.

| Data | Purpose | Retention |
|---|---|---|
| Custom gameplay telemetry in Firestore | Understand aggregate feature usage, diagnose errors, prevent abuse, and improve balance | Up to **14 months**, then deleted or aggregated where feasible |
| Ad measurement records (via Google AdMob, when ads are enabled) | Fraud prevention, aggregate advertising performance | As retained under Google's AdMob policies; we keep only minimal placement/reward records if needed |
| Transaction records (once in-app purchases launch) | Legal obligation (tax records) | As required by applicable tax law, typically 7 years |

After account deletion, retained telemetry is no longer used as active account data. Where technically feasible, we delete or anonymize records linked to your Firebase uid; otherwise we keep only restricted backend logs for the limited purposes and retention windows above.

## 5. Third parties

We do not sell your data. We do not share it with data brokers. The only third parties who receive data are the vendors listed in the [Privacy Policy §6](../privacy/#6-third-parties-we-share-data-with) — each acts under Google's terms of service and honors deletion via their own retention policies.

## 6. Questions

Email **[fcct.support@gmail.com](mailto:fcct.support@gmail.com)**. We aim to respond within 3 business days.

---

## Change log

- **2026-07-12** — clarified that anonymous accounts (auto-signed-in on first launch, no email/Google required) are also deletable through the same in-app path.
- **2026-07-09** — initial publication.
