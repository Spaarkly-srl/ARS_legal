# Informativa Privacy di ARShades VTO for Shopify

Ultimo aggiornamento: 7 luglio 2026

La presente Informativa Privacy descrive le modalità con cui **Spaarkly s.r.l.** ("Spaarkly", "ARShades", "noi") tratta i dati personali e le altre informazioni in relazione all'applicazione **ARShades VTO for Shopify** (la "App Shopify" o l'"App").

La presente informativa è specifica per l'App Shopify ed è circoscritta ai dati trattati in relazione a Shopify (dati relativi al merchant, allo store, ai prodotti, alla configurazione e all'attribuzione). I trattamenti effettuati dai servizi ARShades destinati agli utenti finali — quali Virtual Try-On, 3D/AR Viewer e AR PD Meter — che possono essere avviati tramite l'App non sono oggetto della presente informativa e sono disciplinati dall'**Informativa Privacy principale di ARShades** (versione 5.4), disponibile all'indirizzo [https://github.com/Spaarkly-srl/ARS_legal](https://github.com/Spaarkly-srl/ARS_legal/blob/main/privacy-policy/it.md) e mostrata agli acquirenti all'interno delle esperienze ARShades.

## 1. Titolare del trattamento

Spaarkly s.r.l. opera in qualità di titolare autonomo del trattamento per i dati personali trattati tramite l'App Shopify.

**Titolare del trattamento:** Spaarkly s.r.l.  
**Sede legale:** Via della Tecnica n. 18, 85100 Potenza, Italia  
**Contatto in materia di privacy:** privacy@spaarkly.com

## 2. Funzionamento dell'App Shopify

L'App Shopify collega lo store Shopify di un merchant alla piattaforma ARShades. Consente ai merchant di:

* collegare un token di licenza ARShades a uno store Shopify;
* creare o collegare un catalogo ARShades;
* associare i prodotti e le varianti Shopify agli asset 3D/VTO di ARShades tramite SKU, EAN o identificatori di prodotto analoghi;
* aggiungere theme blocks per Virtual Try-On, 3D/AR Viewer e AR PD Meter;
* personalizzare colori, stili dei pulsanti, impostazioni delle finestre modali e determinati asset di branding;
* utilizzare gli eventi del Shopify Web Pixel per l'attribuzione VTO/3D e per le analisi di conversione.

L'App è installabile gratuitamente su Shopify. Il servizio ARShades sottostante può richiedere una separata sottoscrizione ARShades acquistata al di fuori di Shopify.

## 3. Categorie di dati trattati

### 3.1 Dati del merchant e dati dell'Admin Shopify

Quando un merchant installa o utilizza l'App, possiamo trattare:

* il dominio dello shop e l'URL dello store Shopify;
* i dati della sessione OAuth di Shopify;
* il token di accesso e gli ambiti di autorizzazione (scope) concessi;
* gli identificatori dell'utente admin Shopify e, ove forniti da Shopify, nome, cognome, indirizzo e-mail, impostazione locale (locale), stato di collaboratore, stato di titolare dell'account e stato di verifica dell'e-mail;
* lo stato di installazione, configurazione e utilizzo dell'App.

Tali dati sono utilizzati per autenticare il merchant, far funzionare l'App integrata, mantenere la sessione dell'App e fornire assistenza e sicurezza.

### 3.2 Dati relativi a licenza, catalogo e configurazione ARShades

Trattiamo le informazioni necessarie per collegare lo store Shopify ad ARShades, tra cui:

* il token di licenza o l'identificatore di sottoscrizione ARShades;
* l'ID del catalogo, il nome del catalogo e lo stato del catalogo ARShades;
* l'ID del 3D viewer e le funzionalità del servizio ARShades, quali la disponibilità di VTO o AR PD Meter;
* la configurazione dell'App salvata come metafield di Shopify, tra cui `licenseId`, `catalogueId`, `viewerId`, `webDomain`, `studioDomain`, `has_vto` e `has_arpd`;
* le impostazioni di stile, quali colori, impostazioni delle finestre modali e impostazioni dei pulsanti;
* gli asset di branding caricati dal merchant, quali un logo utilizzato nelle schermate di consenso o di informativa di ARShades.

### 3.3 Dati relativi a prodotti e varianti Shopify

Al fine di associare i prodotti agli asset ARShades e di mostrare le funzionalità VTO/3D solo ove disponibili, l'App può leggere e trattare:

