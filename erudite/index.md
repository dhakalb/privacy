---
layout: default
title: Erudite Privacy Policy
---

# Privacy Policy — Erudite

**Last updated:** 28 March 2026  
**Effective date:** 28 March 2026

Erudite ("the App") is a maths learning application designed for children aged 5–12. We take the privacy of our users — especially children — very seriously. This policy explains what data we collect, how we use it, and how we protect it.

---

## 1. Who We Are

Erudite is developed and operated by Erudite Education ("we", "us", "our"). For privacy enquiries, contact us at: **privacy@erudite.app**

---

## 2. Information We Collect

### 2.1 Data Collected Automatically
- **Anonymous user ID** — a randomly generated identifier with no connection to a real name or email address
- **Year level selection** — chosen during onboarding (e.g. "Year 3")
- **Learning progress** — questions answered, scores, streaks, achievements, lesson completion
- **Session data** — timestamps, question response times (used to adapt difficulty)

### 2.2 Data We Do NOT Collect
- **No personal information** — we do not collect names, email addresses, phone numbers, photos, or physical addresses
- **No location data** — the App does not request or use GPS or IP-based location
- **No contacts or address book** — we never access your contacts
- **No advertising identifiers** — we do not use any advertising SDKs
- **No cookies or web tracking** — the App does not use cookies

---

## 3. How We Use Data

We use the collected data solely for:
- Adapting question difficulty to the learner's level
- Tracking learning progress (streaks, XP, achievements)
- Providing AI tutor responses tailored to the learner's current question
- Improving the App's educational content and features

We **never** use data for advertising, profiling, or selling to third parties.

---

## 4. Third-Party Services

The App uses the following third-party services, all of which process data on our behalf:

| Service | Purpose | Data Shared |
|---------|---------|-------------|
| **Supabase** (Sydney, Australia) | Database, authentication, cloud sync | Anonymous user ID, learning progress |
| **Anthropic Claude** (via Supabase Edge Functions) | AI tutor responses | Question text, student's answer (no personal data) |
| **ElevenLabs** (via server-side API) | Text-to-speech voice generation | Lesson/question text only (no personal data) |

No personal information about any child is shared with these services. All API calls are routed through our server-side edge functions — the child's device never communicates directly with Anthropic or ElevenLabs.

---

## 5. Data Storage & Security

- All data is stored on **Supabase** servers located in **Sydney, Australia**
- Data is encrypted in transit (TLS 1.2+) and at rest
- API keys are stored server-side only and are never included in the app binary
- Anonymous authentication means there are no passwords to compromise
- Local data is stored on-device via AsyncStorage and is not accessible to other apps

---

## 6. Children's Privacy (COPPA & Australian Privacy Act)

Erudite is designed for use by children under 13. We comply with:

- **Children's Online Privacy Protection Act (COPPA)** — United States
- **Australian Privacy Act 1988** and the **Australian Privacy Principles (APPs)**

Specifically:
- We do not knowingly collect personal information from children
- We do not require any personal information to use the App
- We do not display advertising of any kind
- We do not enable social features, chat with strangers, or user-generated content sharing
- A parent or guardian can request deletion of their child's data at any time by contacting us

---

## 7. Parental Controls

The App includes a **PIN-protected Parent Dashboard** that allows parents/guardians to:
- View their child's learning progress by curriculum strand
- See detailed statistics and mastery levels
- Manage app settings

---

## 8. Data Retention & Deletion

- Learning data is retained as long as the App is installed
- Uninstalling the App removes all local data from the device
- Cloud-synced data can be deleted upon request — email **privacy@erudite.app**
- We will respond to deletion requests within 30 days

---

## 9. Changes to This Policy

We may update this policy from time to time. The "Last updated" date at the top of this page will reflect the most recent revision. Continued use of the App after changes constitutes acceptance of the updated policy.

---

## 10. Contact Us

If you have any questions or concerns about this Privacy Policy, please contact us:

**Email:** privacy@erudite.app

---

*This privacy policy is effective as of 28 March 2026.*
