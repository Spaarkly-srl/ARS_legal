---
published: false
---

# CLIENT INTAKE CHECKLIST — GENERAZIONE TERMINI CLIENTE

*Da compilare con il Cliente (o dai dati già presenti in Studio / configurazione plugin) prima di generare i termini. Ogni risposta valorizza un campo di [schema.json](../schema.json).*

## A. Identità del Cliente

| # | Domanda | Campo | Note |
|---|---|---|---|
| A1 | Ragione sociale completa | `client_legal_name` | Come da registro imprese |
| A2 | Nome commerciale / brand mostrato agli utenti | `client_trade_name` | Se coincide, ripetere A1 |
| A3 | Sede legale (indirizzo completo) | `client_registered_office` | |
| A4 | P. IVA / n. registro imprese | `client_vat` | Con prefisso Paese (es. IT…) |
| A5 | Paese principale di operatività | `client_country` | Determina anche eventuali verifiche locali (v. nota in fondo) |
| A6 | Tipo di cliente | — (solo intake) | brand / retailer / ottico-optometrista / altro. Se ottico: quasi sempre D1 = sì |

## B. Canali e contatti

| # | Domanda | Campo | Note |
|---|---|---|---|
| B1 | URL del sito con le funzionalità ARShades | `website_url` | |
| B2 | Canale: e-commerce, showroom/negozio o entrambi | `mirror_enabled` (showroom → true) | Showroom/negozio implica esperienza Mirror: UI e consenso li colloca Spaarkly nel dispositivo (locale); al Cliente restano le sole condizioni materiali |
| B3 | Le funzionalità ARShades sono anche in un'app mobile del Cliente? | `mobile_app_enabled` | App branded per il Cliente: si clonano disclaimer e flussi delle app ARShades. App ARShades nostre: fuori scope del modello (valgono i Termini Spaarkly canonici) |
| B4 | URL dei T&C del Cliente | `client_terms_url` | Dove verrà agganciato il documento |
| B5 | URL dell'informativa privacy del Cliente | `client_privacy_url` | |
| B6 | Email di assistenza clienti | `support_email` | |

## C. Soluzioni ARShades attive

| # | Domanda | Campo | Note |
|---|---|---|---|
| C1 | Virtual Try-On | `vto_enabled` | Di norma sì — template Servizi VTO |
| C2 | 3D Viewer | `viewer_3d_enabled` | Visualizzazione 3D 360° + AR — template Servizi VTO |
| C3 | VTO Explorer | `vto_explorer_enabled` | template Servizi VTO |
| C4 | Shoot & Share (foto da dispositivi in luoghi pubblici) | `shoot_share_enabled` | Richiede C3 = sì |
| C5 | Campaign Catalogue | `campaign_catalogue_enabled` | template Servizi VTO |
| C6 | AR PD Meter | `ar_pd_enabled` | **Genera il documento separato e indipendente** dal template AR PD Meter (non compare nel documento Servizi VTO) |

## D. Profilo di rischio

| # | Domanda | Campo | Note |
|---|---|---|---|
| D1 | Il Cliente vende lenti graduate / occhiali da vista? | `prescription_sales_enabled` | **Se sì:** il testo include obbligatoriamente la verifica professionale e la stima AR PD Meter non è mai presentata come misura definitiva (regola non rimovibile) |
| D2 | L'esperienza è accessibile anche a minori secondo la policy del sito? | `minors_enabled` | Se no: clausola "utenti maggiorenni". In ogni caso AR PD Meter resta 18+ |

## E. Meta (compilazione automatica, non chiedere al Cliente)

| Campo | Fonte |
|---|---|
| `template_version`, `generated_date` | Versione del modello e data di generazione |

## Output generati

- **Se almeno una soluzione VTO è attiva** (VTO, 3D Viewer, VTO Explorer, Mirror, Campaign Catalogue) → si genera il documento **Servizi VTO** (`client-terms-template/`: full + short-clause).
- **Se `ar_pd_enabled = true`** → si genera **in aggiunta** il documento **AR PD Meter** (`client-terms-ar-pd-meter-template/`: full + short-clause), **separato e indipendente**: nessun rinvio incrociato tra i due, anche quando il Cliente ha entrambe le soluzioni.

## Regole di coerenza

- `shoot_share_enabled` richiede `vto_explorer_enabled = true`.
- `prescription_sales_enabled = true` ⇒ nel documento generato pertinente, blocco verifica professionale sempre incluso; vietato presentare la stima AR PD Meter come misura definitiva.
- Il consenso espresso AR PD Meter è raccolto dal modulo consenso ARShades ed è sempre reso a Spaarkly (titolare del trattamento).
- Output generato = bozza: **revisione del legale del Cliente obbligatoria prima della pubblicazione** (in particolare per requisiti locali del Paese A5, es. norme sulla dispensazione di dispositivi ottici o sulla vendita online di lenti graduate).
