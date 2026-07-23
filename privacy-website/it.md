# INFORMATIVA PRIVACY — SITO WEB ARSHADES

> ⚠️ **BOZZA / DRAFT — NON DEFINITIVA.** Documento in attesa di revisione legale, non ancora in vigore. [[Prerequisiti al sign-off: (1) persistenza di `privacyNoticeAcknowledged*` (+ versione e lingua) nel backend di registrazione; (2) verifica/attivazione della policy TTL Firestore su `tokenExpiry` per `PendingRegistration` in staging e produzione; (3) implementazione del flusso backend del form demo (POST + ZeptoMail + Zoho Bigin) — la §2.e descrive lo stato target; (4) verifica impostazioni console: GA4 senza condivisione dati con altri prodotti Google, ZeptoMail senza retention contenuti né tracking aperture/click; (5) verifica DPA Zoho ed elenco sub-responsabili (accessi extra-SEE) per ZeptoMail e Bigin.]]

*Sito marketing ARShades* </br> *Versione: bozza — Ultimo aggiornamento: 22 luglio 2026*

La presente **Informativa Privacy** descrive come **Spaarkly s.r.l.** (“Spaarkly”, “noi”) tratta i tuoi dati personali quando visiti o utilizzi il **sito web di presentazione delle soluzioni ARShades** (il “Sito”).

Questo documento riguarda **esclusivamente il Sito**. I trattamenti effettuati all’interno delle **esperienze di prodotto ARShades** (Virtual Try-On, 3D Viewer, VTO Explorer, AR PD Meter, VTO Mirror, Gateway, Campaign Catalogue) sono regolati dall’[Informativa Privacy delle soluzioni ARShades](../privacy-policy/it.md). Per i cookie e le tecnologie similari utilizzati dal Sito, consulta la [Cookie Policy del Sito](../cookie-policy/it.md).

## 1. Titolare del trattamento

Il titolare del trattamento è **Spaarkly s.r.l.**, Via della Tecnica n. 18, 85100 Potenza (Italia).
Per ogni questione relativa alla protezione dei dati puoi scriverci a **privacy@spaarkly.com**.

## 2. Quali dati trattiamo, perché e su quale base giuridica

### a) Dati di navigazione e log di servizio

Durante la navigazione, i sistemi che ospitano il Sito (infrastruttura Google Firebase, regione **europe-west1**, Belgio) registrano automaticamente dati tecnici la cui trasmissione è implicita nei protocolli Internet: indirizzo IP, data e ora della richiesta, pagina richiesta, codice di risposta, user-agent del browser. Utilizziamo questi log esclusivamente per garantire il **funzionamento, la sicurezza e la diagnostica** del Sito.

- **Base giuridica:** legittimo interesse (art. 6, par. 1, lett. f, GDPR) al corretto e sicuro funzionamento del Sito.
- **Conservazione:** per il tempo strettamente necessario alle finalità di sicurezza e diagnostica, di norma non oltre **30 giorni**.

### b) Statistiche d’uso del Sito (Google Analytics 4) — solo con il tuo consenso

Se abiliti la categoria “Analytics” — accettando tutti i cookie dal banner oppure selezionandola nelle preferenze — utilizziamo **Google Analytics 4** per statistiche aggregate sull’uso del Sito (pagine visitate, provenienza, interazioni). L’analytics è configurato in modalità privacy-friendly: consenso negato per impostazione predefinita (**Google Consent Mode v2**), **anonimizzazione dell’indirizzo IP**, nessun Google Signals, nessuna funzionalità pubblicitaria o di remarketing, nessuna profilazione cross-site.

- **Base giuridica:** consenso (art. 6, par. 1, lett. a, GDPR), revocabile in ogni momento dal link “Preferenze cookie” nel footer.
- **Conservazione:** i dati a livello di utente e di evento raccolti da Google Analytics 4 sono conservati per un massimo di **14 mesi**; i report statistici aggregati, che non contengono dati personali, possono essere conservati più a lungo.
- Il mancato consenso non ha alcuna conseguenza sull’uso del Sito.

### c) Prova delle scelte sui cookie

Quando effettui una scelta nel banner cookie (accettazione, rifiuto o personalizzazione), registriamo sui nostri server una **prova minimale della scelta**: un identificativo casuale, la marca temporale, la versione e la **lingua** dell’informativa visualizzata nel banner, le categorie e l’azione — **senza indirizzo IP né user-agent**.

- **Base giuridica:** legittimo interesse (art. 6, par. 1, lett. f, GDPR) ad assolvere l’obbligo di dimostrare il consenso (accountability, artt. 5, par. 2 e 7, par. 1, GDPR).
- **Conservazione:** fino a **26 mesi**, poi rimozione automatica.

### d) Form di richiesta di registrazione ad ARShades Studio

Il Sito ospita un form con cui la tua azienda può richiedere la registrazione alla piattaforma **ARShades Studio**. I dati raccolti sono:

