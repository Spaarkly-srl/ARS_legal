---
published: false
---

# TERMS AND CONDITIONS OF USE — AR PD METER

*{{client_trade_name}} — {{website_url}}* </br> *Terms of {{client_legal_name}}, presented before the measurement — generated from the Spaarkly template "Client ARShades Integration Terms — AR PD Meter" v{{template_version}} of {{generated_date}}*

<!-- ============================================================
  MODELLO SPAARKLY — QUESTO FILE NON È UN DOCUMENTO IN VIGORE.
  È il testo white-label mostrato e ACCETTATO nel modulo consenso
  ARShades a nome del Cliente, PRIMA della misurazione AR PD Meter
  (istanze servite dalla collezione Firestore ARS_TermsAndCond).
  Documento AUTOSUFFICIENTE e INDIPENDENTE: non rinvia né incorpora
  i Termini dei Servizi VTO, anche quando il Cliente li usa. Le
  soluzioni VTO hanno un template separato (../client-terms-template/).
  Variabili {{…}} da compilare (v. ../client-terms-template/schema.json);
  i blocchi {{#flag}}…{{/flag}} sono inclusi solo se il flag è attivo.
  I blocchi [CORE] non sono modificabili dal Cliente.
  L'istanza generata deve essere rivista dal consulente legale del
  Cliente prima della pubblicazione.
  ============================================================ -->

<!-- BLOCK ruoli [CORE] -->
## Who provides what

**"{{client_trade_name}}"**, **"we"** or **"our"** means {{client_legal_name}}, with registered office in {{client_registered_office}} ({{client_country}}), {{client_vat}}, which operates {{website_url}} and provides the commercial experience.

**"Spaarkly"** means Spaarkly s.r.l. (P. IVA IT02077620769), which develops and provides **AR PD Meter**, the ARShades feature described below, and is the **data controller** of the personal data processed by that feature. Spaarkly is not the seller of the products presented, does not operate a marketplace and is not an optician, an optometrist or any other eye care professional.

These terms ("AR PD Meter Terms") are presented to the User, together with the [ARShades Privacy Policy](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/en/), before the start of the measurement. By selecting the acceptance checkbox the User accepts them and gives their express consent to the processing described below; without acceptance the measurement does not start. The User may withdraw consent at any time by stopping the measurement or by revoking access to the camera; the withdrawal does not affect the processing already carried out.
<!-- /BLOCK ruoli -->

<!-- BLOCK cos-e [CORE] -->
## What AR PD Meter is

**AR PD Meter** provides an **estimate of the User's pupillary distance (PD)** using the device camera and facial landmark detection. It is a **preliminary digital estimate**, offered to support the selection of eyewear during the purchase experience: **it is not a medical device**, has no medical, clinical or diagnostic purpose and **does not replace a measurement carried out by a qualified vision professional** (such as an optician, an optometrist or an ophthalmologist). The accuracy may be affected by lighting, camera quality, distance, angle, face position and movements.
<!-- /BLOCK cos-e -->

<!-- BLOCK consenso-dati [CORE] -->
## Consent and data processing

The start of the measurement requires the **express consent of the User, given to Spaarkly** as data controller, through the acceptance checkbox presented before the measurement. The consent flow indicates the version and date of these AR PD Meter Terms in force and summarizes the data processed, the purpose, the retention and the methods of withdrawal.

Consent is managed as **local in-experience gating**: the measurement starts only after explicit consent and withdrawal is always available, with immediate interruption of the processing in progress. Since Spaarkly does not identify the end User, **no evidence of consent attributable to the User is retained**: the very start of the measurement, conditional on consent, provides evidence of it.

The camera images are processed on the User's device and **are not transmitted to Spaarkly or stored by Spaarkly**. Only derived technical data (facial landmark coordinates, face orientation data, device information) — not used to identify the User and not capable, on their own, of identifying the User — are transmitted encrypted to Spaarkly's backend in the **European Union**, used exclusively to calculate and return the measurement and **permanently deleted immediately after processing**.{{#mirror_enabled}} When the measurement takes place on a **Mirror** device at our points of sale or showrooms, the processing takes place on the device's local backend, without any transmission to cloud servers.{{/mirror_enabled}}

Where the applicable biometric privacy laws so require, the User's affirmative acceptance constitutes the written consent/release for the processing described, given before any capture. Full details are in the [ARShades Privacy Policy](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/en/), of which Spaarkly is the controller.
<!-- /BLOCK consenso-dati -->

<!-- BLOCK eta [CORE] -->
## Age

AR PD Meter is intended for users who are **at least 18 years old**. A User under 18 may use it only with the consent and under the supervision of a parent or legal guardian.
<!-- /BLOCK eta -->

<!-- BLOCK uso-vendita [CLIENT] -->
## Use in our sales process

{{#prescription_sales_enabled}}For us the AR PD Meter estimate is only a **preliminary supporting data point** and **is never used as the definitive measurement** for the supply of prescription lenses: before eyeglasses are made, the pupillary distance and the other necessary parameters are verified or confirmed by a qualified vision professional, in accordance with our sales process and applicable regulations. The responsibility for such verification is ours, not Spaarkly's.{{/prescription_sales_enabled}}{{^prescription_sales_enabled}}We do not sell prescription lenses through {{website_url}}: the AR PD Meter estimate is used exclusively to support the selection of frames and non-prescription eyewear.{{/prescription_sales_enabled}}
<!-- /BLOCK uso-vendita -->

<!-- BLOCK privacy [CORE] -->
## Privacy

For the processing carried out by AR PD Meter — described above — the **data controller is Spaarkly s.r.l.**: the [ARShades Privacy Policy](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/en/) (contact: privacy@spaarkly.com) applies, presented together with these AR PD Meter Terms. We do not access the data processed by AR PD Meter or the related processing: we receive from Spaarkly exclusively aggregated and anonymized data; for this reason Spaarkly remains the data controller.

For the processing that we carry out as data controller — accounts, orders, support and any other processing connected to {{website_url}} — our [privacy policy]({{client_privacy_url}}) applies.
<!-- /BLOCK privacy -->

<!-- BLOCK ip [CORE] -->
## Intellectual property

AR PD Meter — software, algorithms and interfaces — and the related intellectual property rights are and remain the property of **Spaarkly or its licensors**. No ownership right is transferred to the User; reverse engineering (except as permitted by mandatory law) and any unauthorized use of the feature are prohibited.
<!-- /BLOCK ip -->

<!-- BLOCK terzo-beneficiario [CORE] -->
## Spaarkly as third-party beneficiary

The provisions of these AR PD Meter Terms relating to the technology, the nature of the estimate, the data processing, the intellectual property and the exclusions and limitations connected to them are agreed, in the Client's interest, also for the benefit of Spaarkly, pursuant to Article 1411 of the Italian Civil Code, and Spaarkly may enforce them directly against the User. This clause does not prejudice the rights granted to the User by mandatory law.
<!-- /BLOCK terzo-beneficiario -->

<!-- BLOCK rapporto-documenti [CORE] -->
## Relationship with the other documents

These AR PD Meter Terms apply exclusively to the use of the AR PD Meter feature. Purchases and any other commercial relationship with us remain governed by our [Terms and Conditions]({{client_terms_url}}), which also govern the applicable law and the competent court. For the processing of personal data for which Spaarkly is the controller, the [ARShades Privacy Policy](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/en/) applies. Nothing in these AR PD Meter Terms excludes, limits or prejudices the rights granted to the User by mandatory law, including consumer rights.
<!-- /BLOCK rapporto-documenti -->

<!-- BLOCK contatti [CLIENT] -->
## Contacts

For questions about the purchase experience: **{{support_email}}**.

For matters relating to AR PD Meter: **legal@spaarkly.com**; for ARShades privacy: **privacy@spaarkly.com**.
<!-- /BLOCK contatti -->

---

By selecting the acceptance checkbox or by using AR PD Meter, the User declares that they have read and understood these AR PD Meter Terms, accepts them and gives their express consent to the processing described.
