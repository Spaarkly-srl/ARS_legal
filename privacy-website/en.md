# ARSHADES WEBSITE — PRIVACY POLICY

> ⚠️ **DRAFT — NOT FINAL.** Document pending legal review, not yet in force. [[Prerequisites for sign-off: (1) persistence of `privacyNoticeAcknowledged*` (+ version and language) in the registration backend; (2) verification/activation of the Firestore TTL policy on `tokenExpiry` for `PendingRegistration` in staging and production; (3) implementation of the demo form backend flow (POST + ZeptoMail + Zoho Bigin) — §2.e describes the target state; (4) verification of console settings: GA4 with data sharing with other Google products disabled, ZeptoMail without content retention and without open/click tracking; (5) verification of the Zoho DPA and sub-processor list (extra-EEA access) for ZeptoMail and Bigin.]]

*ARShades marketing website* </br> *Version: draft — Last updated: 22 July 2026*

This **Privacy Policy** describes how **Spaarkly s.r.l.** (“Spaarkly”, “we”) processes your personal data when you visit or use the **website presenting the ARShades solutions** (the “Site”).

This document concerns **the Site only**. The processing carried out within the **ARShades product experiences** (Virtual Try-On, 3D Viewer, VTO Explorer, AR PD Meter, VTO Mirror, Gateway, Campaign Catalogue) is governed by the [Privacy Policy of the ARShades solutions](../privacy-policy/en.md). For the cookies and similar technologies used by the Site, see the [Website Cookie Policy](../cookie-policy/en.md).

## 1. Data controller

The data controller is **Spaarkly s.r.l.**, Via della Tecnica n. 18, 85100 Potenza (Italy).
For any matter concerning data protection you can write to us at **privacy@spaarkly.com**.

## 2. What data we process, why, and on what legal basis

### a) Browsing data and service logs

While you browse, the systems hosting the Site (Google Firebase infrastructure, **europe-west1** region, Belgium) automatically record technical data whose transmission is implicit in Internet protocols: IP address, date and time of the request, requested page, response code, browser user-agent. We use these logs exclusively to ensure the **operation, security and diagnostics** of the Site.

- **Legal basis:** legitimate interest (art. 6(1)(f) GDPR) in the proper and secure operation of the Site.
- **Retention:** for the time strictly necessary for security and diagnostic purposes, normally no longer than **30 days**.

### b) Site usage statistics (Google Analytics 4) — only with your consent

If you enable the “Analytics” category — by accepting all cookies from the banner or by selecting it in the preferences — we use **Google Analytics 4** for aggregate statistics on the Site's usage (pages visited, origin, interactions). Analytics is configured in a privacy-friendly mode: consent denied by default (**Google Consent Mode v2**), **IP address anonymization**, no Google Signals, no advertising or remarketing functionality, no cross-site profiling.

- **Legal basis:** consent (art. 6(1)(a) GDPR), revocable at any time via the “Cookie preferences” link in the footer.
- **Retention:** user-level and event-level data collected by Google Analytics 4 is retained for a maximum of **14 months**; aggregate statistical reports, which contain no personal data, may be kept longer.
- Refusing consent has no consequence whatsoever on your use of the Site.

### c) Proof of your cookie choices

When you make a choice in the cookie banner (acceptance, refusal or customisation), we record on our servers a **minimal proof of the choice**: a random identifier, the timestamp, the version and **language** of the policy shown in the banner, the categories and the action — **without IP address or user-agent**.

- **Legal basis:** legitimate interest (art. 6(1)(f) GDPR) in fulfilling the obligation to demonstrate consent (accountability, arts. 5(2) and 7(1) GDPR).
- **Retention:** up to **26 months**, then automatic removal.

### d) ARShades Studio registration request form

The Site hosts a form through which your company can request registration on the **ARShades Studio** platform. The data collected is:

- **company data:** company name, country, VAT number, company website, registered-office address (street, postal code, city, province) and — for Italy only — SDI code and/or PEC certified email address;
- **contact details of the contact person:** first name, last name, business email, role in the company and, optionally, phone number;
- **date and time** of your acceptance of the Terms and Conditions and of your acknowledgement of this notice, together with the **version and language** of the notice displayed.

The request undergoes **automated eligibility checks** (email and phone number format, technical verification of the business email domain, VAT number format): these are technical checks with no legal effects on the person; in case of a negative outcome you can always contact us at privacy@spaarkly.com.

When you submit the form, the data is sent to the ARShades backend (Google Cloud, **europe-central2** region, Poland) and kept in a holding area until your email address is verified: we send you a verification email (sender `no-reply@arshades.com`, through the provider **ZeptoMail** — Zoho Corporation, European endpoint) containing a link valid for **7 days**. If you do not complete the verification within that period, **the request data is deleted automatically**; the email provider's technical delivery logs are retained for approximately **60 days**. We do not record IP address or user-agent together with the request.

Upon completion of the verification and registration, the data flows into your ARShades Studio account and is processed in accordance with the privacy notice made available on the platform and the applicable contractual terms.

- **Legal basis:** legitimate interest (art. 6(1)(f) GDPR) of Spaarkly and of the requesting company in handling the registration request submitted by the company contact person; where you act on your own behalf as a professional or sole trader, performance of pre-contractual measures taken at your request (art. 6(1)(b) GDPR).
- **Retention:** **7 days** for unverified requests; upon completion, according to the terms applicable to the ARShades Studio account.
- Providing the data marked as mandatory is necessary to follow up on the request; without it, the registration cannot be completed. The phone number is optional.

### e) “Request a demo” form

