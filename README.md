# Spaarkly / ARShades — Legal Documents

Canonical public source of the **legal documents** for **Spaarkly s.r.l.** and the **ARShades** solutions (Virtual Try-On, VTO Explorer, AR PD Meter, Mirror, Gateway): privacy policies, terms & conditions and cookie policy.

All Spaarkly services reference the documents in this repository. **File paths are stable**: when a document is updated, the content of the file changes but its URL does not — services pointing at these paths always serve the latest version.

Human-readable versions are published via GitHub Pages at **https://spaarkly-srl.github.io/ARS_legal/** (e.g. [/privacy-policy/it/](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/it/), [/privacy-policy-shopify/en/](https://spaarkly-srl.github.io/ARS_legal/privacy-policy-shopify/en/)); the raw URLs below remain the canonical machine-readable endpoints. A machine-readable index of all documents is available in [`manifest.json`](manifest.json).

## ARShades Core Privacy Policy

Current version: **5.4** — last updated **7 July 2026** (see [CHANGELOG](CHANGELOG.md)). The Italian version is the authoritative text; in case of discrepancy, the Italian version prevails.

| Language | File | Raw URL (for services) |
|---|---|---|
| Italiano | [privacy-policy/it.md](privacy-policy/it.md) | `https://raw.githubusercontent.com/Spaarkly-srl/ARS_legal/main/privacy-policy/it.md` |
| English | [privacy-policy/en.md](privacy-policy/en.md) | `https://raw.githubusercontent.com/Spaarkly-srl/ARS_legal/main/privacy-policy/en.md` |
| Français | [privacy-policy/fr.md](privacy-policy/fr.md) | `https://raw.githubusercontent.com/Spaarkly-srl/ARS_legal/main/privacy-policy/fr.md` |
| Deutsch | [privacy-policy/de.md](privacy-policy/de.md) | `https://raw.githubusercontent.com/Spaarkly-srl/ARS_legal/main/privacy-policy/de.md` |
| Español | [privacy-policy/es.md](privacy-policy/es.md) | `https://raw.githubusercontent.com/Spaarkly-srl/ARS_legal/main/privacy-policy/es.md` |
| 日本語 | [privacy-policy/ja.md](privacy-policy/ja.md) | `https://raw.githubusercontent.com/Spaarkly-srl/ARS_legal/main/privacy-policy/ja.md` |

## ARShades VTO for Shopify — App Privacy Policy

Limited to data processed in connection with Shopify; the ARShades end-user experiences launched through the app are governed by the core policy above. The English version is the authoritative text; in case of discrepancy, the English version prevails.

| Language | File | Raw URL (for services) |
|---|---|---|
| English | [privacy-policy-shopify/en.md](privacy-policy-shopify/en.md) | `https://raw.githubusercontent.com/Spaarkly-srl/ARS_legal/main/privacy-policy-shopify/en.md` |
| Italiano | [privacy-policy-shopify/it.md](privacy-policy-shopify/it.md) | `https://raw.githubusercontent.com/Spaarkly-srl/ARS_legal/main/privacy-policy-shopify/it.md` |
| Français | [privacy-policy-shopify/fr.md](privacy-policy-shopify/fr.md) | `https://raw.githubusercontent.com/Spaarkly-srl/ARS_legal/main/privacy-policy-shopify/fr.md` |
| Deutsch | [privacy-policy-shopify/de.md](privacy-policy-shopify/de.md) | `https://raw.githubusercontent.com/Spaarkly-srl/ARS_legal/main/privacy-policy-shopify/de.md` |
| Español | [privacy-policy-shopify/es.md](privacy-policy-shopify/es.md) | `https://raw.githubusercontent.com/Spaarkly-srl/ARS_legal/main/privacy-policy-shopify/es.md` |
| 日本語 | [privacy-policy-shopify/ja.md](privacy-policy-shopify/ja.md) | `https://raw.githubusercontent.com/Spaarkly-srl/ARS_legal/main/privacy-policy-shopify/ja.md` |

## ARShades Services — Terms & Conditions

