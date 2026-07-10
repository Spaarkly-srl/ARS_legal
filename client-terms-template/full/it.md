---
published: false
---

# TERMINI E CONDIZIONI D'USO — FUNZIONALITÀ ARSHADES

*{{client_trade_name}} — {{website_url}}* </br> *Condizioni di {{client_legal_name}}, presentate all'avvio dell'esperienza — generate dal modello Spaarkly «Client ARShades Integration Terms — Servizi VTO» v{{template_version}} del {{generated_date}}*

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
## Chi fornisce che cosa

**«{{client_trade_name}}»**, **«noi»** o **«nostro»** indica {{client_legal_name}}, con sede in {{client_registered_office}} ({{client_country}}), {{client_vat}}, che gestisce {{website_url}} e offre l'esperienza commerciale: cataloghi e collezioni, prezzi, disponibilità, ordini, assistenza{{#prescription_sales_enabled}}, gestione delle prescrizioni{{/prescription_sales_enabled}} e l'intero percorso di acquisto.

**«Spaarkly»** indica Spaarkly s.r.l. (P. IVA IT02077620769), che sviluppa e fornisce le soluzioni software di realtà aumentata **ARShades** integrate nella nostra esperienza. Spaarkly non è il venditore dei prodotti presentati, non gestisce un marketplace e non è un ottico, un optometrista né altro operatore dell'assistenza oculistica.

Le presenti condizioni («Condizioni») sono presentate all'Utente, insieme all'[Informativa Privacy ARShades](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/it/), prima dell'avvio dell'esperienza e ne disciplinano l'uso. Cliccando su «Accetta» (o compiendo un'azione equivalente) l'Utente le accetta; in mancanza di accettazione l'esperienza non viene avviata. Durante l'esperienza l'Utente può in qualsiasi momento rileggere i documenti e revocare il proprio consenso dalle impostazioni.
<!-- /BLOCK ruoli -->

<!-- BLOCK funzionalita [CORE] -->
## Le funzionalità ARShades disponibili