The Site hosts a form to request a demo of the ARShades solutions. The data collected is: first and last name, business email, company, role, country, catalogue type and size, areas of interest and, optionally, a message. We use this data to **assess and handle your demo request and to contact you back** for that purpose. The request is recorded in our CRM **Zoho Bigin** (European data center) and the related email communications are sent through **ZeptoMail** (Zoho Corporation, European endpoint).

- **Legal basis:** legitimate interest (art. 6(1)(f) GDPR) of Spaarkly and of the requesting company in handling the request submitted by the company contact person; where you act on your own behalf as a professional or sole trader, performance of pre-contractual measures taken at your request (art. 6(1)(b) GDPR).
- **Retention:** **24 months** from the last meaningful contact, unless a contractual relationship is established.
- Providing the data marked as mandatory is necessary to follow up on the request; the message is optional.

### f) Address autocomplete (Google Places) — only at your request

In the registration form, the address field offers autocomplete suggestions based on the **Google Maps Places API**. The service activates **only when you start typing in the address field**: from that moment your browser establishes a connection with Google's servers — which entails the communication to Google of your **IP address and technical browser data** — and the typed text is transmitted to Google to generate the suggestions; when you select a suggestion, Google returns the structured address. For this service **Google acts as an independent data controller** (Google Controller-Controller Terms): for information see [Google's privacy policy](https://policies.google.com/privacy). You can always enter the address manually: if you do not type in the field with suggestions active, no data is sent to Google.

- **Legal basis:** legitimate interest (art. 6(1)(f) GDPR) in facilitating the completion of the form; the service activates only following an explicit action of yours, and manual entry always remains available.

### g) Restricted admin area

The Site includes a non-public administrative area, reserved for authorised Spaarkly personnel, protected by authentication (**Firebase Authentication**) and technical session cookies. The area does not concern visitors of the Site; the related cookies are listed in the [Cookie Policy](../cookie-policy/en.md).

## 3. Recipients of the data

The data is processed by authorised Spaarkly personnel and by the following providers:

| Provider | Service | Role | Processing location |
|---|---|---|---|
| Google Ireland Ltd. / Google LLC | Hosting and database infrastructure (Firebase, Google Cloud) | Data processor | EU (europe-west1, europe-central2) |
| Google Ireland Ltd. / Google LLC | Google Analytics 4 (only with your prior consent) | Data processor — data sharing with other Google products and services is disabled | EU/USA |
| Google Ireland Ltd. / Google LLC | Google Maps Places API (only at your request) | **Independent data controller** (Google Controller-Controller Terms) | EU/USA |
| Zoho Corporation (ZeptoMail) | Sending of verification and service emails | Data processor | EU (European endpoint) |
| Zoho Corporation (Bigin) | CRM for handling demo requests | Data processor | EU (European data center) |

We do not sell your personal data, nor do we share it with third parties for marketing purposes.

## 4. International transfers

The data is processed mainly within the European Union. Where a provider (in particular **Google LLC** for Google Analytics 4 and the Google Maps APIs) processes data in the United States, the transfer is supported, as the case may be: by the European Commission's adequacy decision for the **EU–U.S. Data Privacy Framework**, valid only for certified U.S. entities (Google LLC is certified); and/or by the **Standard Contractual Clauses** adopted by the European Commission. Data entrusted to **Zoho Corporation** (ZeptoMail, Bigin) is hosted in data centres within the European Union; any technical access by Zoho group companies established outside the European Economic Area (for example, for support purposes) is governed by the **Standard Contractual Clauses** included in the provider's Data Processing Addendum. [[Verification in progress: Zoho DPA and sub-processor list for ZeptoMail and Bigin.]] You can obtain a copy of the applicable safeguards by writing to **privacy@spaarkly.com**. For the Google Places service, Google processes the data as an independent data controller in accordance with its own privacy policy.

## 5. Retention periods — summary

| Processing | Retention |
|---|---|
| Service and security logs | Normally no longer than 30 days |
| Google Analytics 4 statistics | User/event data: maximum 14 months (aggregate reports contain no personal data) |
| Proof of cookie choices | Up to 26 months |
| Unverified registration requests | 7 days |
| Email provider delivery logs (ZeptoMail) | Approximately 60 days |
| Demo requests in the CRM | 24 months from the last meaningful contact |
| Cookie choice (`ars_consent` cookie on your device) | 12 months |

## 6. Data subject rights

Within the limits of arts. 15–22 GDPR, you have the right to obtain **access** to your data, **rectification**, **erasure**, **restriction** of processing and **portability**, as well as to **object** to processing based on legitimate interest and to **withdraw your consent** at any time (for analytics, via the “Cookie preferences” link in the footer), without affecting the lawfulness of the processing carried out before the withdrawal.

You can exercise your rights by writing to **privacy@spaarkly.com**. You also have the right to lodge a complaint with the competent supervisory authority — for Italy, the Italian Data Protection Authority (**Garante per la protezione dei dati personali** — www.garanteprivacy.it).

## 7. Minors

The Site and the ARShades Studio services are intended for a professional audience and are not directed at minors. We do not knowingly collect personal data of minors through the Site.

## 8. Changes to this Privacy Policy

We may update this Privacy Policy to reflect changes to the Site, to the processing activities or to the applicable law. The updated version is published on this page with its last-updated date; in case of substantial changes we will give notice on the Site.

## 9. Contacts

Spaarkly s.r.l. — Via della Tecnica n. 18, 85100 Potenza (Italy) — privacy@spaarkly.com.

---

© Spaarkly s.r.l. All rights reserved.