* l'ID del prodotto Shopify, il titolo, l'handle e l'URL dell'immagine in evidenza;
* l'ID della variante Shopify;
* SKU, barcode, EAN o UPC;
* i valori dei metafield ARShades esistenti;
* gli identificatori di prodotto e di variante del catalogo ARShades.

L'App può scrivere metafield tecnici ARShades sulle varianti Shopify, tra cui `catalogueVariantId` e `catalogueProductId`. Tali metafield sono utilizzati dai theme blocks dello storefront per determinare se un prodotto o una variante può avviare ARShades VTO o 3D/AR Viewer.

### 3.4 Dati dello storefront trattati dall'App

Quando un acquirente utilizza VTO o 3D/AR Viewer sullo storefront del merchant, l'App può trattare i seguenti dati tecnici e non riconducibili a un profilo:

* gli identificatori di prodotto e di variante;
* gli identificatori del catalogo ARShades;
* gli identificatori della variante selezionata o dell'ultima variante provata;
* informazioni relative a dispositivo, browser, lingua e sessione;
* eventi tecnici che indicano l'apertura di una sessione VTO o 3D.

Tali dati sono utilizzati per mostrare l'esperienza corretta sullo storefront e per alimentare le analisi di attribuzione descritte alla Sezione 3.6.

### 3.5 Esperienze ARShades per l'utente finale (VTO, 3D/AR Viewer, AR PD Meter)

I trattamenti basati sulla fotocamera che hanno luogo nell'ambito delle esperienze ARShades avviate dallo storefront — inclusi il rendering del Virtual Try-On e il calcolo della distanza pupillare dell'AR PD Meter — sono effettuati dai servizi ARShades e non dall'App Shopify, e sono disciplinati dall'Informativa Privacy principale di ARShades.

In sintesi, e come descritto in tale informativa: le immagini e i flussi video acquisiti dalla fotocamera non vengono conservati; non vengono creati modelli facciali né identificatori biometrici; e, per l'AR PD Meter, i dati tecnici derivati dalla fotocamera che non identificano l'acquirente possono essere temporaneamente trasmessi al backend ARShades ubicato nell'Unione Europea, utilizzati unicamente per restituire il risultato della misurazione e cancellati al termine del trattamento. L'App Shopify di per sé non accede, non conserva né riceve dati provenienti dalla fotocamera.

### 3.6 Shopify Web Pixel e analisi di conversione

L'App utilizza un Shopify Web Pixel per misurare l'attribuzione VTO/3D e le performance di conversione. Il pixel può trattare:

* il dominio dello shop;
* il tipo di evento e la marca temporale;
* un ID di sessione VTO/3D pseudonimizzato;
* gli identificatori di prodotto e di variante;
* gli identificatori di prodotto e di variante del catalogo ARShades;
* gli identificatori del carrello ai fini dell'attribuzione degli eventi di aggiunta al carrello;
* gli identificatori di checkout/ordine, il prezzo totale, la valuta e i metadati delle voci d'ordine (line item) ai fini dell'attribuzione degli acquisti;
* se l'acquisto sia avvenuto a seguito di una sessione VTO/3D o in assenza di una sessione VTO/3D, ai fini delle analisi comparative.

Il pixel è progettato per non trasmettere al backend di analisi ARShades dati di profilo diretti dell'acquirente, quali nome, indirizzo e-mail, numero di telefono o indirizzo di spedizione.

Il pixel dello storefront può utilizzare il local storage del browser per ricordare una sessione VTO/3D attiva ai fini dell'attribuzione. Tali dati di sessione locali scadono dopo 7 giorni o vengono cancellati dopo un acquisto tracciato.

Il pixel viene caricato dal pixel manager di Shopify solo ove il consenso del visitatore corrisponda alle categorie di consenso dichiarate dall'App (quali `analytics`), in conformità con la Customer Privacy API di Shopify e con la configurazione dei consensi del merchant. Rispettiamo tali segnali di consenso e non trattiamo gli eventi del pixel raccolti in assenza del consenso richiesto.

## 4. Finalità e basi giuridiche

Trattiamo i dati sopra descritti per le seguenti finalità:

* installare, autenticare e far funzionare l'App Shopify;
* collegare lo store del merchant a una licenza e a un catalogo ARShades;
* sincronizzare i metadati di prodotti e varianti con ARShades;
* abilitare VTO, 3D/AR Viewer e AR PD Meter sullo storefront;
* gestire i metafield di Shopify e la configurazione dell'App;
* misurare l'attribuzione VTO/3D, gli eventi di aggiunta al carrello e le analisi di conversione degli acquisti;
* garantire la sicurezza dell'App, prevenire abusi e risolvere problemi tecnici;
* adempiere ai requisiti di revisione delle app, privacy e conformità di Shopify;
* dare riscontro alle richieste in materia di privacy e agli obblighi di legge.

