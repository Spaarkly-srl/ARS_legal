---
published: false
---

# TERMINI E CONDIZIONI D'USO — AR PD METER

*{{client_trade_name}} — {{website_url}}* </br> *Condizioni di {{client_legal_name}}, presentate prima della misurazione — generate dal modello Spaarkly «Client ARShades Integration Terms — AR PD Meter» v{{template_version}} del {{generated_date}}*

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
## Chi fornisce che cosa

**«{{client_trade_name}}»**, **«noi»** o **«nostro»** indica {{client_legal_name}}, con sede in {{client_registered_office}} ({{client_country}}), {{client_vat}}, che gestisce {{website_url}} e offre l'esperienza commerciale.

**«Spaarkly»** indica Spaarkly s.r.l. (P. IVA IT02077620769, Via della Tecnica 18, 85100 Potenza, Italia), che sviluppa e fornisce **AR PD Meter**, la funzionalità ARShades descritta di seguito, ed è **titolare del trattamento** dei dati personali trattati da tale funzionalità. Spaarkly non è il venditore dei prodotti presentati, non gestisce un marketplace e non è un ottico, un optometrista né altro operatore dell'assistenza oculistica.

Le presenti condizioni («Condizioni AR PD Meter») sono presentate all'Utente, insieme all'[Informativa Privacy ARShades](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/it/), prima dell'avvio della misurazione. Selezionando la casella di accettazione l'Utente le accetta e presta il proprio consenso espresso al trattamento descritto sotto; in mancanza di accettazione la misurazione non viene avviata. L'Utente può revocare il consenso in qualsiasi momento interrompendo la misurazione o revocando l'accesso alla fotocamera; la revoca non pregiudica i trattamenti già effettuati.
<!-- /BLOCK ruoli -->

<!-- BLOCK cos-e [CORE] -->
## Che cos'è AR PD Meter

**AR PD Meter** fornisce una **stima della distanza pupillare (PD)** dell'Utente utilizzando la fotocamera del dispositivo e il rilevamento dei landmark facciali. È una **stima digitale preliminare**, offerta a supporto della selezione degli occhiali durante l'esperienza di acquisto: **non è un dispositivo medico**, non ha finalità mediche, cliniche o diagnostiche e **non sostituisce una misurazione effettuata da un professionista qualificato della visione** (quale un ottico, un optometrista o un medico oculista). L'accuratezza può essere influenzata da illuminazione, qualità della fotocamera, distanza, angolazione, posizione del volto e movimenti.
<!-- /BLOCK cos-e -->

<!-- BLOCK consenso-dati [CORE] -->
## Consenso e trattamento dei dati

L'avvio della misurazione richiede il **consenso espresso dell'Utente, reso a Spaarkly** quale titolare del trattamento, mediante la casella di accettazione presentata prima della misurazione. Il flusso di consenso indica la versione e la data delle presenti Condizioni AR PD Meter in vigore e riepiloga i dati trattati, la finalità, la conservazione e le modalità di revoca.

