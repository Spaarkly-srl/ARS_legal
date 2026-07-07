# Changelog

## Repository

### 2026-07-07 — policy lingua autentica
- **L'italiano è il testo autentico di tutti i documenti legali**, con un'unica eccezione: la Privacy Policy dell'app Shopify resta EN-autentica (è il testo valutato da Shopify e letto dai merchant). Le altre lingue sono traduzioni di cortesia.

### 2026-07-07 — riorganizzazione come hub legale
- Il repository passa da "solo privacy policy" a **hub dei documenti legali pubblici** (privacy, termini, cookie policy).
- Rinominato `core/` → `privacy-policy/` e `shopify-app/` → `privacy-policy-shopify/` (aggiornati di conseguenza gli URL raw/Pages e i link interni).
- Aggiunte le bozze `terms/` e `cookie-policy/` (it/en, DRAFT con placeholder).
- Aggiunti `manifest.json` (indice machine-readable) e `index.md` (landing Pages).
- Repo rinominato `privacy-policies` → `ARS_legal`; i servizi vanno ri-puntati ai nuovi URL.

## Core Privacy Policy

### v5.4 — 2026-07-07
- **Formula identificabilità AR PD Meter** (feedback consulente legale): sostituita in tutte le lingue la formulazione assoluta "dati tecnici derivati **non riconducibili all'identità dell'Utente**" (EN: "not traceable to the User's identity") con la formula qualificata "**non utilizzati per identificare l'Utente e non idonei, di per sé, a identificarlo**" (EN: "not used to identify the User and not capable, on their own, of identifying the User") — 11 occorrenze per lingua, allineata ai Termini AR PD Meter v1.1+.
- **Intestazione §3**: "Dati di misurazione facciale ~~(non biometrici)~~" — rimossa la classificazione assoluta dal titolo in tutte le lingue; la descrizione del trattamento resta invariata.
- **Elenco "a differenza delle tecnologie biometriche"**: riformulato in forma qualificata anche il punto sulle misurazioni ("non utilizza le misurazioni per identificare specifiche persone, né le misurazioni sono, di per sé, idonee a identificarle") in tutte le lingue.
- Nessuna modifica ad architettura, flussi dati o addenda.
- Lingue: IT (testo autentico), EN, FR, DE, ES, JA.

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

### 2026-07-07 — allineamento
- Rimossa da tutte le lingue la riga "Draft version for Shopify submission" (la policy è in vigore).
- Aggiornato il riferimento alla core policy: versione 5.3 → 5.4.
- Resta l'unico documento con **testo autentico inglese** (policy lingua del 2026-07-07).

### 2026-07-06 — prima pubblicazione
- Policy dedicata all'app "ARShades VTO for Shopify", limitata ai dati trattati in relazione a Shopify; esperienze ARShades regolate dalla core policy.
- Include: compliance webhooks GDPR (30 giorni, shop/redact 48h post-uninstall), consent gating del Web Pixel, incident response, crittografia at rest, diritto di reclamo, DPA su richiesta.
- Traduzioni: EN (testo autentico), IT, FR, DE, ES, JA.

## Terms & Conditions (Servizi ARShades)

### v1.2 — 2026-07-07 — italiano testo autentico
- Pubblicata la **traduzione italiana integrale** (`terms/it.md`): l'**italiano diventa il testo autentico** e prevalente; l'inglese è declassato a traduzione di cortesia (clausola Lingua aggiornata in entrambe le versioni).
- Nessuna modifica sostanziale alle clausole rispetto alla v1.1.

