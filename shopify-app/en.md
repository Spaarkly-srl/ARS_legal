# ARShades VTO for Shopify Privacy Policy

Draft version for Shopify submission  
Last updated: July 6, 2026

This Privacy Policy describes how **Spaarkly s.r.l.** ("Spaarkly", "ARShades", "we", "us", or "our") processes personal data and other information in connection with the **ARShades VTO for Shopify** app (the "Shopify App" or the "App").

This policy is specific to the Shopify App and is limited to the data processed in connection with Shopify (merchant, store, product, configuration and attribution data). The processing performed by ARShades end-user services — such as Virtual Try-On, 3D/AR Viewer and AR PD Meter — that may be launched through the App is not covered by this policy and is governed by the **ARShades core Privacy Policy** (version 5.3), available at [https://github.com/Spaarkly-srl/privacy-policies](https://github.com/Spaarkly-srl/privacy-policies/blob/main/core/en.md) and displayed to shoppers within the ARShades experiences.

## 1. Controller

Spaarkly s.r.l. acts as an independent controller for the personal data processed through the Shopify App.

**Controller:** Spaarkly s.r.l.  
**Registered address:** Via della Tecnica n. 18, 85100 Potenza, Italy  
**Privacy contact:** privacy@spaarkly.com

## 2. What the Shopify App Does

The Shopify App connects a merchant's Shopify store to the ARShades platform. It allows merchants to:

* connect an ARShades license token to a Shopify store;
* create or connect an ARShades catalogue;
* match Shopify products and variants with ARShades 3D/VTO assets using SKU, EAN or similar product identifiers;
* add theme blocks for Virtual Try-On, 3D/AR Viewer and AR PD Meter;
* customize colors, button styles, modal settings and certain branding assets;
* use Shopify Web Pixel events for VTO/3D attribution and conversion analytics.

The App is free to install on Shopify. The underlying ARShades service may require a separate ARShades subscription purchased outside Shopify.

## 3. Categories of Data We Process

### 3.1 Merchant and Shopify Admin Data

When a merchant installs or uses the App, we may process:

* Shopify shop domain and store URL;
* Shopify OAuth session data;
* access token and authorized scopes;
* Shopify admin user identifiers and, where provided by Shopify, first name, last name, email address, locale, collaborator status, account owner status and email verification status;
* App installation, configuration and usage status.

These data are used to authenticate the merchant, operate the embedded App, maintain the App session and provide support and security.

### 3.2 ARShades License, Catalogue and Configuration Data

We process information needed to connect the Shopify store to ARShades, including:

* ARShades license token or subscription identifier;
* ARShades catalogue ID, catalogue name and catalogue status;
* 3D viewer ID and ARShades service capabilities, such as VTO or AR PD Meter availability;
* App configuration saved as Shopify metafields, including `licenseId`, `catalogueId`, `viewerId`, `webDomain`, `studioDomain`, `has_vto` and `has_arpd`;
* style settings such as colors, modal settings and button settings;
* merchant-uploaded branding assets, such as a logo used in ARShades permission or policy screens.

### 3.3 Shopify Product and Variant Data

To match products with ARShades assets and display VTO/3D features only where available, the App may read and process:

* Shopify product ID, title, handle and featured image URL;
* Shopify variant ID;
* SKU, barcode, EAN or UPC;
* existing ARShades metafield values;
* ARShades catalogue product and variant identifiers.

The App may write ARShades technical metafields to Shopify variants, including `catalogueVariantId` and `catalogueProductId`. These metafields are used by the storefront theme blocks to determine whether a product or variant can launch ARShades VTO or 3D/AR Viewer.

### 3.4 Storefront Data Processed by the App

When a shopper uses VTO or 3D/AR Viewer on the merchant's storefront, the App may process the following technical, non-profile data:

* product and variant identifiers;
* ARShades catalogue identifiers;
* selected or last-tried variant identifiers;
* device, browser, language and session information;
* technical events indicating that a VTO or 3D session was opened.

These data are used to display the correct experience on the storefront and to power the attribution analytics described in Section 3.6.

### 3.5 ARShades End-User Experiences (VTO, 3D/AR Viewer, AR PD Meter)

The camera-based processing that takes place within the ARShades experiences launched from the storefront — including Virtual Try-On rendering and the AR PD Meter pupillary distance calculation — is performed by the ARShades services, not by the Shopify App, and is governed by the ARShades core Privacy Policy.

In summary, and as described in that policy: camera images and video streams are not stored; no facial templates or biometric identifiers are created; and, for AR PD Meter, camera-derived technical data that do not identify the shopper may be temporarily transmitted to the ARShades backend located in the European Union, used only to return the measurement result and discarded after processing. The Shopify App itself does not access, store or receive camera data.

### 3.6 Shopify Web Pixel and Conversion Analytics

The App uses a Shopify Web Pixel to measure VTO/3D attribution and conversion performance. The pixel may process:

* shop domain;
* event type and timestamp;
* a pseudonymous VTO/3D session ID;
* product and variant identifiers;
* ARShades catalogue product and variant identifiers;
* cart identifiers for add-to-cart attribution;
* checkout/order identifiers, total price, currency and line item metadata for purchase attribution;
* whether the purchase occurred after a VTO/3D session or without a VTO/3D session, for comparison analytics.

The pixel is designed not to send direct shopper profile data such as name, email address, phone number or shipping address to the ARShades analytics backend.

The storefront pixel may use browser local storage to remember an active VTO/3D session for attribution. This local session data expires after 7 days or is cleared after a tracked purchase.

The pixel is loaded by Shopify's pixel manager only where the visitor's consent matches the consent categories declared by the App (such as `analytics`), in accordance with Shopify's Customer Privacy API and the merchant's consent configuration. We honor these consent signals and do not process pixel events collected without the required consent.

## 4. Purposes and Legal Bases

We process the data described above for the following purposes:

* installing, authenticating and operating the Shopify App;
* connecting the merchant's store to an ARShades license and catalogue;
* synchronizing product and variant metadata with ARShades;
* enabling VTO, 3D/AR Viewer and AR PD Meter on the storefront;
* maintaining Shopify metafields and App configuration;
* measuring VTO/3D attribution, add-to-cart events and purchase conversion analytics;
* securing the App, preventing abuse and troubleshooting technical issues;
* complying with Shopify app review, privacy and compliance requirements;
* responding to privacy requests and legal obligations.

Depending on the context and applicable law, the legal bases may include performance of a contract, legitimate interests, compliance with legal obligations, and consent where required, including camera access or analytics consent requirements.

## 5. Data Retention

We retain data only for as long as needed for the purposes described in this policy.

* Active App configuration, Shopify metafields, product/variant mappings and OAuth sessions are retained while the App remains installed and the data are needed to operate the service.
* Store-specific App data are deleted or anonymized when Shopify sends a valid `shop/redact` compliance webhook, unless retention is required by law or for legitimate security purposes.
* Pixel analytics, conversion events, technical logs, session data and similar historical data are retained for up to 14 months and are then aggregated or anonymized.
* Merchant-uploaded branding assets and style settings are retained while they are needed for the active service and removed or anonymized after deletion, uninstall or applicable retention expiry.
* Data processed within ARShades end-user experiences (including AR PD Meter) are retained as described in the ARShades core Privacy Policy.

## 6. Shopify Privacy and Compliance Webhooks

The App implements Shopify privacy and compliance webhook endpoints for:

* `customers/data_request`;
* `customers/redact`;
* `shop/redact`.

Webhook requests are verified using Shopify's HMAC signature; requests with an invalid signature are rejected. We complete data request and redaction actions within 30 days of receiving the webhook.

The App database does not store direct end-customer profile data such as shopper name, email address, phone number or shipping address. For customer-level requests, we verify the Shopify webhook and respond according to the App's data holdings.

`shop/redact` is sent by Shopify 48 hours after the App is uninstalled. Upon receipt, we delete the shop's stored App data, including Shopify sessions, synced variant mappings and shop pixel settings, subject to legal or security retention requirements.

## 7. Sharing and Subprocessors

We share data only as needed to operate, secure and support the App and ARShades services.

Confirmed service providers and infrastructure used for the Shopify App and related ARShades services include:

* Shopify, for app installation, OAuth, Admin API, theme extensions, Customer Events and Web Pixel infrastructure;
* Vercel, for hosting the Shopify App;
* Neon/Vercel Postgres, for App database hosting;
* Google Cloud/Firebase, for ARShades backend functions and analytics processing, with data processed in European Union regions;
* Cloudways CDN, for serving ARShades storefront bundle assets.

These providers process data under their own terms and applicable data processing commitments. We do not sell or share (as defined by the California Consumer Privacy Act) shopper personal data. We do not use Shopify App data for unrelated advertising, facial recognition, biometric identification or AI model training, and we do not carry out automated decision-making that produces legal or similarly significant effects.

A data processing agreement (DPA) covering the App's processing is available to merchants upon request at privacy@spaarkly.com.

## 8. International Transfers

The Shopify App and ARShades analytics and processing services are configured to process and store relevant data in the European Union where applicable.

If a service provider processes personal data outside the European Economic Area, we use appropriate safeguards required by applicable law, such as Standard Contractual Clauses or equivalent transfer mechanisms.

## 9. Security

We use technical and organizational measures designed to protect the data processed by the App, including:

* HTTPS/TLS for data in transit;
* encryption at rest for the App database;
* access controls and authentication;
* Shopify OAuth and webhook verification;
* database access controls;
* minimization of requested Shopify scopes;
* operational logging and monitoring for security and troubleshooting.

No method of transmission or storage is completely secure, but we work to maintain safeguards appropriate to the nature of the data and the risks involved.

### Security Incident Response

If a security incident affects data processed by the App, we will assess the incident under Article 33 GDPR, mitigate it as quickly as possible and notify the competent supervisory authority within 72 hours where required. Because we hold merchant contact details, we will notify affected merchants directly and without undue delay, and we will cooperate with Shopify's incident processes where applicable.

## 10. Shopper Camera Permissions

Camera access is requested by the shopper's browser or device operating system only within the ARShades experiences (VTO, AR PD Meter). Shoppers can refuse or revoke camera access through browser or device settings; if refused, those experiences may not function. The Shopify App itself does not access the camera.

How camera data are processed within the ARShades experiences is described in the ARShades core Privacy Policy.

## 11. Children's Privacy

The App is intended for use by Shopify merchants and their storefront shoppers. ARShades services are not intended to knowingly collect personal data from children below the applicable age of digital consent without appropriate consent from a parent or guardian.

If you believe that a child has provided personal data through ARShades without appropriate consent, contact us at privacy@spaarkly.com.

## 12. Your Rights

Depending on your location, you may have rights to access, correct, delete, restrict, object to, or receive a copy of your personal data.

Merchants may contact us at privacy@spaarkly.com. Shoppers may also contact the merchant whose store they visited, or contact Spaarkly directly where Spaarkly acts as controller for ARShades processing.

We may need information such as shop domain, approximate date/time, event identifiers, device/session details or other information to locate relevant records.

You also have the right to lodge a complaint with a supervisory authority, such as the Italian Garante per la Protezione dei Dati Personali ([www.garanteprivacy.it](https://www.garanteprivacy.it)) or the competent authority in your country of residence.

## 13. Changes to This Policy

We may update this Privacy Policy to reflect changes to the Shopify App, ARShades services, legal requirements or operational practices. When we update the policy, we will revise the "Last updated" date.

## 14. Contact

For privacy questions or requests, contact:

**Spaarkly s.r.l.**  
Via della Tecnica n. 18  
85100 Potenza, Italy  
Email: privacy@spaarkly.com
