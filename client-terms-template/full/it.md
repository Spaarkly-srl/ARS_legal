---
published: false
---

# CONDIZIONI D'USO DELLE FUNZIONALITÀ ARSHADES

*{{client_trade_name}} — {{website_url}}* </br> *Documento integrativo dei [Termini e Condizioni]({{client_terms_url}}) di {{client_legal_name}} — generato dal modello Spaarkly «Client ARShades Integration Terms» v{{template_version}} del {{generated_date}}*

<!-- ============================================================
  MODELLO SPAARKLY — QUESTO FILE NON È UN DOCUMENTO IN VIGORE.
  Variabili {{…}} da compilare (v. ../schema.json); i blocchi
  {{#flag}}…{{/flag}} sono inclusi solo se il flag è attivo.
  I blocchi [CORE] non sono modificabili dal Cliente (v. ../README.md).
  L'istanza generata deve essere rivista dal consulente legale del
  Cliente prima della pubblicazione.
  ============================================================ -->

<!-- BLOCK ruoli [CORE] -->
## Chi fornisce che cosa

**«{{client_trade_name}}»**, **«noi»** o **«nostro»** indica {{client_legal_name}}, con sede in {{client_registered_office}} ({{client_country}}), {{client_vat}}, che gestisce {{website_url}} e offre l'esperienza commerciale: cataloghi e collezioni, prezzi, disponibilità, ordini, assistenza{{#prescription_sales_enabled}}, gestione delle prescrizioni{{/prescription_sales_enabled}} e l'intero percorso di acquisto.

**«Spaarkly»** indica Spaarkly s.r.l. (P. IVA IT02077620769, Via della Tecnica 18, 85100 Potenza, Italia), che sviluppa e fornisce le soluzioni software di realtà aumentata **ARShades** integrate nella nostra esperienza. Spaarkly non è il venditore dei prodotti presentati, non gestisce un marketplace e non è un ottico, un optometrista né altro operatore dell'assistenza oculistica.

L'utilizzo delle funzionalità ARShades è disciplinato dai [Termini e Condizioni d'Uso — Servizi ARShades](https://spaarkly-srl.github.io/ARS_legal/terms/it/) di Spaarkly, che l'Utente accetta separatamente{{#ar_pd_enabled}}, e — per AR PD Meter — dai relativi [Termini dedicati](https://spaarkly-srl.github.io/ARS_legal/terms-ar-pd-meter/it/){{/ar_pd_enabled}}. Il presente documento non li sostituisce: chiarisce come le funzionalità ARShades si inseriscono nella nostra esperienza di acquisto e quali responsabilità restano nostre.
<!-- /BLOCK ruoli -->

<!-- BLOCK funzionalita [CORE] -->
## Le funzionalità ARShades disponibili

{{#vto_enabled}}- **Virtual Try-On (VTO)** — la prova virtuale degli occhiali in realtà aumentata tramite la fotocamera del dispositivo.{{/vto_enabled}}
{{#vto_explorer_enabled}}- **VTO Explorer** — anteprime personalizzate di più modelli a partire da un numero limitato di immagini acquisite durante la sessione ed elaborate localmente sul dispositivo.{{/vto_explorer_enabled}}
{{#mirror_enabled}}- **Mirror** — l'esperienza di prova virtuale su dispositivo dedicato presso i nostri punti vendita o showroom; la disponibilità e le condizioni materiali di utilizzo del dispositivo sono di nostra responsabilità.{{/mirror_enabled}}
{{#campaign_catalogue_enabled}}- **Campaign Catalogue** — il catalogo digitale curato con cui presentiamo collezioni o campagne selezionate; prodotti, prezzi e informazioni commerciali sono scelti e gestiti da noi.{{/campaign_catalogue_enabled}}
{{#ar_pd_enabled}}- **AR PD Meter** — la stima digitale della distanza pupillare, descritta nella sezione dedicata.{{/ar_pd_enabled}}

{{#mobile_app_enabled}}Le funzionalità ARShades sono disponibili anche all'interno della nostra applicazione mobile; il download e l'uso dell'app sono soggetti anche ai termini dell'app store applicabile, oltre che ai Termini Spaarkly.{{/mobile_app_enabled}}

Requisiti minimi per le funzionalità basate sulla fotocamera: connessione Internet stabile, dispositivo dotato di fotocamera e autorizzazione all'accesso alla fotocamera per la durata dell'esperienza.
<!-- /BLOCK funzionalita -->

<!-- BLOCK natura [CORE] -->
## Natura dell'esperienza virtuale

La prova virtuale è un **ausilio visivo**: per limiti tecnici la resa (aspetto, colori, vestibilità, dimensioni) può differire dal prodotto fisico e varia in funzione di dispositivo, fotocamera, illuminazione e ambiente. Le decisioni di acquisto restano dell'Utente; l'esperienza virtuale non costituisce garanzia di idoneità, disponibilità o aspetto del prodotto. Salvo diversa indicazione, le funzionalità ARShades sono offerte agli Utenti a titolo gratuito.
<!-- /BLOCK natura -->

{{#ar_pd_enabled}}
<!-- BLOCK ar-pd-meter [CORE] -->
## AR PD Meter — stima digitale preliminare

**AR PD Meter** fornisce una **stima della distanza pupillare (PD)** dell'Utente utilizzando la fotocamera del dispositivo e il rilevamento dei landmark facciali. È una **stima digitale preliminare**, offerta a supporto della selezione degli occhiali durante l'esperienza di acquisto: **non è un dispositivo medico**, non ha finalità mediche, cliniche o diagnostiche e **non sostituisce una misurazione effettuata da un professionista qualificato della visione** (quale un ottico, un optometrista o un medico oculista). L'accuratezza può essere influenzata da illuminazione, qualità della fotocamera, distanza, angolazione, posizione del volto e movimenti.

**Consenso.** L'avvio della misurazione richiede il **consenso espresso dell'Utente, reso a Spaarkly** quale titolare del trattamento, mediante la casella di accettazione presentata prima della misurazione; il flusso di consenso indica la versione e la data dei Termini AR PD Meter in vigore e riepiloga i dati trattati, la finalità, la conservazione e le modalità di revoca. Le immagini della fotocamera sono elaborate sul dispositivo dell'Utente e **non sono trasmesse a Spaarkly né da Spaarkly conservate**; soltanto dati tecnici derivati (coordinate dei landmark facciali, dati di orientamento del volto, informazioni sul dispositivo) — non utilizzati per identificare l'Utente e non idonei, di per sé, a identificarlo — sono trasmessi cifrati al backend di Spaarkly nell'**Unione Europea**, utilizzati esclusivamente per calcolare e restituire la misurazione e **cancellati in modo permanente immediatamente dopo l'elaborazione**{{#mirror_enabled}}; nelle esperienze Mirror l'elaborazione avviene sul backend locale del dispositivo, senza alcuna trasmissione a server cloud{{/mirror_enabled}}.

**Età.** AR PD Meter è destinato a utenti che abbiano **almeno 18 anni**; l'Utente minore di 18 anni può utilizzarlo soltanto con il consenso e sotto la supervisione di un genitore o di un tutore legale.

{{#prescription_sales_enabled}}**Uso nel nostro processo di vendita.** La stima AR PD Meter è per noi soltanto un **dato preliminare di supporto** e **non è mai utilizzata come misura definitiva** per la fornitura di lenti graduate: prima della realizzazione di occhiali da vista, la distanza pupillare e gli altri parametri necessari sono verificati o confermati da un professionista qualificato della visione, secondo il nostro processo di vendita e la normativa applicabile. La responsabilità di tale verifica è nostra, non di Spaarkly.{{/prescription_sales_enabled}}{{^prescription_sales_enabled}}**Uso nel nostro processo di vendita.** Non vendiamo lenti graduate attraverso {{website_url}}: la stima AR PD Meter è utilizzata esclusivamente come supporto alla selezione di montature e occhiali non graduati.{{/prescription_sales_enabled}}
<!-- /BLOCK ar-pd-meter -->
{{/ar_pd_enabled}}

{{#shoot_share_enabled}}
<!-- BLOCK shoot-share [CORE] -->
## Foto e «Shoot & Share»

Le immagini eventualmente acquisite durante una sessione VTO Explorer sono elaborate localmente sul dispositivo impiegato per l'esperienza e **non vengono caricate automaticamente** sui server di Spaarkly. Se l'esperienza avviene su un dispositivo installato presso un punto vendita, uno showroom, la sede di un evento o altro luogo aperto al pubblico e l'Utente sceglie di ottenere, scaricare o condividere le foto finali («Shoot & Share» o funzioni equivalenti), **esclusivamente le foto finali selezionate dall'Utente** vengono caricate temporaneamente sui server di Spaarkly, al solo fine di renderle disponibili all'Utente, e sono cancellate al più tardi entro 24 ore (prima, se l'Utente le cancella).
<!-- /BLOCK shoot-share -->
{{/shoot_share_enabled}}

<!-- BLOCK privacy [CORE] -->
## Privacy

Per i trattamenti di dati personali eseguiti dalle funzionalità ARShades — inclusi i landmark facciali elaborati **in tempo reale e localmente sul dispositivo** al solo scopo di posizionare gli occhiali virtuali, senza memorizzazione né trasmissione{{#ar_pd_enabled}}, e il flusso AR PD Meter descritto sopra{{/ar_pd_enabled}} — il **titolare del trattamento è Spaarkly s.r.l.**: si applica l'[Informativa Privacy ARShades](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/it/) (contatto: privacy@spaarkly.com).

Per i trattamenti che eseguiamo noi in qualità di titolari — account, ordini, pagamenti, assistenza, marketing e ogni altro trattamento legato a {{website_url}} — si applica la nostra [informativa privacy]({{client_privacy_url}}).
<!-- /BLOCK privacy -->

<!-- BLOCK venditore [CLIENT] -->
## Le nostre responsabilità di venditore

Siamo noi — e non Spaarkly — i responsabili dei prodotti presentati e venduti su {{website_url}}: prezzi, disponibilità, descrizioni e dichiarazioni sui prodotti, conformità, consegna, garanzia legale, resi e assistenza, secondo i nostri [Termini e Condizioni]({{client_terms_url}}).{{#prescription_sales_enabled}} La dispensazione di lenti graduate avviene sotto la nostra responsabilità, nel rispetto della normativa applicabile e con la verifica professionale descritta nella sezione AR PD Meter.{{/prescription_sales_enabled}} Eventuali acquisti o altre operazioni conclusi dall'Utente con noi sono disciplinati esclusivamente dai nostri termini.
<!-- /BLOCK venditore -->

<!-- BLOCK ip [CORE] -->
## Proprietà intellettuale

Le soluzioni ARShades — software, algoritmi e interfacce — e i relativi diritti di proprietà intellettuale sono e restano di **Spaarkly o dei suoi licenzianti**. I modelli 3D e i contenuti visualizzati possono essere nostri, di Spaarkly o dei rispettivi licenzianti e sono forniti a soli fini di visualizzazione. Restano fermi i divieti previsti dai Termini Spaarkly, tra cui copia, estrazione o scraping dei modelli 3D, reverse engineering e qualsiasi uso commerciale non autorizzato.
<!-- /BLOCK ip -->

<!-- BLOCK minori [CLIENT] -->
## Minori

{{#minors_enabled}}Le funzionalità ARShades sono destinate a un pubblico generale: gli Utenti di età inferiore a quella alla quale possono validamente prestare il consenso in relazione ai servizi della società dell'informazione nel proprio Paese di residenza (in Italia, 14 anni) possono utilizzarle soltanto con il consenso o l'autorizzazione di un genitore o di un tutore legale, ove richiesto dalla legge applicabile.{{#ar_pd_enabled}} Ad AR PD Meter si applica in ogni caso il requisito di età indicato nella sezione dedicata (18 anni).{{/ar_pd_enabled}}{{/minors_enabled}}{{^minors_enabled}}L'esperienza di acquisto su {{website_url}} è destinata a utenti maggiorenni.{{/minors_enabled}}
<!-- /BLOCK minori -->

<!-- BLOCK rapporto-documenti [CORE] -->
## Rapporto con gli altri documenti

Il presente documento è parte integrante dei nostri [Termini e Condizioni]({{client_terms_url}}), che ne disciplinano anche la legge applicabile e il foro competente, e va letto insieme ai [Termini Spaarkly](https://spaarkly-srl.github.io/ARS_legal/terms/it/){{#ar_pd_enabled}}, ai [Termini AR PD Meter](https://spaarkly-srl.github.io/ARS_legal/terms-ar-pd-meter/it/){{/ar_pd_enabled}} e all'[Informativa Privacy ARShades](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/it/). Per il funzionamento delle funzionalità ARShades e per i trattamenti di cui Spaarkly è titolare prevalgono i documenti Spaarkly; per l'esperienza commerciale prevalgono i nostri termini. Nulla nel presente documento esclude, limita o pregiudica i diritti riconosciuti all'Utente da norme imperative, inclusi i diritti dei consumatori.
<!-- /BLOCK rapporto-documenti -->

<!-- BLOCK contatti [CLIENT] -->
## Contatti

Per domande sull'esperienza di acquisto: **{{support_email}}**.

Per questioni relative alle funzionalità ARShades: **legal@spaarkly.com**; per la privacy ARShades: **privacy@spaarkly.com**.
<!-- /BLOCK contatti -->