A seconda del contesto e della normativa applicabile, le basi giuridiche possono includere l'esecuzione di un contratto, il legittimo interesse, l'adempimento di obblighi di legge e il consenso ove richiesto, ivi compresi i requisiti di consenso relativi all'accesso alla fotocamera o alle analisi.

## 5. Conservazione dei dati

Conserviamo i dati soltanto per il tempo necessario alle finalità descritte nella presente informativa.

* La configurazione attiva dell'App, i metafield di Shopify, le associazioni prodotto/variante e le sessioni OAuth sono conservati per il tempo in cui l'App rimane installata e i dati sono necessari al funzionamento del servizio.
* I dati dell'App specifici dello store sono cancellati o anonimizzati quando Shopify invia un valido webhook di conformità `shop/redact`, salvo che la conservazione sia richiesta dalla legge o per legittime finalità di sicurezza.
* Le analisi del pixel, gli eventi di conversione, i log tecnici, i dati di sessione e i dati storici analoghi sono conservati per un massimo di 14 mesi e sono successivamente aggregati o anonimizzati.
* Gli asset di branding caricati dal merchant e le impostazioni di stile sono conservati per il tempo in cui sono necessari al servizio attivo e vengono rimossi o anonimizzati a seguito di cancellazione, disinstallazione o scadenza del periodo di conservazione applicabile.
* I dati trattati nell'ambito delle esperienze ARShades per l'utente finale (incluso l'AR PD Meter) sono conservati secondo quanto descritto nell'Informativa Privacy principale di ARShades.

## 6. Webhook di privacy e conformità di Shopify

L'App implementa gli endpoint dei webhook di privacy e conformità di Shopify per:

* `customers/data_request`;
* `customers/redact`;
* `shop/redact`.

Le richieste tramite webhook sono verificate mediante la firma HMAC di Shopify; le richieste con firma non valida vengono rifiutate. Completiamo le azioni di richiesta dati e di cancellazione (redaction) entro 30 giorni dal ricevimento del webhook.

Il database dell'App non conserva dati di profilo diretti del cliente finale, quali nome dell'acquirente, indirizzo e-mail, numero di telefono o indirizzo di spedizione. Per le richieste a livello di singolo cliente, verifichiamo il webhook di Shopify e diamo riscontro in base ai dati effettivamente detenuti dall'App.

Il webhook `shop/redact` è inviato da Shopify 48 ore dopo la disinstallazione dell'App. Al suo ricevimento, cancelliamo i dati dell'App conservati per lo shop, incluse le sessioni Shopify, le associazioni di variante sincronizzate e le impostazioni del pixel dello shop, fatti salvi gli obblighi di conservazione previsti dalla legge o per finalità di sicurezza.

## 7. Comunicazione dei dati e sub-responsabili

Comunichiamo i dati soltanto nella misura necessaria per far funzionare, mettere in sicurezza e supportare l'App e i servizi ARShades.

I fornitori di servizi e le infrastrutture confermati e utilizzati per l'App Shopify e per i relativi servizi ARShades comprendono:

* Shopify, per l'installazione dell'app, OAuth, Admin API, theme extensions, Customer Events e l'infrastruttura del Web Pixel;
* Vercel, per l'hosting dell'App Shopify;
* Neon/Vercel Postgres, per l'hosting del database dell'App;
* Google Cloud/Firebase, per le funzioni di backend ARShades e per il trattamento delle analisi, con dati trattati in regioni dell'Unione Europea;
* Cloudways CDN, per la distribuzione degli asset del bundle ARShades sullo storefront.

Tali fornitori trattano i dati in base ai propri termini e agli impegni applicabili in materia di trattamento dei dati. Non vendiamo né condividiamo (secondo la definizione del California Consumer Privacy Act) i dati personali degli acquirenti. Non utilizziamo i dati dell'App Shopify per finalità pubblicitarie non correlate, riconoscimento facciale, identificazione biometrica o addestramento di modelli di IA, e non effettuiamo processi decisionali automatizzati che producano effetti giuridici o effetti analogamente significativi.

Un accordo sul trattamento dei dati (DPA) relativo ai trattamenti dell'App è disponibile per i merchant su richiesta all'indirizzo privacy@spaarkly.com.

## 8. Trasferimenti internazionali

L'App Shopify e i servizi ARShades di analisi e trattamento sono configurati per trattare e conservare i dati pertinenti nell'Unione Europea ove applicabile.

Qualora un fornitore di servizi tratti dati personali al di fuori dello Spazio Economico Europeo (SEE), adottiamo le garanzie appropriate richieste dalla normativa applicabile, quali le Clausole Contrattuali Standard (SCC) o meccanismi di trasferimento equivalenti.

## 9. Sicurezza

Adottiamo misure tecniche e organizzative volte a proteggere i dati trattati dall'App, tra cui:

* HTTPS/TLS per i dati in transito;
* cifratura dei dati a riposo per il database dell'App;
* controlli degli accessi e autenticazione;
* verifica di OAuth e dei webhook di Shopify;
* controlli degli accessi al database;
* minimizzazione degli scope Shopify richiesti;
* logging e monitoraggio operativi ai fini della sicurezza e della risoluzione dei problemi.

Nessun metodo di trasmissione o di conservazione è completamente sicuro, ma ci adoperiamo per mantenere garanzie adeguate alla natura dei dati e ai rischi connessi.

### Risposta agli incidenti di sicurezza

Qualora un incidente di sicurezza interessi dati trattati dall'App, valuteremo l'incidente ai sensi dell'art. 33 GDPR, lo mitigheremo con la massima tempestività e notificheremo all'autorità di controllo competente entro 72 ore, ove richiesto. Poiché disponiamo dei recapiti dei merchant, notificheremo direttamente e senza ingiustificato ritardo i merchant interessati e coopereremo con i processi di gestione degli incidenti di Shopify, ove applicabile.

## 10. Autorizzazioni della fotocamera dell'acquirente

L'accesso alla fotocamera è richiesto dal browser o dal sistema operativo del dispositivo dell'acquirente unicamente nell'ambito delle esperienze ARShades (VTO, AR PD Meter). L'acquirente può rifiutare o revocare l'accesso alla fotocamera tramite le impostazioni del browser o del dispositivo; in caso di rifiuto, tali esperienze potrebbero non funzionare. L'App Shopify di per sé non accede alla fotocamera.

Le modalità di trattamento dei dati della fotocamera nell'ambito delle esperienze ARShades sono descritte nell'Informativa Privacy principale di ARShades.

## 11. Privacy dei minori

L'App è destinata all'uso da parte dei merchant Shopify e degli acquirenti dei loro storefront. I servizi ARShades non sono destinati a raccogliere consapevolmente dati personali di minori al di sotto dell'età applicabile per il consenso digitale senza l'apposito consenso di un genitore o di chi esercita la responsabilità genitoriale.

Qualora Lei ritenga che un minore abbia fornito dati personali tramite ARShades senza l'apposito consenso, La invitiamo a contattarci all'indirizzo privacy@spaarkly.com.

## 12. I Suoi diritti

A seconda del luogo in cui si trova, Lei può disporre dei diritti di accesso, rettifica, cancellazione, limitazione, opposizione al trattamento o di ricevere copia dei Suoi dati personali.

I merchant possono contattarci all'indirizzo privacy@spaarkly.com. Gli acquirenti possono altresì contattare il merchant del cui store hanno usufruito, oppure contattare direttamente Spaarkly ove Spaarkly agisca in qualità di titolare del trattamento per i trattamenti ARShades.

Potremmo aver bisogno di informazioni quali il dominio dello shop, la data/ora approssimativa, gli identificatori degli eventi, i dettagli del dispositivo/della sessione o altre informazioni al fine di individuare i registri pertinenti.

Lei ha inoltre il diritto di proporre reclamo a un'autorità di controllo, quale il Garante per la Protezione dei Dati Personali ([www.garanteprivacy.it](https://www.garanteprivacy.it)) o l'autorità competente nel Suo Paese di residenza.

## 13. Modifiche alla presente informativa

Potremmo aggiornare la presente Informativa Privacy per riflettere modifiche all'App Shopify, ai servizi ARShades, ai requisiti di legge o alle prassi operative. In caso di aggiornamento dell'informativa, provvederemo a rivedere la data di "Ultimo aggiornamento".

## 14. Contatti

Per domande o richieste in materia di privacy, La invitiamo a contattare:

**Spaarkly s.r.l.**  
Via della Tecnica n. 18  
85100 Potenza, Italia  
Email: privacy@spaarkly.com
