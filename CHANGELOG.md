# Changelog

## Repository

### 2026-07-07 — riorganizzazione come hub legale
- Il repository passa da "solo privacy policy" a **hub dei documenti legali pubblici** (privacy, termini, cookie policy).
- Rinominato `core/` → `privacy-policy/` e `shopify-app/` → `privacy-policy-shopify/` (aggiornati di conseguenza gli URL raw/Pages e i link interni).
- Aggiunte le bozze `terms/` e `cookie-policy/` (it/en, DRAFT con placeholder).
- Aggiunti `manifest.json` (indice machine-readable) e `index.md` (landing Pages).
- Repo rinominato `privacy-policies` → `ARS_legal`; i servizi vanno ri-puntati ai nuovi URL.

## Core Privacy Policy

### v5.3 — 2026-07-06
- **AR PD Meter**: reso esplicito il flusso dei dati tecnici derivati (landmark facciali, orientamento del volto, informazioni dispositivo) verso il backend ARShades nell'Unione Europea, utilizzati solo per restituire la misurazione e scartati dopo l'elaborazione; nelle esperienze ARShades Mirror l'elaborazione avviene sul backend locale del dispositivo, senza trasmissione cloud.
- **Addenda regionali**: riscritte le sezioni sui trasferimenti internazionali di 10 addenda (Canada, Australia/NZ, Asia-Pacifico, LatAm, Giappone, Cina, Sudafrica, India, Medio Oriente, Altri Paesi): il trasferimento verso l'UE è ora dichiarato con le relative garanzie.
- **Addendum USA**: carve-out AR PD Meter nella sezione biometrica (BIPA/CUBI/RCW 19.375), riscrittura della sezione trasferimenti, consenso espresso via casella di accettazione, aggiunti TDPSA e Washington.
- **Naming**: standardizzato "AR PD Meter" in tutto il documento.
- **Fix normativi**: Giappone (traslitterazione, numerazione articoli APPI post-2022), India (DPDP), Brasile (Res. ANPD 15/2024), Australia (tempistiche NDB), Arabia Saudita (SDAIA), UAE.
- **Responsabili**: chiarito il ricorso a fornitori di infrastruttura cloud UE ex art. 28 GDPR.
- Traduzioni: IT (testo autentico), EN, FR, DE, ES, JA.

### v5.2 — 2026-05-05
- Versione precedente (baseline).

## Shopify App Privacy Policy

### 2026-07-06 — prima pubblicazione
- Policy dedicata all'app "ARShades VTO for Shopify", limitata ai dati trattati in relazione a Shopify; esperienze ARShades regolate dalla core policy.
- Include: compliance webhooks GDPR (30 giorni, shop/redact 48h post-uninstall), consent gating del Web Pixel, incident response, crittografia at rest, diritto di reclamo, DPA su richiesta.
- Traduzioni: EN (testo autentico), IT, FR, DE, ES, JA.

## Terms & Conditions

### v0.1.0-draft — 2026-07-07 — prima bozza
- Scheletro dei Termini e Condizioni ARShades (it/en) con banner DRAFT e placeholder `[[…]]` da completare. Non ancora in vigore.

## Cookie Policy

### v0.1.0-draft — 2026-07-07 — prima bozza
- Scheletro della Cookie Policy ARShades (it/en) con banner DRAFT e placeholder `[[…]]` da completare. Non ancora in vigore.