### v1.1 — 2026-07-07 — revisione post-feedback legale
- **Gateway**: corretta la definizione (piattaforma standalone/hub, non app da store); le clausole store ora riguardano le **mobile app** ARShades (Android/iOS).
- **Apple App Store**: aggiunti i termini minimi richiesti da Apple (licenza limitata, nessun obbligo di manutenzione Apple, claim prodotto/IP a carico Spaarkly, dichiarazione export/embargo USA, Apple third-party beneficiary) — §10.2.
- **VTO Explorer**: carve-out allineato alla PP v5.3 — immagini di sessione elaborate localmente; upload temporaneo solo delle foto finali scelte dall'Utente da dispositivi in luoghi pubblici (Shoot & Share), cancellate ≤24h — §6.2.
- **Consumatori EEA/UK**: cap di responsabilità (€100) e indemnity dichiarati non applicabili — §18.1(d).
- **Minori**: formulazione allineata alla PP ("general audience" + età del consenso digitale) — §9.1.
- **Ruolo di Spaarkly**: esplicitato non-venditore / non-marketplace / non-ottico — §8.3.
- **Modifiche**: ri-accettazione in-flow per i Termini aggiornati; modifiche al trattamento AR PD Meter efficaci solo con nuovo consenso espresso — §15.3–15.4.
- **Scope AR PD Meter**: "not covered" → "not governed solely by" (coerenza con l'incorporation) — Welcome.

### v1.0 — 2026-07-07
- Prima versione unificata **"ARShades Services — Terms and Conditions of Use"** (EN, testo autentico): copre VTO, VTO Explorer, Mirror, Gateway e Campaign Catalogue. **Sostituisce** i "ARShades VTO — Terms and Conditions of Use" del 21 marzo 2025.
- Architettura regionale a tre livelli: corpo conforme al diritto dei consumatori UE + clausola di salvezza dei diritti indisponibili (§13) + addenda regionali (EEA/UK, USA, Australia/NZ).
- Rimossi i residui USA globali del vecchio documento: class action waiver e jury waiver ora **solo nell'addendum USA**; eliminato il riferimento alla clausola arbitrale inesistente (nessun arbitrato, per scelta).
- Foro di Potenza con salvezza espressa del foro del consumatore (Reg. UE 1215/2012); garanzie/limitazioni con carve-out (dolo, colpa grave ex art. 1229 c.c., danni alla persona); indennizzo limitato e non applicabile dove vietato; modifiche ai Termini con preavviso (≥15 giorni ove praticabile); cap di responsabilità: maggiore tra corrispettivi 12 mesi ed EUR 100.
- Sezione privacy allineata alla PP v5.3: "facial landmark coordinates" (non "facial mesh"), elaborazione locale dichiarata solo per i servizi core; AR PD Meter escluso e rinviato ai termini dedicati.
- Aggiunte sezioni mancanti: minori (età consenso digitale, in Italia 14), app store/terze parti, forza maggiore, cessione, notifiche, lingua autentica (EN).
- Traduzioni: in preparazione (segnaposto IT che rinvia al testo EN).

### v0.1.0-draft — 2026-07-07 — prima bozza
- Scheletro dei Termini e Condizioni ARShades (it/en) con banner DRAFT e placeholder `[[…]]` da completare. Non ancora in vigore.

## AR PD Meter — Terms & Conditions

### v1.2 — 2026-07-07 — italiano testo autentico
- Pubblicata la **traduzione italiana integrale** (`terms-ar-pd-meter/it.md`): l'**italiano diventa il testo autentico** e prevalente; l'inglese è traduzione di cortesia (clausola Lingua aggiornata in entrambe le versioni).
- §3.5: riferimento alla Privacy Policy aggiornato a "versione 5.4 o successiva".
- Nessuna modifica sostanziale alle clausole rispetto alla v1.1.

### v1.1 — 2026-07-07 — revisione post-feedback legale
- §1.3: finalità riformulata come **commercial convenience only** (rimosso il riferimento al "lens fitting"); esclusi espressamente usi medici/clinici/diagnostici e dispensazione di lenti su prescrizione.
- §2.4 (nuovo): contrattualizzato il contenuto del flow di consenso — versione/data dei termini, dati trattati, finalità, retention, modalità di revoca. Diventa requisito per la UI.
- §3.3: formula biometrica rafforzata e allineata alla PP v5.3 (immagini/video non conservati, nessun template facciale, nessun enrollment in database identificativi, no facial recognition); mantenuta la qualificazione "not capable, on their own, of identifying you" (posizione carve-out BIPA).

### v1.0 — 2026-07-07 — prima pubblicazione
- Termini dedicati (EN, testo autentico), supplementari ai Termini dei Servizi ARShades e prevalenti per AR PD Meter.
- Consenso espresso via casella di accettazione (valido come written release BIPA/CUBI/RCW 19.375); flusso dati allineato alla PP v5.3: immagini mai trasmesse, dati tecnici derivati → backend UE, cancellazione immediata post-elaborazione; nel Mirror elaborazione sul backend locale del dispositivo.
- Disclaimer di misura: stima indicativa, **non dispositivo medico**, non sostituisce la misurazione di un professionista; età minima 18 anni (o consenso del genitore); limitazione di responsabilità specifica sull'affidamento nella misura.
- Traduzioni: in preparazione.

## Cookie Policy

### v0.1.0-draft — 2026-07-07 — prima bozza
- Scheletro della Cookie Policy ARShades (it/en) con banner DRAFT e placeholder `[[…]]` da completare. Non ancora in vigore.
