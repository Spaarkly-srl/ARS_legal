---
published: false
---

# TERMS AND CONDITIONS OF USE — ARSHADES FEATURES

*{{client_trade_name}} — {{website_url}}* </br> *Terms of {{client_legal_name}}, presented at the start of the experience — generated from the Spaarkly template "Client ARShades Integration Terms — VTO Services" v{{template_version}} of {{generated_date}}*

<!-- ============================================================
  MODELLO SPAARKLY — QUESTO FILE NON È UN DOCUMENTO IN VIGORE.
  È il testo white-label mostrato e ACCETTATO nel modulo consenso
  ARShades a nome del Cliente per le soluzioni VTO (istanze servite
  dalla collezione Firestore ARS_TermsAndCond, mai pubblicate qui).
  AR PD Meter NON è trattato qui: ha un template separato e
  indipendente (../client-terms-ar-pd-meter-template/).
  Variabili {{…}} da compilare (v. ../schema.json); i blocchi
  {{#flag}}…{{/flag}} sono inclusi solo se il flag è attivo.
  I blocchi [CORE] non sono modificabili dal Cliente (v. ../README.md).
  L'istanza generata deve essere rivista dal consulente legale del
  Cliente prima della pubblicazione.
  ============================================================ -->

<!-- BLOCK ruoli [CORE] -->
## Who provides what

**"{{client_trade_name}}"**, **"we"** or **"our"** means {{client_legal_name}}, with registered office in {{client_registered_office}} ({{client_country}}), {{client_vat}}, which operates {{website_url}} and provides the commercial experience: catalogues and collections, prices, availability, orders, support{{#prescription_sales_enabled}}, prescription management{{/prescription_sales_enabled}} and the entire purchase journey.

**"Spaarkly"** means Spaarkly s.r.l. (P. IVA IT02077620769), which develops and provides the **ARShades** augmented reality software solutions integrated into our experience. Spaarkly is not the seller of the products presented, does not operate a marketplace and is not an optician, an optometrist or any other eye care professional.

These terms ("Terms") are presented to the User, together with the [ARShades Privacy Policy](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/en/), before the start of the experience and govern its use. By clicking "Accept" (or taking an equivalent action) the User accepts them; without acceptance the experience does not start. During the experience the User may re-read the documents at any time and withdraw their consent from the settings.
<!-- /BLOCK ruoli -->

<!-- BLOCK funzionalita [CORE] -->
## The available ARShades features

{{#vto_enabled}}- **Virtual Try-On (VTO)** — the virtual try-on of eyewear in augmented reality via the device camera.{{/vto_enabled}}
{{#viewer_3d_enabled}}- **3D Viewer** — the three-dimensional display that allows 360° exploration of the eyewear models (rotation and zoom) and, where the device supports it, their display in augmented reality.{{/viewer_3d_enabled}}
{{#vto_explorer_enabled}}- **VTO Explorer** — personalized previews of multiple models from a limited number of images captured during the session and processed locally on the device.{{/vto_explorer_enabled}}
{{#mirror_enabled}}- **Mirror** — the virtual try-on experience on a dedicated device at our points of sale or showrooms; the availability and the physical conditions of use of the device are our responsibility.{{/mirror_enabled}}
{{#gateway_enabled}}- **Gateway** — the ARShades platform that offers virtual try-on experiences and unified access to the ARShades experiences and to the brand stores; it may optionally use geolocation, subject to consent.{{/gateway_enabled}}
{{#campaign_catalogue_enabled}}- **Campaign Catalogue** — the curated digital catalogue with which we present selected collections or campaigns; products, prices and commercial information are chosen and managed by us.{{/campaign_catalogue_enabled}}

{{#mobile_app_enabled}}The ARShades features are also available within our mobile application; the download and use of the app are also subject to the terms of the applicable app store (Apple App Store or Google Play).{{/mobile_app_enabled}}

Minimum requirements for the camera-based features: a stable Internet connection, a device equipped with a camera and authorization to access the camera for the duration of the experience. The camera images are processed in real time on the User's device to position the virtual eyewear: they are not stored or transmitted to Spaarkly's servers.
<!-- /BLOCK funzionalita -->

<!-- BLOCK natura [CORE] -->
## Nature of the virtual experience

The virtual try-on and the display of the models are a **visual aid**: due to technical limitations the rendering (appearance, colours, fit, dimensions) may differ from the physical product and varies depending on device, camera, lighting and environment. Purchase decisions remain the User's; the virtual experience does not constitute a guarantee of suitability, availability or appearance of the product. Unless otherwise indicated, the ARShades features are offered to Users free of charge.
<!-- /BLOCK natura -->

{{#shoot_share_enabled}}
<!-- BLOCK shoot-share [CORE] -->
## Photos and "Shoot & Share"

Any images captured during a VTO Explorer session are processed locally on the device used for the experience and are **not automatically uploaded** to Spaarkly's servers. If the experience takes place on a device installed at a point of sale, a showroom, an event venue or another place open to the public and the User chooses to obtain, download or share the final photos ("Shoot & Share" or equivalent functions), **only the final photos selected by the User** are temporarily uploaded to Spaarkly's servers, for the sole purpose of making them available to the User, and are deleted within 24 hours at the latest (earlier, if the User deletes them).
<!-- /BLOCK shoot-share -->
{{/shoot_share_enabled}}

<!-- BLOCK privacy [CORE] -->
## Privacy

For the processing of personal data carried out by the ARShades features — including the facial landmarks processed **in real time and locally on the device** for the sole purpose of positioning the virtual eyewear, without storage or transmission — the **data controller is Spaarkly s.r.l.**: the [ARShades Privacy Policy](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/en/) (contact: privacy@spaarkly.com) applies, presented together with these Terms. We do not access the personal data processed by the ARShades features or the related processing: we receive from Spaarkly exclusively aggregated and anonymized data; for this reason Spaarkly remains the data controller for the ARShades processing.

For the processing that we carry out as data controller — accounts, orders, payments, support, marketing and any other processing connected to {{website_url}} — our [privacy policy]({{client_privacy_url}}) applies.
<!-- /BLOCK privacy -->

<!-- BLOCK venditore [CLIENT] -->
## Our responsibilities as seller

We — and not Spaarkly — are responsible for the products presented and sold on {{website_url}}: prices, availability, product descriptions and statements, conformity, delivery, legal warranty, returns and support, in accordance with our [Terms and Conditions]({{client_terms_url}}).{{#prescription_sales_enabled}} The dispensing of prescription lenses takes place under our responsibility, in compliance with the applicable regulations.{{/prescription_sales_enabled}} Any purchases or other transactions concluded by the User with us are governed exclusively by our terms.
<!-- /BLOCK venditore -->

<!-- BLOCK ip [CORE] -->
## Intellectual property

The ARShades solutions — software, algorithms and interfaces — and the related intellectual property rights are and remain the property of **Spaarkly or its licensors**. The 3D models and the displayed content may belong to us, to Spaarkly or to the respective licensors and are provided for display purposes only. In particular, it is prohibited to copy, reproduce, extract or collect by scraping the 3D models and the content, to decompile or reverse engineer the software (except as permitted by mandatory law) and any unauthorized commercial use of the ARShades solutions.
<!-- /BLOCK ip -->

<!-- BLOCK minori [CLIENT] -->
## Minors

{{#minors_enabled}}The ARShades features are intended for a general audience: Users below the age at which they can validly give consent in relation to information society services in their country of residence (in Italy, 14 years) may use them only with the consent or authorization of a parent or legal guardian, where required by applicable law.{{/minors_enabled}}{{^minors_enabled}}The purchase experience on {{website_url}} is intended for adult users.{{/minors_enabled}}
<!-- /BLOCK minori -->

<!-- BLOCK terzo-beneficiario [CORE] -->
## Spaarkly as third-party beneficiary

The provisions of these Terms relating to the ARShades technology, the nature of the virtual experience, the intellectual property and the exclusions and limitations connected to them are agreed, in the Client's interest, also for the benefit of Spaarkly, pursuant to Article 1411 of the Italian Civil Code, and Spaarkly may enforce them directly against the User. This clause does not prejudice the rights granted to the User by mandatory law.
<!-- /BLOCK terzo-beneficiario -->

<!-- BLOCK rapporto-documenti [CORE] -->
## Relationship with the other documents

These Terms apply to the use of the ARShades features within our experience. Purchases and any other commercial relationship with us remain governed by our [Terms and Conditions]({{client_terms_url}}), which also govern the applicable law and the competent court. For the processing of personal data for which Spaarkly is the controller, the [ARShades Privacy Policy](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/en/) applies. Nothing in these Terms excludes, limits or prejudices the rights granted to the User by mandatory law, including consumer rights.
<!-- /BLOCK rapporto-documenti -->

<!-- BLOCK contatti [CLIENT] -->
## Contacts

For questions about the purchase experience: **{{support_email}}**.

For matters relating to the ARShades features: **legal@spaarkly.com**; for ARShades privacy: **privacy@spaarkly.com**.
<!-- /BLOCK contatti -->

---

By clicking "Accept", or by using the ARShades features after having had the opportunity to review them, the User declares that they have read and understood these Terms and accepts them.
