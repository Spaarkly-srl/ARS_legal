---
published: false
---

# Client ARShades Integration Terms — Modello (v0.1.0)

Modello dei **termini di integrazione ARShades "a nome del Cliente"**: il documento che un Cliente (merchant, brand, ottico) può usare nei propri legal docs o nel proprio flow per disciplinare, verso i propri utenti, le funzionalità ARShades integrate nel suo sito/app/punto vendita.

**Non è un documento in vigore e non sono "i Termini Spaarkly a nome del cliente":** è un documento distinto, il cui oggetto è l'integrazione di ARShades nell'esperienza commerciale del Cliente. I Termini Spaarkly ([terms](../terms/it.md), [terms-ar-pd-meter](../terms-ar-pd-meter/it.md)) e la [Privacy Policy](../privacy-policy/it.md) restano i documenti canonici di Spaarkly e continuano ad applicarsi direttamente agli utenti finali.

## Principio dei ruoli (non negoziabile)

- Il **Cliente** offre l'esperienza commerciale sul proprio sito: vende/procura i prodotti, gestisce prezzi, disponibilità, prescrizioni e customer journey.
- **Spaarkly** fornisce la tecnologia ARShades e **resta titolare del trattamento** per i trattamenti descritti nella Privacy Policy ARShades. I ruoli privacy sono funzionali (EDPB Guidelines 07/2020): non si spostano per etichetta contrattuale. Il consenso espresso AR PD Meter (inclusa la written release BIPA/CUBI/RCW) è **sempre reso a Spaarkly**, mai al Cliente.

## Uso del modello

1. Compilare la [intake checklist](intake-checklist/it.md) con il Cliente.
2. Valorizzare le variabili secondo [schema.json](schema.json).
3. Generare i tre output: [full](full/it.md) (documento completo), [short-clause](short-clause/it.md) (clausola da incollare nei T&C del Cliente), [microcopy](microcopy/it.md) (testi per checkout/consenso).
4. **Il documento generato deve essere rivisto dal consulente legale del Cliente prima della pubblicazione.** Il modello è fornito "così com'è", non costituisce parere legale e non crea alcun rapporto professionale; la clausola corrispondente va inserita anche nel contratto quadro Spaarkly–Cliente (item aperto).

## Sintassi

- **Variabili**: `{{nome_variabile}}` (stile mustache). Non usare `[[…]]`, riservato nelle bozze di questo repo ai placeholder redazionali.
- **Blocchi condizionali**: `{{#flag}}…{{/flag}}` (incluso se il flag è `true`), `{{^flag}}…{{/flag}}` (incluso se `false`).
- **Delimitatori di blocco**: `<!-- BLOCK nome [CORE|CLIENT] -->` … `<!-- /BLOCK nome -->`.
- I file del modello hanno front matter `published: false`: GitHub Pages/Liquid interpreterebbe `{{…}}` come proprie variabili e le renderebbe vuote. Il modello si consulta su GitHub o via raw URL; le istanze generate per i Clienti **non** vengono pubblicate in questo repo.

## Regole sui blocchi

- **[CORE]** — non modificabili dal Cliente: descrizione della tecnologia e dei flussi dati, blocco AR PD Meter (consenso, disclaimers, 18+), Shoot & Share, privacy notice Spaarkly, proprietà intellettuale, rapporto tra documenti. Ogni deviazione va approvata da Spaarkly.
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
- Le variabili `ar_pd_terms_version` / `ar_pd_terms_date` vanno valorizzate dal [manifest.json](../manifest.json) al momento della generazione: la microcopy del consenso deve sempre mostrare versione e data vigenti (requisito §2.4 dei Termini AR PD Meter).

## Lingua

Base autentica del modello: **italiano** (decisione 2026-07-07). Le versioni in altre lingue del modello non esistono ancora; la lingua delle istanze è scelta dal Cliente, fermo restando che i blocchi [CORE] tradotti devono restare fedeli alle formule vincolate.

## Stato

`status: template` nel manifest — **non è un documento legale pubblicato**. Prossimi passi: clausola nel contratto quadro Spaarkly–Cliente, pilot con un Cliente reale + revisione del consulente sull'istanza generata, poi generatore JSON → documenti.
