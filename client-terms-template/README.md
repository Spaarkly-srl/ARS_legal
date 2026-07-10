---
published: false
---

# Client ARShades Integration Terms — Modello (v0.2.1)

Modello dei **termini di integrazione ARShades "a nome del Cliente" (white-label)**, rispecchia la separazione canonica in **due documenti indipendenti**:

- **Servizi VTO** — questa cartella (`client-terms-template/`): VTO, 3D Viewer, VTO Explorer, Mirror, Gateway, Campaign Catalogue.
- **AR PD Meter** — cartella separata [`client-terms-ar-pd-meter-template/`](../client-terms-ar-pd-meter-template/): documento autosufficiente e snello per la stima della distanza pupillare.

**I due documenti sono indipendenti: nessun rinvio incrociato**, anche quando il Cliente ha entrambe le soluzioni (decisione 2026-07-10). Ciascuno è mostrato e **accettato nel modulo consenso ARShades** prima della rispettiva esperienza; il modulo in-experience è l'unico punto di accettazione (nessun task legale su sito, footer o UI del Cliente). Ogni template produce due output: **full** (il testo accettato nel modulo) e **short-clause** (articolo da incollare nel corpo dei T&C del Cliente long-term). Lo **schema dei parametri** ([schema.json](schema.json)) e la [intake-checklist](intake-checklist/it.md) sono condivisi tra i due template.

**Non è un documento in vigore e non sono "i Termini Spaarkly a nome del cliente":** è un documento distinto, il cui oggetto è l'integrazione di ARShades nell'esperienza commerciale del Cliente. La [Privacy Policy](../privacy-policy/it.md) ARShades resta il documento canonico del titolare e si applica sempre, in ogni configurazione; i [Termini Spaarkly](../terms/it.md) e i [Termini AR PD Meter](../terms-ar-pd-meter/it.md) restano in vigore per le esperienze non white-label. **L'utente finale di un Cliente white-label accetta le condizioni del Cliente nel modulo — mai i Termini Spaarkly**: la sostanza è garantita dai blocchi [CORE] e dalla clausola di terzo beneficiario (art. 1411 c.c.).

## Principio dei ruoli (non negoziabile)

- Il **Cliente** offre l'esperienza commerciale sul proprio sito: vende/procura i prodotti, gestisce prezzi, disponibilità, prescrizioni e customer journey.
- **Spaarkly** fornisce la tecnologia ARShades e **resta titolare del trattamento** per i trattamenti descritti nella Privacy Policy ARShades. I ruoli privacy sono funzionali (EDPB Guidelines 07/2020): non si spostano per etichetta contrattuale. Il consenso espresso AR PD Meter (inclusa la written release BIPA/CUBI/RCW) è **sempre reso a Spaarkly**, mai al Cliente. Il **Cliente non accede** ai dati personali trattati dalle funzionalità ARShades né al relativo trattamento e riceve da Spaarkly **soltanto dati aggregati e anonimizzati**: è un ulteriore motivo per cui Spaarkly resta titolare per i trattamenti ARShades.
- Il **modulo consenso in-experience** è l'unico punto di accettazione e raccolta del consenso: **gating locale in-experience** — l'esperienza si avvia solo dopo il consenso esplicito, la revoca è sempre disponibile con interruzione immediata. **Nessuna prova del consenso persistente associabile all'Utente**, perché Spaarkly non identifica l'utente finale: ne dà evidenza l'avvio stesso dell'esperienza, subordinato al consenso (nessuna persistenza server-side). Le istanze white-label sono servite al modulo dalla collezione Firestore **`ARS_TermsAndCond`**; le collezioni legacy del VTO web sono obsolete e verranno eliminate.

## Superfici (dove valgono queste condizioni)

- **Web / e-commerce del Cliente** — modulo consenso ARShades standard nel sito del Cliente; l'istanza white-label è servita al modulo dalla collezione `ARS_TermsAndCond`. È il caso d'uso primario del modello.
- **Mirror** — tutto in locale, UI gestita da Spaarkly e customizzata per il Cliente: disclaimer e consenso li colloca **Spaarkly** nella UI del dispositivo. Al Cliente restano solo le condizioni materiali del dispositivo (già coperte dal blocco funzionalità del documento full).
- **App ARShades (nostre)** — nessun impatto: valgono i [Termini Spaarkly](../terms/it.md) e i [Termini AR PD Meter](../terms-ar-pd-meter/it.md) canonici.
- **App branded per il Cliente** — si clonano disclaimer e flussi delle app ARShades; il white-label dei termini usa lo stesso meccanismo di questo modello.

## Uso del modello