- **dati aziendali:** ragione sociale, paese, partita IVA, sito web aziendale, indirizzo della sede (via, CAP, città, provincia) e — solo per l’Italia — codice SDI e/o PEC;
- **dati di contatto del referente:** nome, cognome, email aziendale, ruolo in azienda e, facoltativamente, numero di telefono;
- **data e ora** della tua accettazione dei Termini e Condizioni e della presa visione della presente informativa, insieme alla **versione e alla lingua** dell’informativa visualizzata.

La richiesta è sottoposta a **controlli automatici di ammissibilità** (formato di email e telefono, verifica tecnica del dominio email aziendale, formato della partita IVA): sono controlli tecnici privi di effetti giuridici sulla persona; in caso di esito negativo puoi sempre contattarci a privacy@spaarkly.com.

Alla trasmissione del form, i dati sono inviati al backend ARShades (Google Cloud, regione **europe-central2**, Polonia) e conservati in un’area di attesa fino alla verifica dell’indirizzo email: ti inviamo un’email di verifica (mittente `no-reply@arshades.com`, tramite il fornitore **ZeptoMail** — Zoho Corporation, endpoint europeo) contenente un link valido **7 giorni**. Se non completi la verifica entro tale termine, **i dati della richiesta sono cancellati automaticamente**; i log tecnici di consegna del fornitore email sono conservati per circa **60 giorni**. Non registriamo indirizzo IP né user-agent insieme alla richiesta.

Al completamento della verifica e della registrazione, i dati confluiscono nel tuo account ARShades Studio e sono trattati secondo l’informativa privacy resa disponibile in piattaforma e le condizioni contrattuali applicabili.

- **Base giuridica:** legittimo interesse (art. 6, par. 1, lett. f, GDPR) di Spaarkly e dell’azienda richiedente a gestire la richiesta di registrazione presentata dal referente aziendale; ove tu agisca in proprio quale professionista o ditta individuale, esecuzione di misure precontrattuali adottate su tua richiesta (art. 6, par. 1, lett. b, GDPR).
- **Conservazione:** **7 giorni** per le richieste non verificate; in caso di completamento, secondo i termini applicabili all’account ARShades Studio.
- Il conferimento dei dati indicati come obbligatori è necessario per dare seguito alla richiesta; in loro assenza la registrazione non può essere completata. Il numero di telefono è facoltativo.

### e) Form “Richiedi una demo”

Il Sito ospita un form per richiedere una demo delle soluzioni ARShades. I dati raccolti sono: nome e cognome, email aziendale, azienda, ruolo, paese, tipologia e dimensione del catalogo, ambiti di interesse e, facoltativamente, un messaggio. Utilizziamo questi dati per **valutare e gestire la tua richiesta di demo e per ricontattarti** a tale scopo. La richiesta è registrata nel nostro CRM **Zoho Bigin** (data center europeo) e le comunicazioni email relative sono inviate tramite **ZeptoMail** (Zoho Corporation, endpoint europeo).

- **Base giuridica:** legittimo interesse (art. 6, par. 1, lett. f, GDPR) di Spaarkly e dell’azienda richiedente a gestire la richiesta presentata dal referente aziendale; ove tu agisca in proprio quale professionista o ditta individuale, esecuzione di misure precontrattuali adottate su tua richiesta (art. 6, par. 1, lett. b, GDPR).
- **Conservazione:** **24 mesi** dall’ultimo contatto utile, salvo instaurazione del rapporto contrattuale.
- Il conferimento dei dati indicati come obbligatori è necessario per dare seguito alla richiesta; il messaggio è facoltativo.

### f) Autocompletamento dell’indirizzo (Google Places) — solo su tua richiesta

