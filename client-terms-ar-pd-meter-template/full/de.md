---
published: false
---

# NUTZUNGSBEDINGUNGEN — AR PD METER

*{{client_trade_name}} — {{website_url}}* </br> *Bedingungen von {{client_legal_name}}, die vor der Messung angezeigt werden — erstellt aus der Spaarkly-Vorlage «Client ARShades Integration Terms — AR PD Meter» v{{template_version}} vom {{generated_date}}*

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
## Wer was bereitstellt

**«{{client_trade_name}}»**, **„wir"** oder **„unser"** bezeichnet {{client_legal_name}} mit Sitz in {{client_registered_office}} ({{client_country}}), {{client_vat}}, die {{website_url}} betreibt und das kommerzielle Erlebnis anbietet.

**„Spaarkly"** bezeichnet Spaarkly s.r.l. (P. IVA IT02077620769), die **AR PD Meter**, die nachstehend beschriebene ARShades-Funktion, entwickelt und bereitstellt und **Verantwortlicher** für die von dieser Funktion verarbeiteten personenbezogenen Daten ist. Spaarkly ist nicht der Verkäufer der dargestellten Produkte, betreibt keinen Marktplatz und ist weder Optiker noch Optometrist oder sonstiger Anbieter augenoptischer Leistungen.

