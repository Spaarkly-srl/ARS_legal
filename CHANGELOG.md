# Changelog

## Repository

### 2026-07-21 — housekeeping: dedup Shopify policy, README allineato, sync sito
- **Dedup**: `privacy-policy-plugin/` era una copia byte-identica di `privacy-policy-shopify/` (l'unica registrata in `manifest.json`). I 6 file `plugin/` sono ora **stub di cortesia** che puntano ai path `shopify/` (gli URL in ingresso restano vivi); `index.md` riallineato ai path canonici.
- **Shopify policy (tutte le lingue)**: aggiornato il riferimento alla core policy "versione 5.4" → "versione 5.5" (riferimento incrociato fattuale, nessuna modifica sostanziale — versione Shopify invariata).
- **README**: core policy 5.4 → 5.5 (16 luglio 2026), aggiunta sezione Cookie Policy (draft v0.1.0), esempio Pages corretto.
- **CI**: aggiunto workflow `notify-website` — ogni push su `main` che tocca manifest o documenti notifica il sito marketing (`repository_dispatch`), che sincronizza i testi e apre una PR.
- Rimosso l'indirizzo postale di Spaarkly (Via della Tecnica 18, 85100 Potenza) dai Termini Servizi (§1.1 e §20, tutte le lingue), dai Termini AR PD Meter (§1.1 e §8, tutte le lingue) e dai due template Cliente. Mantenuti ragione sociale, **P. IVA IT02077620769** ed email (`legal@spaarkly.com` / `privacy@spaarkly.com`). Aggiornamento editoriale, nessuna modifica sostanziale (versioni invariate: Termini v1.3, AR PD Meter v1.2, template v0.2.1). L'indirizzo resta nell'Informativa Privacy.

### 2026-07-07 — policy lingua autentica
- **L'italiano è il testo autentico di tutti i documenti legali**, con un'unica eccezione: la Privacy Policy dell'app Shopify resta EN-autentica (è il testo valutato da Shopify e letto dai merchant). Le altre lingue sono traduzioni di cortesia.

### 2026-07-07 — riorganizzazione come hub legale
- Il repository passa da "solo privacy policy" a **hub dei documenti legali pubblici** (privacy, termini, cookie policy).
- Rinominato `core/` → `privacy-policy/` e `shopify-app/` → `privacy-policy-shopify/` (aggiornati di conseguenza gli URL raw/Pages e i link interni).
- Aggiunte le bozze `terms/` e `cookie-policy/` (it/en, DRAFT con placeholder).
- Aggiunti `manifest.json` (indice machine-readable) e `index.md` (landing Pages).
- Repo rinominato `privacy-policies` → `ARS_legal`; i servizi vanno ri-puntati ai nuovi URL.

## Core Privacy Policy

### v5.5 — 2026-07-16
- **ARShades Campaign Catalogue**: aggiunto alle soluzioni coperte (intestazione + Definizioni) come catalogo prodotti pubblico basato sul web.
- **Nuova sezione §3 "Dati di misurazione d'uso dei cataloghi pubblici (Campaign Catalogue)"**: misurazione aggregata delle pagine catalogo senza cookie/local storage/identificatori sul dispositivo; hash non reversibile lato server (IP + info browser) con salt rinnovato ogni 24 ore, IP scartato subito dopo il calcolo; eventi cancellati dopo l'aggregazione giornaliera (di norma ≤48h), conservate solo statistiche aggregate; base giuridica legittimo interesse (art. 6.1.f GDPR); formula di identificabilità qualificata (invariata rispetto alla v5.4).
- **§1**: la misurazione aggregata dei Campaign Catalogue richiamata nella finalità "miglioramento del servizio, analytics" (legittimo interesse).
- **§6**: aggiunto il periodo di conservazione dei dati di misurazione dei cataloghi (cancellazione post-aggregazione giornaliera).
- **§7**: precisato che le pagine pubbliche dei Campaign Catalogue non impostano cookie né local storage.
- Origine: decisioni RPE-0021 (analytics nativi Campaign Catalogue), `ARS_product_governance/masters/campaign-catalogue/decisioni_analytics_nativi_2026-07-16.md`.
- Lingue: IT (testo autentico), EN, FR, DE, ES, JA.

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

### v1.3 — 2026-07-10 — 3D Viewer, Google Play, traduzioni es/fr/de
- **§1.2**: aggiunto il servizio **ARShades 3D Viewer** (visualizzazione 3D a 360° dei modelli + modalità in realtà aumentata) all'elenco dei Servizi, in tutte le lingue.
- **§10**: aggiunta la clausola **Google Play** (§10.3: Google non è parte, nessun obbligo di garanzia/manutenzione, distribuzione soggetta ai termini di Google Play, dichiarazione export) accanto al blocco Apple; rinumerati i successivi §10.4/§10.5. Motivazione: 2 app native VTO (iOS + Android).
- **Traduzioni**: pubblicate le versioni **es, fr, de** (`terms/{es,fr,de}.md`); i Termini Servizi esistono ora in it (autentico), en, es, fr, de. Tradotte dall'italiano autoritativo con l'inglese come riferimento; formule vincolate e clausola Lingua (italiano facente fede) preservate.

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

### 2026-07-10 — traduzioni es/fr/de
- Pubblicate le versioni **es, fr, de** (`terms-ar-pd-meter/{es,fr,de}.md`); i Termini AR PD Meter esistono ora in it (autentico), en, es, fr, de. Nessuna modifica sostanziale alle clausole (resta v1.2); formula di identificabilità qualificata allineata alla PP v5.4 nelle rispettive lingue, clausola Lingua (italiano facente fede) preservata.

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

## Client ARShades Integration Terms — Modello T&C Cliente

### 2026-07-10 — clausola per il contratto quadro
- **Clausola contrattuale** per l'accordo quadro Spaarkly–Cliente (`framework-agreement-clause/it.md`): fornitura as-is / non parere legale, obbligo di revisione del legale del Cliente, integrità dei Blocchi CORE, accettazione degli aggiornamenti/propagazione, ruoli privacy (Spaarkly titolare, Cliente riceve solo dati aggregati/anonimizzati), IP del Modello, responsabilità e manleva.

### v0.2.1 — 2026-07-10 — validazione consulente legale
- **Gateway**: aggiunto `gateway_enabled` allo schema e il relativo blocco nel template Servizi VTO (era mancante nell'elenco funzionalità).
- **Clausola di terzo beneficiario** (art. 1411 c.c.): aggiunto «**nell'interesse del Cliente**» in entrambi i template (requisito dell'art. 1411: lo stipulante deve avere interesse alla pattuizione a favore del terzo) — validata dal consulente come impianto, questo l'unico micro-rafforzamento.
- **AR PD Meter / minori**: allineati full e short-clause del template AR PD Meter (stessa eccezione 18+ con consenso e supervisione del genitore/tutore).
- **Consenso AR PD Meter**: chiarito in template e README che è un **gating locale in-experience** (esperienza avviata solo dopo consenso esplicito, revoca con interruzione immediata, **nessuna prova del consenso persistente associabile all'Utente** perché Spaarkly non identifica l'utente finale).
- **Ruoli privacy**: rafforzato in template e README che il **Cliente non accede** ai dati né al trattamento ARShades e riceve **solo dati aggregati e anonimizzati** — ulteriore fondamento della titolarità Spaarkly.

### v0.2.0 — 2026-07-10 — split in due template + 3D Viewer
- **Split in due template indipendenti** (rispecchia la separazione canonica terms/ vs terms-ar-pd-meter/): `client-terms-template/` per i **Servizi VTO** e nuovo `client-terms-ar-pd-meter-template/` per **AR PD Meter stand-alone**. Decisione Michele: **documenti indipendenti, nessun rinvio incrociato** anche quando il Cliente ha entrambe le soluzioni (AR PD Meter stand-alone non deve trascinarsi la casistica VTO).
- **Template Servizi VTO**: rimosso del tutto il blocco AR PD Meter; aggiunto il blocco **3D Viewer** (flag `viewer_3d_enabled`); modularità per soluzione su nucleo fisso.
- **Template AR PD Meter**: documento autosufficiente e snello (full + short-clause) — consenso espresso sempre reso a Spaarkly, flusso dati (backend UE / Mirror locale), non dispositivo medico, 18+, regola prescrizioni; clausola di terzo beneficiario (art. 1411 c.c.).
- **`microcopy/` rimossa** (Punto 2, 2026-07-08): i wording legali sono leggibili solo nel documento full white-label, mai come task/UI imposti al Cliente.
- **Traduzioni**: entrambi i template (full + short-clause) tradotti dall'IT in **en/es/fr/de** — 16 file, token mustache/condizionali/delimitatori di blocco preservati byte-identici, commenti interni lasciati in IT, URL Privacy Policy per-lingua. I template esistono ora in it/en/es/fr/de.
- `schema.json` (+ `viewer_3d_enabled`) e `intake-checklist/it.md` **condivisi** tra i due template; `manifest.json`, `README`, `index` aggiornati. Le istanze generate vivono nella collezione Firestore `ARS_TermsAndCond`, non nel repo.
- **Aperti**: validazione consulente sulla clausola di terzo beneficiario; clausola nel contratto quadro Spaarkly–Cliente; pilot + generatore JSON → `ARS_TermsAndCond`.

### v0.1.0 — 2026-07-08 — prima bozza del modello
- Nuova sezione `client-terms-template/`: **modello parametrico dei termini di integrazione ARShades "a nome del Cliente"** (impostato come *Client ARShades Integration Terms*, non come "Termini Spaarkly rimarchiati"). Il Cliente è la controparte commerciale dei propri utenti (prodotti, prezzi, prescrizioni, customer journey); Spaarkly resta fornitore della tecnologia e **titolare del trattamento** per i trattamenti della Privacy Policy ARShades (ruoli funzionali, EDPB Guidelines 07/2020).
- **Lingua base: italiano** (decisione 2026-07-07); la lingua delle istanze è scelta dal Cliente.
- Due output: `full/it.md` (documento completo agganciato ai T&C del Cliente) e `short-clause/it.md` (articolo singolo da incollare nei T&C del Cliente). Il microcopy operativo è stato escluso dal modello e non viene pubblicato in questa sezione.
- Variabili mustache `{{…}}` e blocchi condizionali `{{#flag}}…{{/flag}}` definiti in `schema.json` (identità Cliente + flag soluzioni: VTO, VTO Explorer, Shoot & Share, Mirror, Campaign Catalogue, AR PD Meter, app mobile, lenti graduate, minori); `intake-checklist/it.md` per la raccolta dati (da Studio / configurazione plugin).
- Blocchi marcati **[CORE]** (non modificabili dal Cliente: tecnologia e flussi dati, AR PD Meter, Shoot & Share, privacy notice Spaarkly, IP, rapporto tra documenti) e **[CLIENT]** (adattabili: identità, responsabilità di vendita, minori, contatti).
- **Regola prescrizioni**: con `prescription_sales_enabled` il testo include obbligatoriamente la verifica professionale (optician responsibility) e non presenta mai la stima AR PD Meter come misura definitiva — la stima resta "digitale preliminare"; il posizionamento d'uso nel processo di vendita è responsabilità del Cliente (soluzione complementare alla riformulazione "commercial convenience only" del §1.3 dei Termini AR PD Meter).
- Il consenso espresso AR PD Meter (inclusa la written release BIPA/CUBI/RCW) resta **sempre reso a Spaarkly**; formule vincolate identiche ai documenti canonici (identificabilità qualificata, flusso backend UE / Mirror locale, non dispositivo medico, 18+, Shoot & Share ≤24h, naming "AR PD Meter").
- `manifest.json`: nuova voce con `status: template` e mappa `artifacts`; i file del modello sono esclusi da GitHub Pages (`published: false`, per evitare che Liquid interpreti le variabili `{{…}}`); le istanze generate per i Clienti **non** vengono pubblicate in questo repo.
- Modello fornito "as is", non costituisce parere legale: revisione del legale del Cliente obbligatoria; clausola corrispondente da inserire nel contratto quadro Spaarkly–Cliente (item aperto, con pilot + revisione consulente e generatore JSON → documenti).

## Cookie Policy

### v0.1.0-draft — 2026-07-07 — prima bozza
- Scheletro della Cookie Policy ARShades (it/en) con banner DRAFT e placeholder `[[…]]` da completare. Non ancora in vigore.
