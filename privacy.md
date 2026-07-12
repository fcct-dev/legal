---
layout: default
title: Privacy Policy — Fraud Call Center Tycoon
permalink: /privacy/
---

# Privacy Policy — Fraud Call Center Tycoon

**Effective date:** 2026-07-12
**Publisher:** FCCT Studio
**Contact:** [fcct.support@gmail.com](mailto:fcct.support@gmail.com)
**App package:** `com.fcctstudio.callcentertycoon`

## 1. What this app is

Fraud Call Center Tycoon ("FCCT," "the game," "we") is a satirical idle-tycoon mobile game about a fictional call-center operation. All characters, schemes, victims, brand names, phone numbers, and events depicted are entirely fictional; any resemblance to real people, companies, or agencies is coincidental and used for parody. The game does not teach real fraud techniques and does not endorse or promote illegal activity.

The game is intended for a mature audience: **you must be at least 13 years old (16 in the EEA/UK, per GDPR Article 8)** to use the app.

**Important Safety Disclaimer:** The game is a local simulation. It does not dial real phone numbers, send actual SMS/text messages, connect to cellular telephone networks, or interact with your device's actual phone dialer, contacts, or call logs in any way. All "calls" and "schemes" are fully virtual, simulated in-game text and animations.

## 2. Information we collect

We collect only the minimum needed to run the game, keep it working, and improve it.

*Note on accounts:* If you launch the game without signing in with email or Google, we automatically sign you in with **Firebase anonymous authentication** — a randomly generated user ID with no personal identifiers (no email, no name). Anonymous sign-in enables cloud save and analytics but does not link to any external identity. You can upgrade an anonymous account to email or Google later without losing progress.

| Category | Examples | Purpose | Retention |
|---|---|---|---|
| **Account** | Firebase Auth user ID (uid — anonymous by default, or linked to your email or Google account if you choose to sign in), email if you use Email sign-in, Google account ID if you use Google Sign-In | Log you in, sync your save across devices | Until you delete your account or 24 months of inactivity |
| **Save data** | Your in-game progress: cash balances, workers, upgrades, schemes, timestamps | Cloud-save so you don't lose progress if you switch devices | Same as account |
| **Gameplay telemetry** | Session start / session end (with per-session aggregates: total taps, crits, mammoths spawned/closed/expired, payout totals and max, closes by role, purchases counter), random session ID, Firebase uid, app version, platform, language, sign-in provider, game stage, and rare event records (raid outcomes, prison events, laundering unlocks, prestige, shop/boost purchases, meta-scam outcomes, short client error messages) | Understand which features work, tune game balance, debug problems, and prevent abuse | Up to 14 months, then deleted or aggregated where feasible |
| **Advertising data** | Android Advertising ID (AAID), consent status, rewarded-ad placement, ad interaction/reward status | Only when real rewarded ads are enabled in a future release (see §4). **In the current release ads are not integrated; we do not read AAID and no ad SDK is initialized.** | Handled mainly by Google AdMob under Google's policies once ads are live; we keep only minimal placement/reward records if needed |
| **Approximate location** | Country/region inferred by service providers from IP address (not GPS) | Regional ad consent/compliance when ads are enabled | Session-only or as retained by the relevant provider |
| **Device/app info** | Platform, app version, language; ad providers may also receive device model/OS info when ads are enabled | Debugging, compatibility, ad delivery, fraud prevention | Up to 14 months for our telemetry; provider retention varies |

**We do NOT collect or access:** your device's precise GPS location, real phone contacts, real call logs, SMS/text messages, photos, microphone input, web browsing history, or the Android Advertising ID (until ads are integrated in a future release).

## 3. Legal bases (GDPR, if you're in the EEA/UK)

- **Contract** — providing you the game service (save, account)
- **Consent** — personalized ads, where real ads are enabled and consent is legally required. You can decline in the consent form or in Settings → Manage ad consent.
- **Legitimate interest** — security, fraud prevention, product analytics, game balancing, and debugging
- **Legal obligation** — tax records for in-app purchases (when we roll out IAP)

## 4. Advertising

FCCT is designed to show **optional rewarded video ads** — short videos you choose to watch in exchange for in-game bonuses. We do NOT show forced interstitials or banners.

**Current release status: ads are NOT integrated.** No ad SDK is loaded, no Android Advertising ID (AAID) is read, and no ad-network requests are made. Rewarded-ad UI (buttons like "Watch ad") is hidden while ads are not integrated so nothing about ads reaches your device.