Le immagini della fotocamera sono elaborate sul dispositivo dell'Utente e **non sono trasmesse a Spaarkly né da Spaarkly conservate**. Soltanto dati tecnici derivati (coordinate dei landmark facciali, dati di orientamento del volto, informazioni sul dispositivo) — non utilizzati per identificare l'Utente e non idonei, di per sé, a identificarlo — sono trasmessi cifrati al backend di Spaarkly nell'**Unione Europea**, utilizzati esclusivamente per calcolare e restituire la misurazione e **cancellati in modo permanente immediatamente dopo l'elaborazione**.{{#mirror_enabled}} Quando la misurazione avviene su un dispositivo **Mirror** presso i nostri punti vendita o showroom, l'elaborazione avviene sul backend locale del dispositivo, senza alcuna trasmissione a server cloud.{{/mirror_enabled}}

Ove le leggi applicabili in materia di privacy biometrica lo richiedano, l'accettazione affermativa dell'Utente costituisce il consenso/la liberatoria scritta al trattamento descritto, prestato prima di qualsiasi acquisizione. I dettagli completi sono nell'[Informativa Privacy ARShades](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/it/), di cui Spaarkly è titolare.
<!-- /BLOCK consenso-dati -->

<!-- BLOCK eta [CORE] -->
## Età

AR PD Meter è destinato a utenti che abbiano **almeno 18 anni**. L'Utente minore di 18 anni può utilizzarlo soltanto con il consenso e sotto la supervisione di un genitore o di un tutore legale.
<!-- /BLOCK eta -->

<!-- BLOCK uso-vendita [CLIENT] -->
## Uso nel nostro processo di vendita

{{#prescription_sales_enabled}}La stima AR PD Meter è per noi soltanto un **dato preliminare di supporto** e **non è mai utilizzata come misura definitiva** per la fornitura di lenti graduate: prima della realizzazione di occhiali da vista, la distanza pupillare e gli altri parametri necessari sono verificati o confermati da un professionista qualificato della visione, secondo il nostro processo di vendita e la normativa applicabile. La responsabilità di tale verifica è nostra, non di Spaarkly.{{/prescription_sales_enabled}}{{^prescription_sales_enabled}}Non vendiamo lenti graduate attraverso {{website_url}}: la stima AR PD Meter è utilizzata esclusivamente come supporto alla selezione di montature e occhiali non graduati.{{/prescription_sales_enabled}}
<!-- /BLOCK uso-vendita -->

<!-- BLOCK privacy [CORE] -->
## Privacy

Per il trattamento eseguito da AR PD Meter — descritto sopra — il **titolare del trattamento è Spaarkly s.r.l.**: si applica l'[Informativa Privacy ARShades](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/it/) (contatto: privacy@spaarkly.com), presentata insieme alle presenti Condizioni AR PD Meter.

Per i trattamenti che eseguiamo noi in qualità di titolari — account, ordini, assistenza e ogni altro trattamento legato a {{website_url}} — si applica la nostra [informativa privacy]({{client_privacy_url}}).
<!-- /BLOCK privacy -->

<!-- BLOCK ip [CORE] -->
## Proprietà intellettuale

AR PD Meter — software, algoritmi e interfacce — e i relativi diritti di proprietà intellettuale sono e restano di **Spaarkly o dei suoi licenzianti**. All'Utente non è trasferito alcun diritto di proprietà; sono vietati il reverse engineering (salvo quanto consentito da norme inderogabili) e ogni uso non autorizzato della funzionalità.
<!-- /BLOCK ip -->

<!-- BLOCK terzo-beneficiario [CORE] -->
## Spaarkly quale terzo beneficiario

Le previsioni delle presenti Condizioni AR PD Meter relative alla tecnologia, alla natura della stima, al trattamento dei dati, alla proprietà intellettuale e alle esclusioni e limitazioni ad esse collegate sono pattuite anche a favore di Spaarkly, ai sensi dell'articolo 1411 del codice civile italiano, e Spaarkly può farle valere direttamente nei confronti dell'Utente. La presente clausola non pregiudica i diritti riconosciuti all'Utente da norme imperative.
<!-- /BLOCK terzo-beneficiario -->

<!-- BLOCK rapporto-documenti [CORE] -->
## Rapporto con gli altri documenti

Le presenti Condizioni AR PD Meter si applicano esclusivamente all'uso della funzionalità AR PD Meter. Gli acquisti e ogni altro rapporto commerciale con noi restano disciplinati dai nostri [Termini e Condizioni]({{client_terms_url}}), che regolano anche la legge applicabile e il foro competente. Per il trattamento di dati personali di cui Spaarkly è titolare si applica l'[Informativa Privacy ARShades](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/it/). Nulla nelle presenti Condizioni AR PD Meter esclude, limita o pregiudica i diritti riconosciuti all'Utente da norme imperative, inclusi i diritti dei consumatori.
<!-- /BLOCK rapporto-documenti -->

<!-- BLOCK contatti [CLIENT] -->
## Contatti

Per domande sull'esperienza di acquisto: **{{support_email}}**.

Per questioni relative ad AR PD Meter: **legal@spaarkly.com**; per la privacy ARShades: **privacy@spaarkly.com**.
<!-- /BLOCK contatti -->

---

Selezionando la casella di accettazione o utilizzando AR PD Meter, l'Utente dichiara di aver letto e compreso le presenti Condizioni AR PD Meter, le accetta e presta il proprio consenso espresso al trattamento descritto.