Current version: **1.2** — effective **7 July 2026**. Covers ARShades Virtual Try-On, VTO Explorer, Mirror, Gateway and Campaign Catalogue; supersedes the ARShades VTO Terms and Conditions of Use dated 21 March 2025. AR PD Meter is governed by its own terms (below). The Italian version is the authoritative text; the English version is a courtesy translation.

| Language | File | Raw URL |
|---|---|---|
| Italiano | [terms/it.md](terms/it.md) | `https://raw.githubusercontent.com/Spaarkly-srl/ARS_legal/main/terms/it.md` |
| English | [terms/en.md](terms/en.md) | `https://raw.githubusercontent.com/Spaarkly-srl/ARS_legal/main/terms/en.md` |

## AR PD Meter — Terms & Conditions

Current version: **1.2** — effective **7 July 2026**. Supplemental to the ARShades Services Terms: measurement disclaimer (indicative estimate, not a medical device, does not replace a professional measurement) and express-consent flow for the derived technical data processed on the EU backend. The Italian version is the authoritative text; the English version is a courtesy translation.

| Language | File | Raw URL |
|---|---|---|
| Italiano | [terms-ar-pd-meter/it.md](terms-ar-pd-meter/it.md) | `https://raw.githubusercontent.com/Spaarkly-srl/ARS_legal/main/terms-ar-pd-meter/it.md` |
| English | [terms-ar-pd-meter/en.md](terms-ar-pd-meter/en.md) | `https://raw.githubusercontent.com/Spaarkly-srl/ARS_legal/main/terms-ar-pd-meter/en.md` |

## Client ARShades Integration Terms — 🧩 TEMPLATE

Current version: **0.1.0** — a parametric **template** (mustache `{{…}}` variables), not published legal terms. Used to generate the per-client ARShades integration terms a merchant can adopt in its own legal docs: the client is the commercial counterparty of its users; Spaarkly provides the technology and remains the data controller for the processing described in the ARShades Privacy Policy. Generated instances are **not** published in this repository and must be reviewed by the client's counsel. Template files are excluded from GitHub Pages (`published: false`) so Liquid does not interpolate the variables — browse them on GitHub or via the raw URLs.

| Artifact | File |
|---|---|
| Governance & rules | [client-terms-template/README.md](client-terms-template/README.md) |
| Full client terms (IT) | [client-terms-template/full/it.md](client-terms-template/full/it.md) |
| Short clause (IT) | [client-terms-template/short-clause/it.md](client-terms-template/short-clause/it.md) |
| Checkout/consent microcopy (IT) | [client-terms-template/microcopy/it.md](client-terms-template/microcopy/it.md) |
| Client intake checklist (IT) | [client-terms-template/intake-checklist/it.md](client-terms-template/intake-checklist/it.md) |
| Variables schema (JSON Schema) | [client-terms-template/schema.json](client-terms-template/schema.json) |

## Cookie Policy — 🚧 DRAFT

Work in progress, not yet in force. Contains `[[…]]` placeholders to complete before production.

| Language | File | Raw URL |
|---|---|---|
| Italiano | [cookie-policy/it.md](cookie-policy/it.md) | `https://raw.githubusercontent.com/Spaarkly-srl/ARS_legal/main/cookie-policy/it.md` |
| English | [cookie-policy/en.md](cookie-policy/en.md) | `https://raw.githubusercontent.com/Spaarkly-srl/ARS_legal/main/cookie-policy/en.md` |

## Versioning

- Each document release is recorded in [CHANGELOG.md](CHANGELOG.md) and tagged in git (e.g. `v5.3` for the core policy).
- Historical versions are available through git history and tags.
- The "Last updated" date inside each document identifies the version in force.

## Consuming from services

- **Direct link** (recommended for the Shopify listing / apps): use the GitHub Pages URLs.
- **Fetch the source**: use the raw URLs above (served as `text/plain`).
- **Programmatic index**: read [`manifest.json`](manifest.json) for the full list of documents, languages, versions and paths.

## Contact

**Spaarkly s.r.l.** — Via della Tecnica n. 18, 85100 Potenza, Italy
Privacy contact: privacy@spaarkly.com

---

© Spaarkly s.r.l. All rights reserved. These documents are published for transparency toward users of Spaarkly/ARShades services; they may not be reused or adapted for other purposes without permission.