When real ads are enabled in a future release, our ad partner is **Google AdMob**. When you first watch an ad, you may see a consent form (Google's User Messaging Platform / UMP) asking whether ads can be personalized. You can:
- **Accept** — see ads relevant to your interests (usually higher payout for us; keeps FCCT free)
- **Decline** — see generic ads, everything else unchanged

You can change this decision any time: **Settings → Ads & privacy → Manage ad consent**.

If you're in California, the same form serves as your CCPA "Do Not Sell / Do Not Share" opt-out.

AdMob's privacy policy: [policies.google.com/technologies/ads](https://policies.google.com/technologies/ads)

## 5. In-app purchases

When we enable IAP (currently disabled), purchases are processed by **Google Play Billing**. We don't see or store your credit card. Google Play stores the transaction record and shares only the purchase status and product ID with us.

Refunds are handled through Google Play according to Google Play's policies.

## 6. Third parties we share data with

| Party | What we share | Why |
|---|---|---|
| Google Firebase (Authentication, Cloud Firestore) | Account, cloud save, custom gameplay telemetry, auth tokens | Login, backend services, cloud save, diagnostics |
| Google Sign-In / Android Credential Manager | Google ID token, email/display name if provided by Google | Optional Google sign-in |
| Google AdMob | Advertising ID, coarse region, consent status, ad interaction data | Optional rewarded ads, when enabled |
| Google Play Billing | Purchase status, product ID, purchase token/transaction reference | IAP transactions, when enabled |

Each has its own privacy policy — we don't share more than the fields listed above.

We do NOT sell your data. We do NOT share it with data brokers.

Google Privacy Policy: [policies.google.com/privacy](https://policies.google.com/privacy)

Firebase privacy and security information: [firebase.google.com/support/privacy](https://firebase.google.com/support/privacy)

## 7. Your rights

### Everyone
- **Access** — email [fcct.support@gmail.com](mailto:fcct.support@gmail.com) and we'll send you a copy of your data
- **Delete** — Settings → Account → Delete my account (in-app), OR email us. Full instructions and email-based path: [Account & Data Deletion](../data-deletion/). We act within 7 days and complete within 30 days.
- **Correct** — for account info, edit in Settings; for anything else, email us.

### EEA / UK residents
Additional rights under GDPR:
- Restrict processing
- Object to legitimate-interest processing
- Data portability (JSON export via email)
- Withdraw consent for personalized ads any time
- Lodge a complaint with your local data protection authority

### California residents
Additional rights under CCPA/CPRA:
- Right to know what personal information we collect
- Right to delete
- Right to correct
- Right to opt out of "sale" or "sharing" (we don't sell, but AdMob personalization can qualify as "sharing" for cross-context behavioral advertising — the ads consent form serves as your opt-out mechanism)
- Right to non-discrimination for exercising your rights

Send requests to: [fcct.support@gmail.com](mailto:fcct.support@gmail.com). We verify identity by requiring the request come from the email address linked to your account.

### Children (under 13)
FCCT is not for children under 13. We do not knowingly collect data from users under 13. If you believe your child has provided us data, contact us and we will delete it.

## 8. Security

- Firebase and Firestore data are transmitted over HTTPS and encrypted at rest by Google
- Saves are HMAC-SHA256 signed (tamper-evident)
- Cloud saves are uploaded on a throttled schedule and skipped when the payload is unchanged (SHA-256 content hash), which minimises the amount of data leaving your device
- New installs are automatically signed in with **Firebase anonymous authentication** — a random uid with no personal identifiers (no email, no name required)
- Firebase App Check will be required before we allow public production traffic (planned before soft launch)
- Passwords (if you use Email sign-in) are hashed by Firebase Auth using PBKDF2 — we never see the plaintext

## 9. International data transfers

Firebase, Google Play, and AdMob may process data in countries other than where you live. Where required, Google and/or FCCT rely on appropriate transfer mechanisms such as standard contractual clauses or other legally recognized safeguards.

## 10. Changes to this policy

We'll post updates here with a new "Effective date." Material changes will trigger an in-app notification.

## 11. Contact

**Email:** [fcct.support@gmail.com](mailto:fcct.support@gmail.com)
**Publisher:** FCCT Studio

---

## Change log

- **2026-07-12** — clarified age gate (13, or 16 in EEA/UK per GDPR Art. 8); reflected anonymous-auth default for fresh installs (no more purely-local "Guest" mode); telemetry rewrite from sampled per-event to session-end aggregate counters; explicitly stated that ads are not integrated in the current release and AAID is not collected; added cloud-save hash-skip note in §8.
- **2026-07-09** — initial publication.
