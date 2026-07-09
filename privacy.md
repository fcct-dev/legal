---
layout: default
title: Privacy Policy — Fraud Call Center Tycoon
permalink: /privacy/
---

# Privacy Policy — Fraud Call Center Tycoon

**Effective date:** 2026-07-09
**Publisher:** FCCT Studio
**Contact:** [fcct.support@gmail.com](mailto:fcct.support@gmail.com)
**App package:** `com.fcctstudio.callcentertycoon`

## 1. What this app is

Fraud Call Center Tycoon ("FCCT," "the game," "we") is a satirical idle-tycoon mobile game about a fictional call-center operation. All characters, schemes, and victims depicted are fictional. The game is intended for a mature audience (13+ per Google Play content rating).

**Important Safety Disclaimer:** The game is a local simulation. It does not dial real phone numbers, send actual SMS/text messages, connect to cellular telephone networks, or interact with your device's actual phone dialer, contacts, or call logs in any way. All "calls" and "schemes" are fully virtual, simulated in-game text and animations.

## 2. Information we collect

We collect only the minimum needed to run the game, keep it working, and improve it.

*Note: If you play using a "Guest" account, your game progress is stored only locally on your device, and no personal account identifiers or email addresses are sent to our servers.*

| Category | Examples | Purpose | Retention |
|---|---|---|---|
| **Account** | Firebase Auth user ID (uid), email if you use Email sign-in, Google account ID if you use Google Sign-In | Log you in, sync your save across devices (does not apply to Guest accounts) | Until you delete your account or 24 months of inactivity |
| **Save data** | Your in-game progress: cash balances, workers, upgrades, schemes, timestamps | Cloud-save so you don't lose progress if you switch devices (does not apply to Guest accounts) | Same as account |
| **Analytics events** | Session start/end, mammoth conversions (20% sampled), raid outcomes, laundering unlocks, prestige, boost purchases, errors | Understand which features work and which cause problems | 14 months (Google Analytics default) |
| **Advertising ID** | Android Advertising ID (AAID) via AdMob | Personalized ads (opt-in via consent form), frequency capping, fraud prevention | 12 months after last use |
| **Approximate location** | Derived from IP address, country + region only (not GPS) | Regional ad compliance (GDPR/CCPA gating), currency detection | Session-only |
| **Device info** | OS version, device model, app version, language | Debug crashes, plan support | 90 days |

**We do NOT collect or access:** your device's precise GPS location, real phone contacts, real call logs, SMS/text messages, photos, microphone input, or web browsing history.

## 3. Legal bases (GDPR, if you're in the EEA/UK)

- **Contract** — providing you the game service (save, account)
- **Consent** — personalized ads (you can decline in the consent form on first launch or in Settings → Manage ad consent). Analytics is legitimate interest with anonymized IDs.
- **Legitimate interest** — security, fraud prevention, debugging crashes
- **Legal obligation** — tax records for in-app purchases (when we roll out IAP)

## 4. Advertising

FCCT shows **rewarded video ads** — short videos you choose to watch in exchange for in-game bonuses. We do NOT show forced interstitials or banners.

Our ad partner is **Google AdMob**. When you first watch an ad, you'll see a consent form (Google's User Messaging Platform / UMP) asking whether ads can be personalized. You can:
- **Accept** — see ads relevant to your interests (usually higher payout for us; keeps FCCT free)
- **Decline** — see generic ads, everything else unchanged

You can change this decision any time: **Settings → Ads & privacy → Manage ad consent**.

If you're in California, the same form serves as your CCPA "Do Not Sell / Do Not Share" opt-out.

AdMob's privacy policy: [policies.google.com/technologies/ads](https://policies.google.com/technologies/ads)

## 5. In-app purchases

When we enable IAP (currently disabled), purchases are processed by **Google Play Billing**. We don't see or store your credit card. Google Play stores the transaction record and shares only the purchase status and product ID with us.

Refunds: handled through Google Play per their standard 48-hour policy.

## 6. Third parties we share data with

| Party | What we share | Why |
|---|---|---|
| Google Firebase (Auth, Firestore, Analytics) | Account, save, analytics events | Backend services |
| Google AdMob | Advertising ID, coarse region, consent status | Serving ads |
| Google Play Billing | Purchase status, product ID | IAP transactions |

Each has its own privacy policy — we don't share more than the fields listed above.

We do NOT sell your data. We do NOT share it with data brokers.

## 7. Your rights

### Everyone
- **Access** — email [fcct.support@gmail.com](mailto:fcct.support@gmail.com) and we'll send you a copy of your data
- **Delete** — Settings → Account → Delete account (when we ship account deletion) OR email us. We delete within 30 days.
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

- Firestore data is encrypted at rest and in transit
- Saves are HMAC-SHA256 signed (tamper-evident)
- Firebase App Check will be required before we allow public traffic (planned before soft launch)
- Passwords (if you use Email sign-in) are hashed by Firebase Auth using PBKDF2 — we never see the plaintext

## 9. International data transfers

Firebase project region: **europe-west1** (Belgium). Your data is stored in the EU. AdMob and Google Play Billing may process data in other regions per Google's standard contractual clauses.

## 10. Changes to this policy

We'll post updates here with a new "Effective date." Material changes will trigger an in-app notification.

## 11. Contact

**Email:** [fcct.support@gmail.com](mailto:fcct.support@gmail.com)
**Publisher:** FCCT Studio

---

## Change log

- **2026-07-09** — initial publication.