{{#vto_enabled}}- **Virtual Try-On (VTO)** — la prova virtuale degli occhiali in realtà aumentata tramite la fotocamera del dispositivo.{{/vto_enabled}}
{{#viewer_3d_enabled}}- **3D Viewer** — la visualizzazione tridimensionale che consente l'esplorazione a 360° dei modelli di occhiali (rotazione e zoom) e, ove il dispositivo lo supporti, la loro visualizzazione in realtà aumentata.{{/viewer_3d_enabled}}
{{#vto_explorer_enabled}}- **VTO Explorer** — anteprime personalizzate di più modelli a partire da un numero limitato di immagini acquisite durante la sessione ed elaborate localmente sul dispositivo.{{/vto_explorer_enabled}}
{{#mirror_enabled}}- **Mirror** — l'esperienza di prova virtuale su dispositivo dedicato presso i nostri punti vendita o showroom; la disponibilità e le condizioni materiali di utilizzo del dispositivo sono di nostra responsabilità.{{/mirror_enabled}}
{{#gateway_enabled}}- **Gateway** — la piattaforma ARShades che offre esperienze di prova virtuale e un accesso unificato alle esperienze ARShades e agli store dei marchi; può facoltativamente utilizzare la geolocalizzazione, previo consenso.{{/gateway_enabled}}
{{#campaign_catalogue_enabled}}- **Campaign Catalogue** — il catalogo digitale curato con cui presentiamo collezioni o campagne selezionate; prodotti, prezzi e informazioni commerciali sono scelti e gestiti da noi.{{/campaign_catalogue_enabled}}

{{#mobile_app_enabled}}Le funzionalità ARShades sono disponibili anche all'interno della nostra applicazione mobile; il download e l'uso dell'app sono soggetti anche ai termini dell'app store applicabile (Apple App Store o Google Play).{{/mobile_app_enabled}}

Requisiti minimi per le funzionalità basate sulla fotocamera: connessione Internet stabile, dispositivo dotato di fotocamera e autorizzazione all'accesso alla fotocamera per la durata dell'esperienza. Le immagini della fotocamera sono elaborate in tempo reale sul dispositivo dell'Utente per posizionare gli occhiali virtuali: non vengono memorizzate né trasmesse ai server di Spaarkly.
<!-- /BLOCK funzionalita -->

<!-- BLOCK natura [CORE] -->
## Natura dell'esperienza virtuale

La prova virtuale e la visualizzazione dei modelli sono un **ausilio visivo**: per limiti tecnici la resa (aspetto, colori, vestibilità, dimensioni) può differire dal prodotto fisico e varia in funzione di dispositivo, fotocamera, illuminazione e ambiente. Le decisioni di acquisto restano dell'Utente; l'esperienza virtuale non costituisce garanzia di idoneità, disponibilità o aspetto del prodotto. Salvo diversa indicazione, le funzionalità ARShades sono offerte agli Utenti a titolo gratuito.
<!-- /BLOCK natura -->

{{#shoot_share_enabled}}
<!-- BLOCK shoot-share [CORE] -->
## Foto e «Shoot & Share»

Le immagini eventualmente acquisite durante una sessione VTO Explorer sono elaborate localmente sul dispositivo impiegato per l'esperienza e **non vengono caricate automaticamente** sui server di Spaarkly. Se l'esperienza avviene su un dispositivo installato presso un punto vendita, uno showroom, la sede di un evento o altro luogo aperto al pubblico e l'Utente sceglie di ottenere, scaricare o condividere le foto finali («Shoot & Share» o funzioni equivalenti), **esclusivamente le foto finali selezionate dall'Utente** vengono caricate temporaneamente sui server di Spaarkly, al solo fine di renderle disponibili all'Utente, e sono cancellate al più tardi entro 24 ore (prima, se l'Utente le cancella).
<!-- /BLOCK shoot-share -->
{{/shoot_share_enabled}}

<!-- BLOCK privacy [CORE] -->
## Privacy

Per i trattamenti di dati personali eseguiti dalle funzionalità ARShades — inclusi i landmark facciali elaborati **in tempo reale e localmente sul dispositivo** al solo scopo di posizionare gli occhiali virtuali, senza memorizzazione né trasmissione — il **titolare del trattamento è Spaarkly s.r.l.**: si applica l'[Informativa Privacy ARShades](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/it/) (contatto: privacy@spaarkly.com), presentata insieme alle presenti Condizioni. Noi non accediamo ai dati personali trattati dalle funzionalità ARShades né al relativo trattamento: riceviamo da Spaarkly esclusivamente dati aggregati e anonimizzati; per questo Spaarkly resta titolare del trattamento per i trattamenti ARShades.

Per i trattamenti che eseguiamo noi in qualità di titolari — account, ordini, pagamenti, assistenza, marketing e ogni altro trattamento legato a {{website_url}} — si applica la nostra [informativa privacy]({{client_privacy_url}}).
<!-- /BLOCK privacy -->

<!-- BLOCK venditore [CLIENT] -->
## Le nostre responsabilità di venditore

Siamo noi — e non Spaarkly — i responsabili dei prodotti presentati e venduti su {{website_url}}: prezzi, disponibilità, descrizioni e dichiarazioni sui prodotti, conformità, consegna, garanzia legale, resi e assistenza, secondo i nostri [Termini e Condizioni]({{client_terms_url}}).{{#prescription_sales_enabled}} La dispensazione di lenti graduate avviene sotto la nostra responsabilità, nel rispetto della normativa applicabile.{{/prescription_sales_enabled}} Eventuali acquisti o altre operazioni conclusi dall'Utente con noi sono disciplinati esclusivamente dai nostri termini.
<!-- /BLOCK venditore -->

<!-- BLOCK ip [CORE] -->
## Proprietà intellettuale

Le soluzioni ARShades — software, algoritmi e interfacce — e i relativi diritti di proprietà intellettuale sono e restano di **Spaarkly o dei suoi licenzianti**. I modelli 3D e i contenuti visualizzati possono essere nostri, di Spaarkly o dei rispettivi licenzianti e sono forniti a soli fini di visualizzazione. È vietato in particolare copiare, riprodurre, estrarre o raccogliere mediante scraping i modelli 3D e i contenuti, decompilare o sottoporre a reverse engineering il software (salvo quanto consentito da norme inderogabili) e ogni uso commerciale non autorizzato delle soluzioni ARShades.
<!-- /BLOCK ip -->

<!-- BLOCK minori [CLIENT] -->
## Minori

{{#minors_enabled}}Le funzionalità ARShades sono destinate a un pubblico generale: gli Utenti di età inferiore a quella alla quale possono validamente prestare il consenso in relazione ai servizi della società dell'informazione nel proprio Paese di residenza (in Italia, 14 anni) possono utilizzarle soltanto con il consenso o l'autorizzazione di un genitore o di un tutore legale, ove richiesto dalla legge applicabile.{{/minors_enabled}}{{^minors_enabled}}L'esperienza di acquisto su {{website_url}} è destinata a utenti maggiorenni.{{/minors_enabled}}
<!-- /BLOCK minori -->

<!-- BLOCK terzo-beneficiario [CORE] -->
## Spaarkly quale terzo beneficiario

Le previsioni delle presenti Condizioni relative alla tecnologia ARShades, alla natura dell'esperienza virtuale, alla proprietà intellettuale e alle esclusioni e limitazioni ad esse collegate sono pattuite, nell'interesse del Cliente, anche a favore di Spaarkly, ai sensi dell'articolo 1411 del codice civile italiano, e Spaarkly può farle valere direttamente nei confronti dell'Utente. La presente clausola non pregiudica i diritti riconosciuti all'Utente da norme imperative.
<!-- /BLOCK terzo-beneficiario -->

<!-- BLOCK rapporto-documenti [CORE] -->
## Rapporto con gli altri documenti

Le presenti Condizioni si applicano all'uso delle funzionalità ARShades all'interno della nostra esperienza. Gli acquisti e ogni altro rapporto commerciale con noi restano disciplinati dai nostri [Termini e Condizioni]({{client_terms_url}}), che regolano anche la legge applicabile e il foro competente. Per i trattamenti di dati personali di cui Spaarkly è titolare si applica l'[Informativa Privacy ARShades](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/it/). Nulla nelle presenti Condizioni esclude, limita o pregiudica i diritti riconosciuti all'Utente da norme imperative, inclusi i diritti dei consumatori.
<!-- /BLOCK rapporto-documenti -->

<!-- BLOCK contatti [CLIENT] -->
## Contatti

Per domande sull'esperienza di acquisto: **{{support_email}}**.

Per questioni relative alle funzionalità ARShades: **legal@spaarkly.com**; per la privacy ARShades: **privacy@spaarkly.com**.
<!-- /BLOCK contatti -->

---

Cliccando su «Accetta», o utilizzando le funzionalità ARShades dopo aver avuto la possibilità di prenderne visione, l'Utente dichiara di aver letto e compreso le presenti Condizioni e di accettarle.