1. Compilare la [intake checklist](intake-checklist/it.md) con il Cliente (unica per entrambi i template).
2. Valorizzare le variabili secondo [schema.json](schema.json).
3. Generare gli output pertinenti alle soluzioni attive:
   - se è attiva almeno una soluzione VTO → [full](full/it.md) + [short-clause](short-clause/it.md) di questa cartella (Servizi VTO);
   - se `ar_pd_enabled` → [full](../client-terms-ar-pd-meter-template/full/it.md) + [short-clause](../client-terms-ar-pd-meter-template/short-clause/it.md) della cartella AR PD Meter, **come documento separato**.
4. **Il documento generato deve essere rivisto dal consulente legale del Cliente prima della pubblicazione.** Il modello è fornito "così com'è", non costituisce parere legale e non crea alcun rapporto professionale; la clausola corrispondente va inserita anche nel contratto quadro Spaarkly–Cliente (item aperto).

## Sintassi

- **Variabili**: `{{nome_variabile}}` (stile mustache). Non usare `[[…]]`, riservato nelle bozze di questo repo ai placeholder redazionali.
- **Blocchi condizionali**: `{{#flag}}…{{/flag}}` (incluso se il flag è `true`), `{{^flag}}…{{/flag}}` (incluso se `false`).
- **Delimitatori di blocco**: `<!-- BLOCK nome [CORE|CLIENT] -->` … `<!-- /BLOCK nome -->`.
- I file del modello hanno front matter `published: false`: GitHub Pages/Liquid interpreterebbe `{{…}}` come proprie variabili e le renderebbe vuote. Il modello si consulta su GitHub o via raw URL; le istanze generate per i Clienti **non** vengono pubblicate in questo repo.

## Regole sui blocchi

- **[CORE]** — non modificabili dal Cliente: descrizione della tecnologia e dei flussi dati (incl. Gateway e Shoot & Share), natura dell'esperienza, privacy notice Spaarkly, proprietà intellettuale, clausola di terzo beneficiario, rapporto tra documenti. Nel template AR PD Meter sono [CORE] anche il consenso/gating, i disclaimer di misura e il requisito 18+. Ogni deviazione va approvata da Spaarkly.
- **[CLIENT]** — adattabili dal legale del Cliente: identità e ruolo commerciale del Cliente, responsabilità di vendita, minori (policy del sito), rinvii ai documenti del Cliente.
- **Regola prescrizioni**: se `prescription_sales_enabled = true`, il testo generato **deve** includere la verifica professionale (optician responsibility) e non può presentare la stima AR PD Meter come misura definitiva. Il blocco è già cablato nel modello: non rimuoverlo.

## Formule vincolate (identiche in tutti i documenti Spaarkly)

- Naming: sempre **"AR PD Meter"** (mai ARPDMeter, AR PD Metrics, ARShades PD Meter, "PD Meter" da solo nei testi legali).
- Identificabilità: "dati tecnici derivati **non utilizzati per identificare l'Utente e non idonei, di per sé, a identificarlo**" — mai forme assolute ("non riconducibili all'identità", "non biometrici").
- Flusso AR PD Meter: immagini mai trasmesse né conservate → soli dati tecnici derivati → backend Spaarkly nell'Unione Europea → cancellazione immediata dopo l'elaborazione; nelle esperienze Mirror, elaborazione sul backend locale del dispositivo.
- Disclaimers: non dispositivo medico; stima indicativa; non sostituisce la misurazione di un professionista qualificato della visione; età minima 18 anni.
- Shoot & Share: solo le foto finali selezionate dall'Utente, upload temporaneo, cancellazione entro 24 ore al più tardi.

## Versionamento e propagazione

- Il modello è versionato in [CHANGELOG.md](../CHANGELOG.md) (sezione "Client ARShades Integration Terms"). Le istanze generate riportano `template_version` e `generated_date` nell'intestazione.
- A ogni bump del modello che tocca blocchi [CORE]: rigenerare le istanze dei Clienti e notificare i Clienti; se cambia il trattamento dati AR PD Meter, serve il rinnovo del consenso espresso degli utenti (v. Termini Generali §15.3–15.4).
- Il flusso di consenso AR PD Meter (requisito §2.4 dei Termini AR PD Meter: versione/data + dati, finalità, conservazione, revoca) è attuato dal **modulo consenso ARShades**, mai da testi o task richiesti al Cliente; la sua descrizione resta leggibile nella sezione AR PD Meter del documento full.

## Lingua

Base autentica del modello: **italiano** (decisione 2026-07-07). Le versioni in altre lingue del modello non esistono ancora; la lingua delle istanze è scelta dal Cliente, fermo restando che i blocchi [CORE] tradotti devono restare fedeli alle formule vincolate.

## Stato

`status: template` nel manifest — **non è un documento legale pubblicato**. Prossimi passi: validazione del consulente sulla clausola di terzo beneficiario (art. 1411 c.c.), clausola nel contratto quadro Spaarkly–Cliente, pilot con un Cliente reale + revisione del consulente sull'istanza generata, poi generatore JSON → collezione `ARS_TermsAndCond` e aggancio del modulo consenso.
