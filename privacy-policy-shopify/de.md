# Datenschutzerklärung für ARShades VTO for Shopify

Zuletzt aktualisiert: 7. Juli 2026

Diese Datenschutzerklärung beschreibt, wie die **Spaarkly s.r.l.** („Spaarkly", „ARShades", „wir", „uns" oder „unser") personenbezogene Daten und sonstige Informationen im Zusammenhang mit der App **ARShades VTO for Shopify** (die „Shopify-App" oder die „App") verarbeitet.

Diese Erklärung bezieht sich ausschließlich auf die Shopify-App und ist auf die im Zusammenhang mit Shopify verarbeiteten Daten beschränkt (Daten zu Händler, Shop, Produkten, Konfiguration und Attribution). Die Verarbeitung durch die ARShades-Endnutzerdienste — etwa Virtual Try-On, 3D/AR Viewer und AR PD Meter —, die über die App gestartet werden können, ist nicht Gegenstand dieser Erklärung und unterliegt der **ARShades Core-Datenschutzerklärung** (Version 5.5), abrufbar unter [https://github.com/Spaarkly-srl/ARS_legal](https://github.com/Spaarkly-srl/ARS_legal/blob/main/privacy-policy/de.md) und den Käuferinnen und Käufern innerhalb der ARShades-Erlebnisse angezeigt.

## 1. Verantwortlicher

Die Spaarkly s.r.l. ist für die über die Shopify-App verarbeiteten personenbezogenen Daten eigenständig Verantwortlicher.

**Verantwortlicher:** Spaarkly s.r.l.  
**Eingetragene Anschrift:** Via della Tecnica n. 18, 85100 Potenza, Italy  
**Datenschutzkontakt:** privacy@spaarkly.com

## 2. Funktionsweise der Shopify-App

Die Shopify-App verbindet den Shopify-Store eines Händlers mit der ARShades-Plattform. Sie ermöglicht es Händlern:

* ein ARShades-Lizenz-Token mit einem Shopify-Store zu verbinden;
* einen ARShades-Katalog anzulegen oder zu verbinden;
* Shopify-Produkte und -Varianten anhand von SKU, EAN oder ähnlichen Produktkennungen mit ARShades-3D/VTO-Assets abzugleichen;
* Theme-Blocks für Virtual Try-On, 3D/AR Viewer und AR PD Meter hinzuzufügen;
* Farben, Button-Stile, Modal-Einstellungen und bestimmte Branding-Assets anzupassen;
* Shopify-Web-Pixel-Ereignisse für die VTO/3D-Attribution und die Conversion-Analyse zu nutzen.

Die Installation der App in Shopify ist kostenlos. Der zugrunde liegende ARShades-Dienst kann ein separates, außerhalb von Shopify erworbenes ARShades-Abonnement erfordern.

## 3. Kategorien der von uns verarbeiteten Daten

### 3.1 Händler- und Shopify-Admin-Daten

Wenn ein Händler die App installiert oder nutzt, können wir folgende Daten verarbeiten:

* Shopify-Shop-Domain und Store-URL;
* Shopify-OAuth-Sitzungsdaten;
* Access-Token und autorisierte Scopes;
* Shopify-Admin-Benutzerkennungen sowie, soweit von Shopify bereitgestellt, Vorname, Nachname, E-Mail-Adresse, Spracheinstellung, Mitarbeiterstatus (Collaborator), Kontoinhaberstatus und Status der E-Mail-Verifizierung;
* Status von Installation, Konfiguration und Nutzung der App.

Diese Daten dienen dazu, den Händler zu authentifizieren, die eingebettete App zu betreiben, die App-Sitzung aufrechtzuerhalten sowie Support und Sicherheit zu gewährleisten.

### 3.2 ARShades-Lizenz-, Katalog- und Konfigurationsdaten

Wir verarbeiten die zur Verbindung des Shopify-Stores mit ARShades erforderlichen Informationen, darunter:

* ARShades-Lizenz-Token oder Abonnementkennung;
* ARShades-Katalog-ID, Katalogname und Katalogstatus;
* 3D-Viewer-ID sowie ARShades-Dienstfunktionen wie die Verfügbarkeit von VTO oder AR PD Meter;
* App-Konfiguration, gespeichert als Shopify-Metafields, darunter `licenseId`, `catalogueId`, `viewerId`, `webDomain`, `studioDomain`, `has_vto` und `has_arpd`;
* Stileinstellungen wie Farben, Modal-Einstellungen und Button-Einstellungen;
* vom Händler hochgeladene Branding-Assets, etwa ein Logo, das in ARShades-Berechtigungs- oder -Richtlinienbildschirmen verwendet wird.

### 3.3 Shopify-Produkt- und -Variantendaten

Um Produkte mit ARShades-Assets abzugleichen und VTO/3D-Funktionen nur dort anzuzeigen, wo sie verfügbar sind, kann die App folgende Daten lesen und verarbeiten:

* Shopify-Produkt-ID, -Titel, -Handle und URL des Featured Image;
* Shopify-Varianten-ID;
* SKU, Barcode, EAN oder UPC;
* vorhandene ARShades-Metafield-Werte;
* ARShades-Katalogprodukt- und -variantenkennungen.

Die App kann technische ARShades-Metafields in Shopify-Varianten schreiben, darunter `catalogueVariantId` und `catalogueProductId`. Diese Metafields werden von den Storefront-Theme-Blocks verwendet, um zu bestimmen, ob für ein Produkt oder eine Variante ARShades VTO oder der 3D/AR Viewer gestartet werden kann.

### 3.4 Von der App verarbeitete Storefront-Daten

Wenn eine Käuferin oder ein Käufer VTO oder den 3D/AR Viewer in der Storefront des Händlers nutzt, kann die App die folgenden technischen, nicht profilbezogenen Daten verarbeiten:

* Produkt- und Variantenkennungen;
* ARShades-Katalogkennungen;
* Kennungen der ausgewählten oder zuletzt anprobierten Variante;
* Geräte-, Browser-, Sprach- und Sitzungsinformationen;
* technische Ereignisse, die anzeigen, dass eine VTO- oder 3D-Sitzung geöffnet wurde.

Diese Daten dienen dazu, das korrekte Erlebnis in der Storefront anzuzeigen und die in Abschnitt 3.6 beschriebene Attributionsanalyse zu ermöglichen.

### 3.5 ARShades-Endnutzererlebnisse (VTO, 3D/AR Viewer, AR PD Meter)

Die kamerabasierte Verarbeitung, die innerhalb der aus der Storefront gestarteten ARShades-Erlebnisse stattfindet — einschließlich des Virtual-Try-On-Renderings und der Pupillendistanzberechnung durch den AR PD Meter —, wird von den ARShades-Diensten durchgeführt, nicht von der Shopify-App, und unterliegt der ARShades Core-Datenschutzerklärung.

Zusammenfassend und wie in jener Erklärung dargestellt: Kamerabilder und Videostreams werden nicht gespeichert; es werden keine Gesichtstemplates oder biometrischen Identifikatoren erstellt; und beim AR PD Meter können von der Kamera abgeleitete technische Daten, die die Käuferin oder den Käufer nicht identifizieren, vorübergehend an das in der Europäischen Union befindliche ARShades-Backend übermittelt werden, wobei sie ausschließlich zur Rückgabe des Messergebnisses verwendet und nach der Verarbeitung gelöscht werden. Die Shopify-App selbst greift nicht auf Kameradaten zu, speichert sie nicht und empfängt sie nicht.

### 3.6 Shopify-Web-Pixel und Conversion-Analyse

Die App verwendet ein Shopify-Web-Pixel, um die VTO/3D-Attribution und die Conversion-Performance zu messen. Das Pixel kann folgende Daten verarbeiten:

* Shop-Domain;
* Ereignistyp und Zeitstempel;
* eine pseudonyme VTO/3D-Sitzungs-ID;
* Produkt- und Variantenkennungen;
* ARShades-Katalogprodukt- und -variantenkennungen;
* Warenkorbkennungen für die Add-to-Cart-Attribution;
* Checkout-/Bestellkennungen, Gesamtpreis, Währung und Metadaten der Positionen (Line Items) für die Kaufattribution;
* die Angabe, ob der Kauf nach einer VTO/3D-Sitzung oder ohne eine VTO/3D-Sitzung erfolgt ist, zu Vergleichszwecken.

Das Pixel ist so gestaltet, dass es keine direkten Käuferprofildaten wie Name, E-Mail-Adresse, Telefonnummer oder Lieferanschrift an das ARShades-Analyse-Backend übermittelt.

Das Storefront-Pixel kann den lokalen Speicher (Local Storage) des Browsers nutzen, um eine aktive VTO/3D-Sitzung für die Attribution zu speichern. Diese lokalen Sitzungsdaten verfallen nach 7 Tagen oder werden nach einem erfassten Kauf gelöscht.

Das Pixel wird vom Pixel-Manager von Shopify nur dann geladen, wenn die Einwilligung der Besucherin oder des Besuchers den von der App deklarierten Einwilligungskategorien (etwa `analytics`) entspricht, im Einklang mit der Customer Privacy API von Shopify und der Einwilligungskonfiguration des Händlers. Wir beachten diese Einwilligungssignale und verarbeiten keine Pixel-Ereignisse, die ohne die erforderliche Einwilligung erhoben wurden.

## 4. Zwecke und Rechtsgrundlagen

Wir verarbeiten die oben beschriebenen Daten zu folgenden Zwecken:

* Installation, Authentifizierung und Betrieb der Shopify-App;
* Verbindung des Händler-Stores mit einer ARShades-Lizenz und einem ARShades-Katalog;
* Synchronisierung von Produkt- und Variantenmetadaten mit ARShades;
* Bereitstellung von VTO, 3D/AR Viewer und AR PD Meter in der Storefront;
* Pflege der Shopify-Metafields und der App-Konfiguration;
* Messung der VTO/3D-Attribution, von Add-to-Cart-Ereignissen und der Kauf-Conversion-Analyse;
* Absicherung der App, Missbrauchsprävention und Behebung technischer Probleme;
* Einhaltung der Anforderungen von Shopify hinsichtlich App-Prüfung, Datenschutz und Compliance;
* Beantwortung von Datenschutzanfragen und Erfüllung rechtlicher Verpflichtungen.

Je nach Kontext und anwendbarem Recht können die Rechtsgrundlagen die Erfüllung eines Vertrags, berechtigte Interessen, die Erfüllung rechtlicher Verpflichtungen sowie die Einwilligung umfassen, soweit erforderlich, einschließlich der Anforderungen an die Einwilligung in den Kamerazugriff oder in die Analyse.

## 5. Speicherdauer

Wir speichern Daten nur so lange, wie dies für die in dieser Erklärung beschriebenen Zwecke erforderlich ist.

* Die aktive App-Konfiguration, Shopify-Metafields, Produkt-/Variantenzuordnungen und OAuth-Sitzungen werden gespeichert, solange die App installiert bleibt und die Daten für den Betrieb des Dienstes erforderlich sind.
* Store-spezifische App-Daten werden gelöscht oder anonymisiert, wenn Shopify einen gültigen `shop/redact`-Compliance-Webhook sendet, es sei denn, eine Speicherung ist gesetzlich vorgeschrieben oder zu berechtigten Sicherheitszwecken erforderlich.
* Pixel-Analysedaten, Conversion-Ereignisse, technische Protokolle, Sitzungsdaten und ähnliche historische Daten werden bis zu 14 Monate gespeichert und anschließend aggregiert oder anonymisiert.
* Vom Händler hochgeladene Branding-Assets und Stileinstellungen werden gespeichert, solange sie für den aktiven Dienst erforderlich sind, und nach Löschung, Deinstallation oder Ablauf der geltenden Speicherfrist entfernt oder anonymisiert.
* Innerhalb der ARShades-Endnutzererlebnisse verarbeitete Daten (einschließlich AR PD Meter) werden wie in der ARShades Core-Datenschutzerklärung beschrieben gespeichert.

## 6. Shopify-Datenschutz- und -Compliance-Webhooks

Die App implementiert Shopify-Datenschutz- und -Compliance-Webhook-Endpunkte für:

* `customers/data_request`;
* `customers/redact`;
* `shop/redact`.

Webhook-Anfragen werden anhand der HMAC-Signatur von Shopify verifiziert; Anfragen mit ungültiger Signatur werden abgewiesen. Wir schließen Datenauskunfts- und Löschvorgänge innerhalb von 30 Tagen nach Eingang des Webhooks ab.

Die App-Datenbank speichert keine direkten Endkundenprofildaten wie Käufername, E-Mail-Adresse, Telefonnummer oder Lieferanschrift. Bei kundenbezogenen Anfragen verifizieren wir den Shopify-Webhook und antworten entsprechend den in der App vorhandenen Datenbeständen.

`shop/redact` wird von Shopify 48 Stunden nach der Deinstallation der App gesendet. Nach Eingang löschen wir die gespeicherten App-Daten des Shops, einschließlich Shopify-Sitzungen, synchronisierter Variantenzuordnungen und Shop-Pixel-Einstellungen, vorbehaltlich rechtlicher oder sicherheitsbezogener Aufbewahrungspflichten.

## 7. Weitergabe und Unterauftragsverarbeiter

Wir geben Daten nur insoweit weiter, wie dies zum Betrieb, zur Absicherung und zum Support der App und der ARShades-Dienste erforderlich ist.

Zu den bestätigten Dienstleistern und der für die Shopify-App und die zugehörigen ARShades-Dienste genutzten Infrastruktur gehören:

* Shopify, für die App-Installation, OAuth, Admin API, Theme-Extensions, Customer Events und Web-Pixel-Infrastruktur;
* Vercel, für das Hosting der Shopify-App;
* Neon/Vercel Postgres, für das Hosting der App-Datenbank;
* Google Cloud/Firebase, für ARShades-Backend-Funktionen und die Analyseverarbeitung, wobei die Daten in Regionen der Europäischen Union verarbeitet werden;
* Cloudways CDN, für die Bereitstellung der ARShades-Storefront-Bundle-Assets.

Diese Anbieter verarbeiten Daten nach ihren eigenen Bedingungen und geltenden Datenverarbeitungsverpflichtungen. Wir verkaufen oder teilen (im Sinne des California Consumer Privacy Act) keine personenbezogenen Daten von Käuferinnen und Käufern. Wir verwenden Shopify-App-Daten nicht für sachfremde Werbung, Gesichtserkennung, biometrische Identifizierung oder das Training von KI-Modellen, und wir führen keine automatisierte Entscheidungsfindung durch, die rechtliche oder in ähnlicher Weise erhebliche Auswirkungen entfaltet.

Ein die Verarbeitung durch die App abdeckender Auftragsverarbeitungsvertrag (DPA) ist für Händler auf Anfrage unter privacy@spaarkly.com erhältlich.

## 8. Internationale Datenübermittlungen

Die Shopify-App sowie die ARShades-Analyse- und -Verarbeitungsdienste sind so konfiguriert, dass sie die relevanten Daten, soweit anwendbar, in der Europäischen Union verarbeiten und speichern.

Sofern ein Dienstleister personenbezogene Daten außerhalb des Europäischen Wirtschaftsraums (EWR) verarbeitet, setzen wir geeignete, nach anwendbarem Recht erforderliche Garantien ein, etwa Standardvertragsklauseln (SCC) oder gleichwertige Übermittlungsmechanismen.

## 9. Sicherheit

Wir setzen technische und organisatorische Maßnahmen ein, die dem Schutz der von der App verarbeiteten Daten dienen, darunter:

* HTTPS/TLS für Daten während der Übertragung;
* Verschlüsselung im Ruhezustand für die App-Datenbank;
* Zugriffskontrollen und Authentifizierung;
* Shopify-OAuth- und Webhook-Verifizierung;
* Datenbankzugriffskontrollen;
* Minimierung der angeforderten Shopify-Scopes;
* betriebliche Protokollierung und Überwachung zu Sicherheits- und Fehlerbehebungszwecken.

Keine Übertragungs- oder Speichermethode ist vollständig sicher, doch wir sind bestrebt, Schutzmaßnahmen aufrechtzuerhalten, die der Art der Daten und den damit verbundenen Risiken angemessen sind.

### Reaktion auf Sicherheitsvorfälle

Betrifft ein Sicherheitsvorfall von der App verarbeitete Daten, bewerten wir den Vorfall nach Art. 33 DSGVO, mindern ihn so schnell wie möglich und benachrichtigen die zuständige Aufsichtsbehörde, sofern erforderlich, innerhalb von 72 Stunden. Da uns die Kontaktdaten der Händler vorliegen, benachrichtigen wir betroffene Händler unmittelbar und ohne unangemessene Verzögerung und kooperieren, soweit anwendbar, mit den Vorfallsprozessen von Shopify.

## 10. Kameraberechtigungen der Käuferinnen und Käufer

Der Kamerazugriff wird ausschließlich innerhalb der ARShades-Erlebnisse (VTO, AR PD Meter) durch den Browser oder das Betriebssystem des Geräts der Käuferin oder des Käufers angefordert. Käuferinnen und Käufer können den Kamerazugriff über die Browser- oder Geräteeinstellungen verweigern oder widerrufen; wird er verweigert, funktionieren diese Erlebnisse möglicherweise nicht. Die Shopify-App selbst greift nicht auf die Kamera zu.

Wie Kameradaten innerhalb der ARShades-Erlebnisse verarbeitet werden, ist in der ARShades Core-Datenschutzerklärung beschrieben.

## 11. Datenschutz für Kinder

Die App ist für die Nutzung durch Shopify-Händler und deren Storefront-Käuferinnen und -Käufer bestimmt. Wir erheben und verarbeiten die personenbezogenen Daten keines Nutzers — und damit auch keines Kindes — wissentlich ohne eine gültige Rechtsgrundlage sowie, soweit es sich um Kinder unterhalb des jeweils geltenden Alters für die digitale Einwilligung handelt, ohne die Einwilligung eines Elternteils oder Erziehungsberechtigten. Aufgrund der Konzeption von ARShades legen wir keine Konten an, verlangen weder Namen noch Kontaktdaten und erzeugen keine dauerhaften Kennungen, und wir halten keine Daten vor, die sich einem identifizierten oder identifizierbaren Kind zuordnen lassen.

Ist ein Elternteil oder Erziehungsberechtigter der Auffassung, dass ein Kind den Dienst ohne seine Einwilligung genutzt hat, kann er uns unter privacy@spaarkly.com kontaktieren, um die Löschung der Daten zu verlangen, wobei die verwendete IP-Adresse und nach Möglichkeit das ungefähre Datum und die ungefähre Uhrzeit der Sitzung anzugeben sind. Sofern uns diese Angaben ermöglichen, die betreffenden Daten aufzufinden, ergreifen wir unverzüglich Maßnahmen zu deren Löschung; andernfalls weisen wir darauf hin, dass die technischen Daten ohnehin den in dieser Erklärung beschriebenen Fristen für Aufbewahrung und automatische Löschung unterliegen.

## 12. Ihre Rechte

Je nach Ihrem Standort können Ihnen Rechte auf Auskunft, Berichtigung, Löschung, Einschränkung, Widerspruch sowie auf Erhalt einer Kopie Ihrer personenbezogenen Daten zustehen.

Händler können uns unter privacy@spaarkly.com kontaktieren. Käuferinnen und Käufer können sich auch an den Händler wenden, dessen Store sie besucht haben, oder sich direkt an Spaarkly wenden, soweit Spaarkly als Verantwortlicher für die ARShades-Verarbeitung auftritt.

Wir benötigen möglicherweise Informationen wie die Shop-Domain, das ungefähre Datum bzw. die Uhrzeit, Ereigniskennungen, Geräte-/Sitzungsdetails oder sonstige Angaben, um die relevanten Datensätze auffinden zu können.

Sie haben zudem das Recht, Beschwerde bei einer Aufsichtsbehörde einzulegen, etwa beim italienischen Garante per la Protezione dei Dati Personali ([www.garanteprivacy.it](https://www.garanteprivacy.it)) oder bei der zuständigen Behörde in Ihrem Wohnsitzland.

## 13. Änderungen dieser Erklärung

Wir können diese Datenschutzerklärung aktualisieren, um Änderungen der Shopify-App, der ARShades-Dienste, rechtlicher Anforderungen oder betrieblicher Praktiken Rechnung zu tragen. Wenn wir die Erklärung aktualisieren, überarbeiten wir das Datum unter „Zuletzt aktualisiert".

## 14. Kontakt

Bei Datenschutzfragen oder -anfragen wenden Sie sich an:

**Spaarkly s.r.l.**  
Via della Tecnica n. 18  
85100 Potenza, Italy  
Email: privacy@spaarkly.com