Diese Bedingungen („AR PD Meter-Bedingungen") werden dem Nutzer zusammen mit der [ARShades-Datenschutzerklärung](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/de/) vor dem Start der Messung angezeigt. Durch Ankreuzen des Annahmekästchens akzeptiert der Nutzer sie und erteilt seine ausdrückliche Einwilligung in die nachstehend beschriebene Verarbeitung; ohne Annahme wird die Messung nicht gestartet. Der Nutzer kann die Einwilligung jederzeit widerrufen, indem er die Messung abbricht oder den Zugriff auf die Kamera widerruft; der Widerruf berührt nicht die bereits durchgeführten Verarbeitungen.
<!-- /BLOCK ruoli -->

<!-- BLOCK cos-e [CORE] -->
## Was ist AR PD Meter

**AR PD Meter** liefert eine **Schätzung des Pupillenabstands (PD)** des Nutzers unter Verwendung der Kamera des Geräts und der Erkennung der Gesichts-Landmarks. Es handelt sich um eine **vorläufige digitale Schätzung**, die zur Unterstützung der Brillenauswahl während des Kauferlebnisses angeboten wird: Es ist **kein Medizinprodukt**, verfolgt keine medizinischen, klinischen oder diagnostischen Zwecke und **ersetzt keine von einer qualifizierten Fachkraft für Augenoptik durchgeführte Messung** (wie einem Optiker, einem Optometristen oder einem Augenarzt). Die Genauigkeit kann durch Beleuchtung, Kameraqualität, Abstand, Winkel, Position des Gesichts und Bewegungen beeinflusst werden.
<!-- /BLOCK cos-e -->

<!-- BLOCK consenso-dati [CORE] -->
## Einwilligung und Datenverarbeitung

Der Start der Messung erfordert die **ausdrückliche Einwilligung des Nutzers, die gegenüber Spaarkly** als Verantwortlichem erteilt wird, über das vor der Messung angezeigte Annahmekästchen. Der Einwilligungsablauf gibt die Version und das Datum der geltenden AR PD Meter-Bedingungen an und fasst die verarbeiteten Daten, den Zweck, die Aufbewahrung und die Modalitäten des Widerrufs zusammen.

Die Einwilligung wird als **lokales In-Experience-Gating** verwaltet: Die Messung startet erst nach der ausdrücklichen Einwilligung, und der Widerruf ist jederzeit möglich, mit sofortiger Unterbrechung der laufenden Verarbeitung. Da Spaarkly den Endnutzer nicht identifiziert, **wird kein dem Nutzer zuordenbarer Nachweis der Einwilligung aufbewahrt**: Beleg dafür ist der Start der Messung selbst, der von der Einwilligung abhängt.

Die Kamerabilder werden auf dem Gerät des Nutzers verarbeitet und **weder an Spaarkly übertragen noch von Spaarkly aufbewahrt**. Nur abgeleitete technische Daten (Koordinaten der Gesichts-Landmarks, Daten zur Ausrichtung des Gesichts, Geräteinformationen) — nicht zur Identifizierung des Nutzers verwendet und für sich genommen nicht geeignet, ihn zu identifizieren — werden verschlüsselt an das Backend von Spaarkly in der **Europäischen Union** übertragen, ausschließlich zur Berechnung und Rückgabe der Messung verwendet und **unmittelbar nach der Verarbeitung dauerhaft gelöscht**.{{#mirror_enabled}} Erfolgt die Messung auf einem **Mirror**-Gerät in unseren Verkaufsstellen oder Showrooms, so findet die Verarbeitung auf dem lokalen Backend des Geräts statt, ohne jegliche Übertragung an Cloud-Server.{{/mirror_enabled}}

Soweit die anwendbaren Gesetze über den Schutz biometrischer Daten dies verlangen, stellt die bejahende Annahme durch den Nutzer die schriftliche Einwilligung/Freigabe in die beschriebene Verarbeitung dar, die vor jeder Erfassung erteilt wird. Die vollständigen Einzelheiten finden sich in der [ARShades-Datenschutzerklärung](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/de/), für die Spaarkly der Verantwortliche ist.
<!-- /BLOCK consenso-dati -->

<!-- BLOCK eta [CORE] -->
## Alter

AR PD Meter richtet sich an Nutzer, die **mindestens 18 Jahre** alt sind. Ein Nutzer unter 18 Jahren darf es nur mit der Einwilligung und unter der Aufsicht eines Elternteils oder gesetzlichen Vormunds nutzen.
<!-- /BLOCK eta -->

<!-- BLOCK uso-vendita [CLIENT] -->
## Verwendung in unserem Verkaufsprozess

{{#prescription_sales_enabled}}Die AR PD Meter-Schätzung ist für uns nur ein **vorläufiges Hilfsdatum** und **wird niemals als endgültiges Maß** für die Anfertigung von Korrektionsgläsern verwendet: Vor der Herstellung einer Korrektionsbrille werden der Pupillenabstand und die übrigen erforderlichen Parameter von einer qualifizierten Fachkraft für Augenoptik gemäß unserem Verkaufsprozess und den anwendbaren Vorschriften überprüft oder bestätigt. Die Verantwortung für diese Überprüfung liegt bei uns, nicht bei Spaarkly.{{/prescription_sales_enabled}}{{^prescription_sales_enabled}}Wir verkaufen keine Korrektionsgläser über {{website_url}}: Die AR PD Meter-Schätzung wird ausschließlich zur Unterstützung der Auswahl von Fassungen und Brillen ohne Korrektion verwendet.{{/prescription_sales_enabled}}
<!-- /BLOCK uso-vendita -->

<!-- BLOCK privacy [CORE] -->
## Datenschutz

Für die von AR PD Meter durchgeführte Verarbeitung — wie oben beschrieben — ist **Spaarkly s.r.l. der Verantwortliche**: Es gilt die [ARShades-Datenschutzerklärung](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/de/) (Kontakt: privacy@spaarkly.com), die zusammen mit diesen AR PD Meter-Bedingungen angezeigt wird. Wir haben weder Zugriff auf die von AR PD Meter verarbeiteten Daten noch auf deren Verarbeitung: Wir erhalten von Spaarkly ausschließlich aggregierte und anonymisierte Daten; deshalb bleibt Spaarkly der Verantwortliche.

Für die Verarbeitungen, die wir als Verantwortliche durchführen — Konten, Bestellungen, Kundenbetreuung und jede andere mit {{website_url}} verbundene Verarbeitung — gilt unsere [Datenschutzerklärung]({{client_privacy_url}}).
<!-- /BLOCK privacy -->

<!-- BLOCK ip [CORE] -->
## Geistiges Eigentum

AR PD Meter — Software, Algorithmen und Schnittstellen — sowie die zugehörigen Rechte des geistigen Eigentums stehen und verbleiben im Eigentum von **Spaarkly oder seinen Lizenzgebern**. Dem Nutzer wird kein Eigentumsrecht übertragen; untersagt sind das Reverse Engineering (soweit nicht durch zwingende Vorschriften gestattet) und jede unbefugte Nutzung der Funktion.
<!-- /BLOCK ip -->

<!-- BLOCK terzo-beneficiario [CORE] -->
## Spaarkly als begünstigter Dritter

Die Bestimmungen dieser AR PD Meter-Bedingungen betreffend die Technologie, die Art der Schätzung, die Datenverarbeitung, das geistige Eigentum sowie die damit verbundenen Ausschlüsse und Beschränkungen werden, im Interesse des Kunden, auch zugunsten von Spaarkly vereinbart, gemäß Artikel 1411 des italienischen Zivilgesetzbuchs, und Spaarkly kann sie unmittelbar gegenüber dem Nutzer geltend machen. Diese Klausel lässt die dem Nutzer durch zwingende Vorschriften zuerkannten Rechte unberührt.
<!-- /BLOCK terzo-beneficiario -->

<!-- BLOCK rapporto-documenti [CORE] -->
## Verhältnis zu den übrigen Dokumenten

Diese AR PD Meter-Bedingungen gelten ausschließlich für die Nutzung der AR PD Meter-Funktion. Käufe und jede sonstige Geschäftsbeziehung mit uns unterliegen weiterhin unseren [Allgemeinen Geschäftsbedingungen]({{client_terms_url}}), die auch das anwendbare Recht und den Gerichtsstand regeln. Für die Verarbeitung personenbezogener Daten, für die Spaarkly der Verantwortliche ist, gilt die [ARShades-Datenschutzerklärung](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/de/). Nichts in diesen AR PD Meter-Bedingungen schließt die dem Nutzer durch zwingende Vorschriften zuerkannten Rechte, einschließlich der Verbraucherrechte, aus, beschränkt oder beeinträchtigt sie.
<!-- /BLOCK rapporto-documenti -->

<!-- BLOCK contatti [CLIENT] -->
## Kontakt

Bei Fragen zum Kauferlebnis: **{{support_email}}**.

Bei Fragen zu AR PD Meter: **legal@spaarkly.com**; zum Datenschutz von ARShades: **privacy@spaarkly.com**.
<!-- /BLOCK contatti -->

---

Durch Ankreuzen des Annahmekästchens oder durch Nutzung von AR PD Meter erklärt der Nutzer, diese AR PD Meter-Bedingungen gelesen und verstanden zu haben, akzeptiert sie und erteilt seine ausdrückliche Einwilligung in die beschriebene Verarbeitung.
