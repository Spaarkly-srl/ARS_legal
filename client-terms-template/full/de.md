---
published: false
---

# NUTZUNGSBEDINGUNGEN — ARSHADES-FUNKTIONEN

*{{client_trade_name}} — {{website_url}}* </br> *Bedingungen von {{client_legal_name}}, die beim Start des Erlebnisses angezeigt werden — erstellt aus der Spaarkly-Vorlage «Client ARShades Integration Terms — Servizi VTO» v{{template_version}} vom {{generated_date}}*

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
## Wer was bereitstellt

**«{{client_trade_name}}»**, **„wir"** oder **„unser"** bezeichnet {{client_legal_name}} mit Sitz in {{client_registered_office}} ({{client_country}}), {{client_vat}}, die {{website_url}} betreibt und das kommerzielle Erlebnis anbietet: Kataloge und Kollektionen, Preise, Verfügbarkeit, Bestellungen, Kundenbetreuung{{#prescription_sales_enabled}}, Verwaltung der Verordnungen{{/prescription_sales_enabled}} und den gesamten Kaufprozess.

**„Spaarkly"** bezeichnet Spaarkly s.r.l. (P. IVA IT02077620769), die die in unser Erlebnis integrierten Augmented-Reality-Softwarelösungen **ARShades** entwickelt und bereitstellt. Spaarkly ist nicht der Verkäufer der dargestellten Produkte, betreibt keinen Marktplatz und ist weder Optiker noch Optometrist oder sonstiger Anbieter augenoptischer Leistungen.

Diese Bedingungen („Bedingungen") werden dem Nutzer zusammen mit der [ARShades-Datenschutzerklärung](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/de/) vor dem Start des Erlebnisses angezeigt und regeln dessen Nutzung. Durch Klicken auf „Akzeptieren" (oder durch eine gleichwertige Handlung) akzeptiert der Nutzer sie; ohne Annahme wird das Erlebnis nicht gestartet. Während des Erlebnisses kann der Nutzer die Dokumente jederzeit erneut lesen und seine Einwilligung in den Einstellungen widerrufen.
<!-- /BLOCK ruoli -->

<!-- BLOCK funzionalita [CORE] -->
## Die verfügbaren ARShades-Funktionen

{{#vto_enabled}}- **Virtual Try-On (VTO)** — die virtuelle Anprobe der Brille in Augmented Reality über die Kamera des Geräts.{{/vto_enabled}}
{{#viewer_3d_enabled}}- **3D Viewer** — die dreidimensionale Darstellung, die eine 360°-Erkundung der Brillenmodelle (Drehen und Zoomen) und, sofern das Gerät dies unterstützt, deren Darstellung in Augmented Reality ermöglicht.{{/viewer_3d_enabled}}
{{#vto_explorer_enabled}}- **VTO Explorer** — personalisierte Vorschauen mehrerer Modelle auf Grundlage einer begrenzten Anzahl von Bildern, die während der Sitzung aufgenommen und lokal auf dem Gerät verarbeitet werden.{{/vto_explorer_enabled}}
{{#mirror_enabled}}- **Mirror** — das virtuelle Anprobeerlebnis auf einem dedizierten Gerät in unseren Verkaufsstellen oder Showrooms; die Verfügbarkeit und die materiellen Nutzungsbedingungen des Geräts liegen in unserer Verantwortung.{{/mirror_enabled}}
{{#gateway_enabled}}- **Gateway** — die ARShades-Plattform, die virtuelle Anprobeerlebnisse und einen einheitlichen Zugang zu den ARShades-Erlebnissen und den Marken-Stores bietet; sie kann optional, vorbehaltlich der Einwilligung, die Geolokalisierung nutzen.{{/gateway_enabled}}
{{#campaign_catalogue_enabled}}- **Campaign Catalogue** — der kuratierte digitale Katalog, mit dem wir ausgewählte Kollektionen oder Kampagnen präsentieren; Produkte, Preise und kommerzielle Informationen werden von uns ausgewählt und verwaltet.{{/campaign_catalogue_enabled}}

{{#mobile_app_enabled}}Die ARShades-Funktionen sind auch innerhalb unserer mobilen Anwendung verfügbar; der Download und die Nutzung der App unterliegen auch den Bedingungen des jeweiligen App Stores (Apple App Store oder Google Play).{{/mobile_app_enabled}}

Mindestanforderungen für die kamerabasierten Funktionen: eine stabile Internetverbindung, ein mit einer Kamera ausgestattetes Gerät und die Erlaubnis zum Zugriff auf die Kamera für die Dauer des Erlebnisses. Die Kamerabilder werden in Echtzeit auf dem Gerät des Nutzers verarbeitet, um die virtuelle Brille zu positionieren: Sie werden weder gespeichert noch an die Server von Spaarkly übertragen.
<!-- /BLOCK funzionalita -->

<!-- BLOCK natura [CORE] -->
## Art des virtuellen Erlebnisses

Die virtuelle Anprobe und die Darstellung der Modelle sind eine **visuelle Hilfe**: aufgrund technischer Grenzen kann die Wiedergabe (Aussehen, Farben, Passform, Größe) vom physischen Produkt abweichen und variiert je nach Gerät, Kamera, Beleuchtung und Umgebung. Die Kaufentscheidungen verbleiben beim Nutzer; das virtuelle Erlebnis stellt keine Gewähr für die Eignung, Verfügbarkeit oder das Aussehen des Produkts dar. Sofern nicht anders angegeben, werden die ARShades-Funktionen den Nutzern unentgeltlich angeboten.
<!-- /BLOCK natura -->

{{#shoot_share_enabled}}
<!-- BLOCK shoot-share [CORE] -->
## Fotos und „Shoot & Share"

Die gegebenenfalls während einer VTO-Explorer-Sitzung aufgenommenen Bilder werden lokal auf dem für das Erlebnis verwendeten Gerät verarbeitet und **nicht automatisch** auf die Server von Spaarkly hochgeladen. Findet das Erlebnis auf einem Gerät statt, das in einer Verkaufsstelle, einem Showroom, an einem Veranstaltungsort oder an einem anderen öffentlich zugänglichen Ort aufgestellt ist, und entscheidet sich der Nutzer, die endgültigen Fotos zu erhalten, herunterzuladen oder zu teilen („Shoot & Share" oder gleichwertige Funktionen), so werden **ausschließlich die vom Nutzer ausgewählten endgültigen Fotos** vorübergehend auf die Server von Spaarkly hochgeladen, allein zu dem Zweck, sie dem Nutzer zur Verfügung zu stellen, und spätestens innerhalb von 24 Stunden gelöscht (früher, wenn der Nutzer sie löscht).
<!-- /BLOCK shoot-share -->
{{/shoot_share_enabled}}

<!-- BLOCK privacy [CORE] -->
## Datenschutz

Für die von den ARShades-Funktionen durchgeführten Verarbeitungen personenbezogener Daten — einschließlich der Gesichts-Landmarks, die **in Echtzeit und lokal auf dem Gerät** allein zu dem Zweck verarbeitet werden, die virtuelle Brille zu positionieren, ohne Speicherung oder Übertragung — ist **Spaarkly s.r.l. der Verantwortliche**: Es gilt die [ARShades-Datenschutzerklärung](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/de/) (Kontakt: privacy@spaarkly.com), die zusammen mit diesen Bedingungen angezeigt wird. Wir haben weder Zugriff auf die von den ARShades-Funktionen verarbeiteten personenbezogenen Daten noch auf deren Verarbeitung: Wir erhalten von Spaarkly ausschließlich aggregierte und anonymisierte Daten; deshalb bleibt Spaarkly der Verantwortliche für die ARShades-Verarbeitungen.

Für die Verarbeitungen, die wir als Verantwortliche durchführen — Konten, Bestellungen, Zahlungen, Kundenbetreuung, Marketing und jede andere mit {{website_url}} verbundene Verarbeitung — gilt unsere [Datenschutzerklärung]({{client_privacy_url}}).
<!-- /BLOCK privacy -->

<!-- BLOCK venditore [CLIENT] -->
## Unsere Verantwortung als Verkäufer

Wir — und nicht Spaarkly — sind für die auf {{website_url}} dargestellten und verkauften Produkte verantwortlich: Preise, Verfügbarkeit, Produktbeschreibungen und -angaben, Konformität, Lieferung, gesetzliche Gewährleistung, Rückgaben und Kundenbetreuung, gemäß unseren [Allgemeinen Geschäftsbedingungen]({{client_terms_url}}).{{#prescription_sales_enabled}} Die Abgabe von Korrektionsgläsern erfolgt unter unserer Verantwortung und unter Einhaltung der anwendbaren Vorschriften.{{/prescription_sales_enabled}} Etwaige Käufe oder sonstige Geschäfte, die der Nutzer mit uns abschließt, unterliegen ausschließlich unseren Bedingungen.
<!-- /BLOCK venditore -->

<!-- BLOCK ip [CORE] -->
## Geistiges Eigentum

Die ARShades-Lösungen — Software, Algorithmen und Schnittstellen — sowie die zugehörigen Rechte des geistigen Eigentums stehen und verbleiben im Eigentum von **Spaarkly oder seinen Lizenzgebern**. Die 3D-Modelle und die dargestellten Inhalte können uns, Spaarkly oder den jeweiligen Lizenzgebern gehören und werden ausschließlich zu Darstellungszwecken bereitgestellt. Untersagt sind insbesondere das Kopieren, Vervielfältigen, Extrahieren oder Sammeln der 3D-Modelle und Inhalte mittels Scraping, das Dekompilieren oder Reverse Engineering der Software (soweit nicht durch zwingende Vorschriften gestattet) sowie jede unbefugte kommerzielle Nutzung der ARShades-Lösungen.
<!-- /BLOCK ip -->

<!-- BLOCK minori [CLIENT] -->
## Minderjährige

{{#minors_enabled}}Die ARShades-Funktionen richten sich an ein allgemeines Publikum: Nutzer, die das Alter noch nicht erreicht haben, in dem sie in Bezug auf Dienste der Informationsgesellschaft in ihrem Wohnsitzland wirksam einwilligen können (in Italien 14 Jahre), dürfen sie nur mit der Einwilligung oder Genehmigung eines Elternteils oder gesetzlichen Vormunds nutzen, soweit dies nach dem anwendbaren Recht erforderlich ist.{{/minors_enabled}}{{^minors_enabled}}Das Kauferlebnis auf {{website_url}} richtet sich an volljährige Nutzer.{{/minors_enabled}}
<!-- /BLOCK minori -->

<!-- BLOCK terzo-beneficiario [CORE] -->
## Spaarkly als begünstigter Dritter

Die Bestimmungen dieser Bedingungen betreffend die ARShades-Technologie, die Art des virtuellen Erlebnisses, das geistige Eigentum sowie die damit verbundenen Ausschlüsse und Beschränkungen werden, im Interesse des Kunden, auch zugunsten von Spaarkly vereinbart, gemäß Artikel 1411 des italienischen Zivilgesetzbuchs, und Spaarkly kann sie unmittelbar gegenüber dem Nutzer geltend machen. Diese Klausel lässt die dem Nutzer durch zwingende Vorschriften zuerkannten Rechte unberührt.
<!-- /BLOCK terzo-beneficiario -->

<!-- BLOCK rapporto-documenti [CORE] -->
## Verhältnis zu den übrigen Dokumenten

Diese Bedingungen gelten für die Nutzung der ARShades-Funktionen innerhalb unseres Erlebnisses. Käufe und jede sonstige Geschäftsbeziehung mit uns unterliegen weiterhin unseren [Allgemeinen Geschäftsbedingungen]({{client_terms_url}}), die auch das anwendbare Recht und den Gerichtsstand regeln. Für die Verarbeitungen personenbezogener Daten, für die Spaarkly der Verantwortliche ist, gilt die [ARShades-Datenschutzerklärung](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/de/). Nichts in diesen Bedingungen schließt die dem Nutzer durch zwingende Vorschriften zuerkannten Rechte, einschließlich der Verbraucherrechte, aus, beschränkt oder beeinträchtigt sie.
<!-- /BLOCK rapporto-documenti -->

<!-- BLOCK contatti [CLIENT] -->
## Kontakt

Bei Fragen zum Kauferlebnis: **{{support_email}}**.

Bei Fragen zu den ARShades-Funktionen: **legal@spaarkly.com**; zum Datenschutz von ARShades: **privacy@spaarkly.com**.
<!-- /BLOCK contatti -->

---

Durch Klicken auf „Akzeptieren" oder durch Nutzung der ARShades-Funktionen, nachdem er die Möglichkeit hatte, sie zur Kenntnis zu nehmen, erklärt der Nutzer, diese Bedingungen gelesen und verstanden zu haben und sie zu akzeptieren.