Nel form di registrazione, il campo indirizzo offre suggerimenti di autocompletamento basati su **API Google Maps Places**. Il servizio si attiva **solo quando inizi a digitare nel campo indirizzo**: da quel momento il tuo browser stabilisce una connessione con i server di Google — il che comporta la comunicazione a Google del tuo **indirizzo IP e di dati tecnici del browser** — e il testo digitato è trasmesso a Google per generare i suggerimenti; alla selezione di un suggerimento, Google restituisce l’indirizzo strutturato. Per questo servizio **Google opera quale titolare autonomo del trattamento** (Google Controller-Controller Terms): per informazioni consulta l’[informativa privacy di Google](https://policies.google.com/privacy). Puoi sempre inserire l’indirizzo manualmente: se non digiti nel campo con i suggerimenti attivi, nessun dato è inviato a Google.

- **Base giuridica:** legittimo interesse (art. 6, par. 1, lett. f, GDPR) ad agevolare la compilazione del form; il servizio si attiva solo in seguito a una tua azione esplicita e resta sempre disponibile l’inserimento manuale.

### g) Area amministrativa riservata

Il Sito include un’area amministrativa non pubblica, riservata al personale autorizzato di Spaarkly, protetta da autenticazione (**Firebase Authentication**) e cookie tecnici di sessione. L’area non riguarda i visitatori del Sito; i relativi cookie sono elencati nella [Cookie Policy](../cookie-policy/it.md).

## 3. Destinatari dei dati

I dati sono trattati dal personale autorizzato di Spaarkly e dai seguenti fornitori:

| Fornitore | Servizio | Ruolo | Sede del trattamento |
|---|---|---|---|
| Google Ireland Ltd. / Google LLC | Infrastruttura di hosting e database (Firebase, Google Cloud) | Responsabile del trattamento | UE (europe-west1, europe-central2) |
| Google Ireland Ltd. / Google LLC | Google Analytics 4 (solo previo consenso) | Responsabile del trattamento — la condivisione dei dati con altri prodotti e servizi Google è disattivata | UE/USA |
| Google Ireland Ltd. / Google LLC | API Google Maps Places (solo su tua richiesta) | **Titolare autonomo** (Google Controller-Controller Terms) | UE/USA |
| Zoho Corporation (ZeptoMail) | Invio delle email di verifica e di servizio | Responsabile del trattamento | UE (endpoint europeo) |
| Zoho Corporation (Bigin) | CRM per la gestione delle richieste demo | Responsabile del trattamento | UE (data center europeo) |

Non vendiamo i tuoi dati personali né li condividiamo con terzi per finalità di marketing.

## 4. Trasferimenti internazionali

I dati sono trattati principalmente all’interno dell’Unione Europea. Ove un fornitore (in particolare **Google LLC** per Google Analytics 4 e le API Google Maps) tratti dati negli Stati Uniti, il trasferimento è assistito, a seconda dei casi: dalla decisione di adeguatezza della Commissione Europea per l’**EU–U.S. Data Privacy Framework**, valida per le sole entità statunitensi certificate (Google LLC è certificata); e/o dalle **Clausole Contrattuali Standard** adottate dalla Commissione Europea. I dati affidati a **Zoho Corporation** (ZeptoMail, Bigin) sono ospitati in data center nell’Unione Europea; eventuali accessi tecnici da parte di società del gruppo Zoho stabilite al di fuori dello Spazio Economico Europeo (ad esempio per l’assistenza) sono disciplinati dalle **Clausole Contrattuali Standard** incluse nel Data Processing Addendum del fornitore. [[Verifica in corso: DPA Zoho ed elenco sub-responsabili per ZeptoMail e Bigin.]] Puoi ottenere copia delle garanzie applicabili scrivendo a **privacy@spaarkly.com**. Per il servizio Google Places, Google tratta i dati quale titolare autonomo secondo la propria informativa privacy.

## 5. Periodi di conservazione — riepilogo

| Trattamento | Conservazione |
|---|---|
| Log di servizio e sicurezza | Di norma non oltre 30 giorni |
| Statistiche Google Analytics 4 | Dati utente/evento: massimo 14 mesi (i report aggregati non contengono dati personali) |
| Prova delle scelte sui cookie | Fino a 26 mesi |
| Richieste di registrazione non verificate | 7 giorni |
| Log di consegna email del fornitore (ZeptoMail) | Circa 60 giorni |
| Richieste demo nel CRM | 24 mesi dall’ultimo contatto utile |
| Scelta sui cookie (cookie `ars_consent` sul tuo dispositivo) | 12 mesi |

## 6. Diritti dell’interessato

Nei limiti previsti dagli artt. 15–22 GDPR, hai diritto di ottenere l’**accesso** ai tuoi dati, la **rettifica**, la **cancellazione**, la **limitazione** del trattamento, la **portabilità**, nonché di **opporti** al trattamento fondato sul legittimo interesse e di **revocare il consenso** in qualsiasi momento (per l’analytics, dal link “Preferenze cookie” nel footer), senza pregiudicare la liceità del trattamento anteriore alla revoca.

Puoi esercitare i tuoi diritti scrivendo a **privacy@spaarkly.com**. Hai inoltre diritto di proporre reclamo all’autorità di controllo competente (per l’Italia, il **Garante per la protezione dei dati personali** — www.garanteprivacy.it).

## 7. Minori

Il Sito e i servizi ARShades Studio sono destinati a un pubblico professionale e non sono rivolti a minori. Non raccogliamo consapevolmente dati personali di minori attraverso il Sito.

## 8. Modifiche alla presente Informativa

Potremo aggiornare la presente Informativa per riflettere modifiche del Sito, dei trattamenti o della normativa. La versione aggiornata è pubblicata su questa pagina con la data di ultimo aggiornamento; in caso di modifiche sostanziali ne daremo evidenza sul Sito.

## 9. Contatti

Spaarkly s.r.l. — Via della Tecnica n. 18, 85100 Potenza (Italia) — privacy@spaarkly.com.

---

© Spaarkly s.r.l. Tutti i diritti riservati.
