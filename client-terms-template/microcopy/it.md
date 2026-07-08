---
published: false
---

# MICROCOPY — CHECKOUT E FLUSSI DI CONSENSO

*Testi brevi per le UI del Cliente (widget, checkout, flow di consenso). Generati dal modello Spaarkly «Client ARShades Integration Terms» v{{template_version}} del {{generated_date}}.*

<!-- ============================================================
  MODELLO SPAARKLY — NON IN VIGORE. I testi del blocco consenso
  AR PD Meter attuano il requisito contrattuale §2.4 dei Termini
  AR PD Meter (versione/data dei termini + dati, finalità,
  conservazione, revoca): sono [CORE] e non possono essere
  accorciati oltre la "variante compatta" indicata.
  Le variabili {{ar_pd_terms_version}} / {{ar_pd_terms_date}} vanno
  valorizzate dal manifest.json al momento della generazione.
  ============================================================ -->

## 1. Attribuzione widget / footer esperienza [CORE]

> Prova virtuale offerta dalla tecnologia **ARShades** di Spaarkly s.r.l. — [Termini](https://spaarkly-srl.github.io/ARS_legal/terms/it/) · [Privacy](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/it/)

## 2. Pre-prompt fotocamera (prima della richiesta del browser) [CORE]

> Per la prova virtuale serve l'accesso alla fotocamera. Le immagini sono elaborate **in tempo reale sul tuo dispositivo** per posizionare gli occhiali virtuali: non vengono memorizzate né trasmesse ai server di Spaarkly. Dettagli nell'[Informativa Privacy ARShades](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/it/).

{{#ar_pd_enabled}}
## 3. Consenso espresso AR PD Meter — casella di accettazione [CORE — attua il §2.4]

**Titolo del passaggio:** Misura la tua distanza pupillare (PD)

**Testo informativo sopra la casella:**

> **AR PD Meter — Termini e Condizioni v{{ar_pd_terms_version}} del {{ar_pd_terms_date}}** ([testo integrale](https://spaarkly-srl.github.io/ARS_legal/terms-ar-pd-meter/it/))
>
> - **Dati trattati:** le immagini della fotocamera sono elaborate **sul tuo dispositivo** e **non vengono trasmesse né conservate**; al backend di Spaarkly nell'Unione Europea arrivano, cifrati, solo dati tecnici derivati (coordinate dei landmark facciali, orientamento del volto, informazioni sul dispositivo), non utilizzati per identificarti e non idonei, di per sé, a identificarti.{{#mirror_enabled}} Su dispositivi Mirror in negozio l'elaborazione avviene sul backend locale del dispositivo, senza trasmissione a server cloud.{{/mirror_enabled}}
> - **Finalità:** calcolare e restituirti la stima della distanza pupillare, a supporto della selezione degli occhiali.
> - **Conservazione:** i dati sono **cancellati in modo permanente subito dopo l'elaborazione**.
> - **Revoca:** puoi revocare il consenso in qualsiasi momento interrompendo la misurazione o revocando l'accesso alla fotocamera; la revoca non pregiudica i trattamenti già effettuati.
> - Titolare del trattamento: **Spaarkly s.r.l.** ([Informativa Privacy](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/it/) · privacy@spaarkly.com). Servizio riservato a chi ha **almeno 18 anni**.

**Casella (non preselezionata):**

> ☐ Ho letto i Termini AR PD Meter e presto il mio **consenso espresso** al trattamento descritto sopra.

**Pulsanti:** `Avvia la misurazione` / `Non ora`

*Variante compatta (spazi ridotti; il riepilogo per punti deve restare raggiungibile con un tap/click, es. in un expander "Come trattiamo i tuoi dati"):*

> ☐ Ho letto i [Termini AR PD Meter v{{ar_pd_terms_version}} del {{ar_pd_terms_date}}](https://spaarkly-srl.github.io/ARS_legal/terms-ar-pd-meter/it/) e presto il mio consenso espresso al trattamento descritto in «Come trattiamo i tuoi dati».

## 4. Disclaimer sotto il risultato della misurazione [CORE + regola prescrizioni]

> La tua PD stimata: **{{result_placeholder}}**. È una **stima digitale preliminare**, non una misurazione medica: l'accuratezza può variare in base a illuminazione, fotocamera, distanza e posizione del volto. Non sostituisce la misurazione di un professionista qualificato della visione.{{#prescription_sales_enabled}} Per gli occhiali da vista la useremo solo come dato di partenza: la tua PD sarà **verificata da un professionista qualificato** prima della realizzazione delle lenti.{{/prescription_sales_enabled}}

## 5. Nota età (accanto all'avvio di AR PD Meter) [CORE]

> AR PD Meter è riservato a chi ha **almeno 18 anni** (i minori solo con il consenso e la supervisione di un genitore o tutore).
{{/ar_pd_enabled}}

{{#shoot_share_enabled}}
## 6. Avviso «Shoot & Share» (dispositivi in luoghi aperti al pubblico) [CORE]

> Scegli le foto che vuoi ricevere o condividere: **solo quelle selezionate** vengono caricate temporaneamente sui server di Spaarkly per essere rese disponibili a te e vengono **cancellate al più tardi entro 24 ore**. Le altre immagini della sessione restano sul dispositivo e non vengono caricate.
{{/shoot_share_enabled}}

## 7. Rinvio nei T&C / footer del sito [CLIENT]

> L'esperienza di prova virtuale su {{website_url}} è fornita dalla tecnologia ARShades di Spaarkly s.r.l. — v. la sezione «Funzionalità ARShades» dei nostri [Termini e Condizioni]({{client_terms_url}}) e la nostra [informativa privacy]({{client_privacy_url}}).
