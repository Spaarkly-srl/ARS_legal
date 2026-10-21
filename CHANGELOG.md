# Changelog

## Repository

### 2026-10-21 — Cookie Policy 1.1.1 e Informativa Privacy del sito web 1.0.0 (testi definitivi del consulente, approvati; in vigore dal lancio del nuovo sito)
- **Cookie Policy del sito web → v1.1.1** (`cookie-policy/it.md`): testo definitivo rivisto dal consulente privacy di Spaarkly e approvato da Michele Lo Russo il 21/10/2026 (sostituisce la 1.1.0 della stessa giornata). Cinque sezioni: cosa usiamo e perché (tecnici e funzionali necessari senza consenso, art. 122 Codice Privacy; Analytics solo con consenso), tabella dei cookie e archivi del browser (sei voci, con la tecnologia accanto al nome; `ARS_CAPTURE_DB` = foto della demo VTO Explorer, mai inviata ai server), scelta e modifica delle preferenze (12 mesi; registro minimale delle scelte 26 mesi), demo incorporate (archivi tecnici sui loro domini; Google Maps nella demo Gateway, Google titolare autonomo), aggiornamenti. Tolti i cookie dell'area amministrativa (li riceve solo il personale), Google Places, sedi dei server e reti di distribuzione. Status `approved`, `effective_date` da impostare al lancio; fino ad allora il sito serve la 1.0.1. Le traduzioni 1.0.1 restano nella storia git; en/fr/de/es/ja della 1.1.1 in corso.
- **Informativa Privacy del sito web → v1.0.0** (`privacy-website/it.md`): prima versione approvata (da 0.1.0-draft del 22/07), testo definitivo del consulente approvato da Michele Lo Russo il 21/10/2026. Sei sezioni: titolare; dati, finalità e basi (navigazione e sicurezza; Google Analytics 4 su consenso; registro delle scelte sui cookie, art. 6.1.c per il consenso; richieste di demo e prova con link di conferma di 24 ore, CRM solo dopo la conferma, richieste non confermate conservate solo contro abusi e frodi, senza ricontatti); conservazione in tabella (log 30 giorni, GA4 14 mesi, registro scelte 26 mesi, richieste non confermate 12 mesi, confermate 24 mesi dall'ultima interazione, log ZeptoMail 60 giorni); fornitori e trasferimenti (Google, Zoho; DPF e Clausole Contrattuali Standard); diritti con opposizione esplicita; aggiornamenti. Status `approved`, in vigore dal lancio; traduzioni in corso (fino ad allora solo `it`).

### 2026-10-13 — estratti «in breve» per AR PD Meter (bozze)
- Aggiunti `terms-ar-pd-meter/summary/{it,en,es,fr,de}.md` e `privacy-policy/summary-ar-pd-meter/{it,en,es,fr,de}.md`: i punti essenziali dei Termini AR PD Meter e dell'Informativa Privacy in linguaggio semplice, da mostrare nel pannello Termini/Privacy dell'AR PD Meter con il link al testo completo (modello «informativa breve + testo completo», coerente con il §2.4 v1.4). Non sostituiscono i documenti. **Versione 1.0, approvata da Michele il 13/10/2026** (italiano testo autentico); en/es/fr/de riviste lo stesso giorno da revisori madrelingua di linguaggio legale semplice, allineate ai documenti completi nella rispettiva lingua (termini, registro: «Sie», «usted», «vous»; titolo spagnolo «en resumen»). Pubblicati; voci `published` v1.0 nel manifest.

### 2026-07-10 — rimozione indirizzo Spaarkly da Termini e template
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

### v5.6 — 2026-08-26 — allineamento al Master ARShades Mirror
- **Regola di cancellazione** delle foto finali da dispositivi in-store: «entro 24 ore» → «**entro il giorno successivo alla sessione**» (§4, §5 e 9 addenda regionali). Invariato il salt del Campaign Catalogue «rinnovato ogni 24 ore» (§3), che non è una retention.
- **Naming**: «VTO Mirror» / «Mirror Showroom» → «**ARShades Mirror**» / «edizione ARShades Mirror Showroom» (Definizioni, §2b, titolo §5); nelle Definizioni la descrizione del prodotto (postazioni dedicate in punti vendita, showroom e sedi di eventi; edizioni Showroom, Portrait e Photobooth) sostituisce «specchi digitali e chioschi in-store».
- **§5**: formula sul volto allineata al Master («elaborati in tempo reale, localmente sul dispositivo, senza template persistenti né riconoscimento dell'identità; nessun flusso video lascia la postazione»). **Rimosse** le frasi sull'uso di AR PD Meter nel Mirror (Definizioni, §3, §5): il Mirror non misura la distanza pupillare — nell'edizione Showroom dai landmark è derivata sul dispositivo una **stima della distanza dalla fotocamera basata su valori antropometrici medi**, al solo fine di dimensionare le montature virtuali, non conservata né trasmessa (verifica di codice `ARS_Mirror` 26/08/2026).
- **Modulo AI locale (§2)**: attributi stimati = genere, fascia d'età, presenza di occhiali; la stima di ulteriori attributi demografici generali è **disattivata per impostazione predefinita** e attivabile solo per specifici progetti, previa valutazione legale, con indicazione nell'informativa mostrata sul dispositivo.
- Origine: `ARS_product_governance/masters/mirror/master_mirror.md` §13, §18, §20 (decisioni D3, D4, B6, B8 del 26/08/2026).
- Lingue: IT (testo autentico), EN, FR, DE, ES, JA.

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

### v1.4 — 2026-08-26 — Mirror: postazione in noleggio, regola di cancellazione
- **§1.2**: Mirror = esperienza presso punti vendita, showroom o eventi erogata tramite una postazione dedicata.
- **§3.4**: la postazione è **fornita da Spaarkly in noleggio** e installata presso i locali del Cliente o la sede di un evento (prima: «dispositivo messo a disposizione dal Cliente»); spazio, alimentazione, connettività, custodia e condizioni materiali di utilizzo restano di responsabilità del Cliente.
- **§6.1**: aggiunta la stima della distanza dalla fotocamera da valori antropometrici medi nell'edizione Showroom (nessuna misura della distanza pupillare; non conservata né trasmessa). **§6.2**: foto finali cancellate «al più tardi entro il giorno successivo alla sessione».
- Origine: Master ARShades Mirror v1.0.0 (§13, §16, §18). Lingue: it (autentico), en, es, fr, de.

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

### v1.4 — 2026-10-13 — §2.4 ridotto a quello che la schermata fa
- **§2.4**: non chiede più che il flusso di consenso mostri versione e data dei Termini e riepiloghi dati, finalità, conservazione e revoca (requisito per la UI della v1.1, giudicato da Michele un dettaglio troppo fine per i Termini). Ora dice che prima della misurazione l'Utente vede come sono trattati i suoi dati e può leggere Termini e Informativa Privacy; resta la revoca in qualsiasi momento. Origine: design delle schermate AR PD Meter del 13/10/2026 (consenso = tocco su «Inizia», pannello di lettura di Termini e Privacy dentro il contenitore).
- Stessa riduzione nella frase corrispondente del template Cliente AR PD Meter (`client-terms-ar-pd-meter-template/full/*.md`, v0.2.3) e nei README dei due template.
- Lingue: it (autentico), en, es, fr, de.

### v1.3 — 2026-08-26 — rimosso il flusso «Mirror locale»
- **§1.2** e **§3.4** (rimossa; la vecchia §3.5 diventa §3.4): eliminato il riferimento all'uso di AR PD Meter nelle esperienze ARShades Mirror — anticipatorio e non corrispondente al prodotto (il Mirror non misura la distanza pupillare; Master Mirror B6). Nessuna modifica al flusso web/app né al consenso espresso.
- Lingue: it (autentico), en, es, fr, de.

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

### v0.2.3 — 2026-10-13 — AR PD Meter: frase sul flusso di consenso
- **AR PD Meter — full**: la frase che ricalcava il §2.4 dei Termini AR PD Meter (versione/data + riepilogo di dati, finalità, conservazione, revoca) segue la v1.4 dei Termini: prima della misurazione l'Utente vede come sono trattati i suoi dati e può leggere Condizioni e Informativa Privacy; revoca in qualsiasi momento. Il template Servizi VTO non cambia (resta v0.2.2).
- Lingue: it, en, es, fr, de.

### v0.2.2 — 2026-08-26 — allineamento al Master ARShades Mirror
- **Servizi VTO — full**: blocco Mirror riscritto (postazione fornita da Spaarkly in noleggio e installata presso punti vendita, showroom o eventi del Cliente; spazio, alimentazione, connettività, custodia e condizioni materiali a cura del Cliente); Shoot & Share «al più tardi entro il giorno successivo alla sessione» (anche nelle formule vincolate del README).
- **AR PD Meter — full**: rimosso il blocco condizionale `mirror_enabled` («backend locale del dispositivo Mirror»); il template AR PD Meter non usa più `mirror_enabled` (resta nello schema per il template Servizi VTO). README: tolto «su Mirror elaborazione locale».
- Lingue: it, en, es, fr, de.

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

### v1.0.1 — 2026-07-23 — correzioni dal secondo giro di revisione legale
- **Cross-link corretti**: "Informativa Privacy del Sito" ora punta al nuovo documento `privacy-website/` (prima puntava per errore alla Privacy Policy delle soluzioni). Le lingue fr/de/es/ja linkano la EN finché la PP sito non sarà pubblicata nelle altre lingue.
- **§3 prova del consenso**: aggiunta la **lingua** del banner visualizzato all'elenco dei dati registrati (il campo `locale` è già persistito nel log — EDPB 05/2020 §107-108).
- **§4/§5**: `vto_demo_embed` e `google_places_session` non sono cookie (storage "none" nel registry) — rimossi dalla tabella cookie e descritti al §5 come "servizi caricati su richiesta"; per Google Places precisato che il caricamento avviene alla digitazione e che Google opera quale titolare autonomo.
- **§4 retention GA4**: precisato che i 14 mesi riguardano i dati a livello di utente/evento (i report aggregati non contengono dati personali).
- Efficacia invariata (2026-07-22); tutte e 6 le lingue.

### v1.0 — 2026-07-22 — prima versione pubblicata
- Cookie Policy del **sito marketing ARShades** in 6 lingue (it, en, fr, de, es, ja). Categorie (necessari, analytics, funzionali; marketing prevista ma non usata), meccanismo di consenso (`ars_consent` 12 mesi, banner a 2 layer, revoca con cancellazione `_ga*`, prova di consenso server-side senza IP/UA), tabella cookie al §4 — statica qui su GitHub Pages, iniettata dinamicamente sul sito marketing dal registro `data/cookie-registry.json`. Rimosso banner BOZZA; `status: published`, `effective_date: 2026-07-22`.

### v0.1.0-draft — 2026-07-07 — prima bozza
- Scheletro della Cookie Policy ARShades (it/en) con banner DRAFT e placeholder `[[…]]` da completare. Non ancora in vigore.
