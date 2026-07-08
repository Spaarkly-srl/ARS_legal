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
| B2 | Canale: e-commerce, showroom/negozio o entrambi | `mirror_enabled` (showroom → true) | Showroom/negozio implica esperienza Mirror |
| B3 | Le funzionalità ARShades sono anche in un'app mobile del Cliente? | `mobile_app_enabled` | |
| B4 | URL dei T&C del Cliente | `client_terms_url` | Dove verrà agganciato il documento |
| B5 | URL dell'informativa privacy del Cliente | `client_privacy_url` | |
| B6 | Email di assistenza clienti | `support_email` | |

## C. Soluzioni ARShades attive

| # | Domanda | Campo | Note |
|---|---|---|---|
| C1 | Virtual Try-On | `vto_enabled` | Di norma sì |
| C2 | VTO Explorer | `vto_explorer_enabled` | |
| C3 | Shoot & Share (foto da dispositivi in luoghi pubblici) | `shoot_share_enabled` | Richiede C2 = sì |
| C4 | Campaign Catalogue | `campaign_catalogue_enabled` | |
| C5 | AR PD Meter | `ar_pd_enabled` | Attiva il blocco consenso (microcopy §3) |

## D. Profilo di rischio

| # | Domanda | Campo | Note |
|---|---|---|---|
| D1 | Il Cliente vende lenti graduate / occhiali da vista? | `prescription_sales_enabled` | **Se sì:** il testo include obbligatoriamente la verifica professionale e la stima AR PD Meter non è mai presentata come misura definitiva (regola non rimovibile) |
| D2 | L'esperienza è accessibile anche a minori secondo la policy del sito? | `minors_enabled` | Se no: clausola "utenti maggiorenni". In ogni caso AR PD Meter resta 18+ |

## E. Meta (compilazione automatica, non chiedere al Cliente)

| Campo | Fonte |
|---|---|
| `template_version`, `generated_date` | Versione del modello e data di generazione |
| `ar_pd_terms_version`, `ar_pd_terms_date` | `manifest.json` → documento `terms-ar-pd-meter` (obbligatori se C5 = sì) |

## Regole di coerenza

- `shoot_share_enabled` richiede `vto_explorer_enabled = true`.
- `ar_pd_enabled = true` ⇒ includere blocco AR PD Meter (full), periodo AR PD Meter (short clause) e microcopy §3–§5.
- `prescription_sales_enabled = true` ⇒ blocco verifica professionale sempre incluso; vietato presentare la stima come misura definitiva.
- Output generato = bozza: **revisione del legale del Cliente obbligatoria prima della pubblicazione** (in particolare per requisiti locali del Paese A5, es. norme sulla dispensazione di dispositivi ottici o sulla vendita online di lenti graduate).
