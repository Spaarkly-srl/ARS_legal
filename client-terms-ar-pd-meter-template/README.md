---
published: false
---

# Client ARShades Integration Terms — AR PD Meter (v0.2.1)

Template white-label **AR PD Meter stand-alone**, parte del sistema *Client ARShades Integration Terms*. È il documento mostrato e **accettato nel modulo consenso ARShades a nome del Cliente, prima della misurazione** AR PD Meter.

**Documento autosufficiente e indipendente.** Non rinvia né incorpora i Termini dei Servizi VTO ([`client-terms-template/`](../client-terms-template/)), **anche quando il Cliente usa entrambe le soluzioni** (decisione 2026-07-10): AR PD Meter, quando è stand-alone, non deve trascinarsi la casistica VTO. Rispecchia la separazione canonica tra [terms/](../terms/it.md) e [terms-ar-pd-meter/](../terms-ar-pd-meter/it.md).

## Output

- [full/it.md](full/it.md) — il testo accettato nel modulo consenso prima della misurazione.
- [short-clause/it.md](short-clause/it.md) — articolo AR PD Meter da incollare nel corpo dei T&C del Cliente long-term.

## Tooling condiviso

Schema dei parametri e intake-checklist sono **in comune** col template Servizi VTO:

- Variabili: [`../client-terms-template/schema.json`](../client-terms-template/schema.json) — questo template usa `ar_pd_enabled` (gate di generazione), l'identità del Cliente, `prescription_sales_enabled`, `mirror_enabled`, `support_email`, `client_terms_url`, `client_privacy_url`.
- Raccolta dati: [`../client-terms-template/intake-checklist/it.md`](../client-terms-template/intake-checklist/it.md).
- Regole, blocchi [CORE]/[CLIENT], formule vincolate, versionamento e stato: [`../client-terms-template/README.md`](../client-terms-template/README.md).

## Punti fermi (identici ai documenti canonici)

- Consenso espresso **sempre reso a Spaarkly** (titolare del trattamento), inclusa la written release BIPA/CUBI/RCW; requisito §2.4 attuato dal modulo consenso (versione/data + dati, finalità, conservazione, revoca). **Gating locale in-experience**: misurazione avviata solo dopo consenso esplicito, revoca sempre disponibile con interruzione immediata, **nessuna prova del consenso persistente associabile all'Utente** (Spaarkly non identifica l'utente finale). Il Cliente non accede ai dati AR PD Meter: riceve solo dati aggregati e anonimizzati.
- Flusso dati: immagini mai trasmesse né conservate → soli dati tecnici derivati (non idonei, di per sé, a identificare l'Utente) → backend Spaarkly nell'Unione Europea → cancellazione immediata; su Mirror elaborazione locale sul dispositivo.
- Disclaimers: non dispositivo medico; stima digitale preliminare; non sostituisce la misurazione di un professionista qualificato della visione; età minima 18 anni.
- Regola prescrizioni: se `prescription_sales_enabled`, verifica professionale obbligatoria e stima mai presentata come misura definitiva.
