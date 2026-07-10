---
published: false
---

# TÉRMINOS Y CONDICIONES DE USO — AR PD METER

*{{client_trade_name}} — {{website_url}}* </br> *Condiciones de {{client_legal_name}}, presentadas antes de la medición — generadas a partir del modelo Spaarkly «Client ARShades Integration Terms — AR PD Meter» v{{template_version}} de {{generated_date}}*

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
## Quién proporciona qué

**«{{client_trade_name}}»**, **«nosotros»** o **«nuestro»** hace referencia a {{client_legal_name}}, con domicilio en {{client_registered_office}} ({{client_country}}), {{client_vat}}, que gestiona {{website_url}} y ofrece la experiencia comercial.

**«Spaarkly»** hace referencia a Spaarkly s.r.l. (P. IVA IT02077620769), que desarrolla y suministra **AR PD Meter**, la funcionalidad ARShades descrita a continuación, y es **responsable del tratamiento** de los datos personales tratados por dicha funcionalidad. Spaarkly no es el vendedor de los productos presentados, no gestiona un marketplace ni es un óptico, un optometrista u otro profesional del cuidado de la visión.

Las presentes condiciones («Condiciones AR PD Meter») se presentan al Usuario, junto con la [Política de Privacidad ARShades](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/es/), antes del inicio de la medición. Al marcar la casilla de aceptación el Usuario las acepta y presta su consentimiento expreso al tratamiento descrito a continuación; a falta de aceptación la medición no se inicia. El Usuario puede revocar el consentimiento en cualquier momento interrumpiendo la medición o revocando el acceso a la cámara; la revocación no afecta a los tratamientos ya realizados.
<!-- /BLOCK ruoli -->

<!-- BLOCK cos-e [CORE] -->
## Qué es AR PD Meter

**AR PD Meter** proporciona una **estimación de la distancia pupilar (PD)** del Usuario utilizando la cámara del dispositivo y la detección de los puntos de referencia faciales (landmarks). Es una **estimación digital preliminar**, ofrecida como apoyo a la selección de las gafas durante la experiencia de compra: **no es un producto sanitario**, no tiene finalidades médicas, clínicas o diagnósticas y **no sustituye una medición realizada por un profesional cualificado de la visión** (como un óptico, un optometrista o un médico oftalmólogo). La precisión puede verse afectada por la iluminación, la calidad de la cámara, la distancia, la angulación, la posición del rostro y los movimientos.
<!-- /BLOCK cos-e -->

<!-- BLOCK consenso-dati [CORE] -->
## Consentimiento y tratamiento de los datos

El inicio de la medición requiere el **consentimiento expreso del Usuario, prestado a Spaarkly** como responsable del tratamiento, mediante la casilla de aceptación presentada antes de la medición. El flujo de consentimiento indica la versión y la fecha de las presentes Condiciones AR PD Meter en vigor y resume los datos tratados, la finalidad, la conservación y las modalidades de revocación.

El consentimiento se gestiona como **gating local in-experience**: la medición se inicia solo después del consentimiento explícito y la revocación está siempre disponible, con interrupción inmediata del tratamiento en curso. Dado que Spaarkly no identifica al Usuario final, **no se conserva ninguna prueba del consentimiento asociable al Usuario**: lo evidencia el propio inicio de la medición, supeditado al consentimiento.

Las imágenes de la cámara se procesan en el dispositivo del Usuario y **no se transmiten a Spaarkly ni son conservadas por Spaarkly**. Únicamente datos técnicos derivados (coordenadas de los puntos de referencia faciales, datos de orientación del rostro, información sobre el dispositivo) — no utilizados para identificar al Usuario y no aptos, por sí solos, para identificarlo — se transmiten cifrados al backend de Spaarkly en la **Unión Europea**, se utilizan exclusivamente para calcular y devolver la medición y se **eliminan de forma permanente inmediatamente después del procesamiento**.{{#mirror_enabled}} Cuando la medición se realiza en un dispositivo **Mirror** en nuestros puntos de venta o showrooms, el procesamiento tiene lugar en el backend local del dispositivo, sin transmisión alguna a servidores en la nube.{{/mirror_enabled}}

Cuando así lo exijan las leyes aplicables en materia de privacidad biométrica, la aceptación afirmativa del Usuario constituye el consentimiento/la autorización escrita al tratamiento descrito, prestado antes de cualquier captación. Los detalles completos están en la [Política de Privacidad ARShades](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/es/), de la que Spaarkly es responsable.
<!-- /BLOCK consenso-dati -->

<!-- BLOCK eta [CORE] -->
## Edad

AR PD Meter está destinado a usuarios que tengan **al menos 18 años**. El Usuario menor de 18 años solo puede utilizarlo con el consentimiento y bajo la supervisión de un progenitor o de un tutor legal.
<!-- /BLOCK eta -->

<!-- BLOCK uso-vendita [CLIENT] -->
## Uso en nuestro proceso de venta

{{#prescription_sales_enabled}}La estimación de AR PD Meter es para nosotros únicamente un **dato preliminar de apoyo** y **nunca se utiliza como medida definitiva** para el suministro de lentes graduadas: antes de la fabricación de gafas graduadas, la distancia pupilar y los demás parámetros necesarios son verificados o confirmados por un profesional cualificado de la visión, conforme a nuestro proceso de venta y a la normativa aplicable. La responsabilidad de dicha verificación es nuestra, no de Spaarkly.{{/prescription_sales_enabled}}{{^prescription_sales_enabled}}No vendemos lentes graduadas a través de {{website_url}}: la estimación de AR PD Meter se utiliza exclusivamente como apoyo a la selección de monturas y gafas no graduadas.{{/prescription_sales_enabled}}
<!-- /BLOCK uso-vendita -->

<!-- BLOCK privacy [CORE] -->
## Privacidad

Para el tratamiento realizado por AR PD Meter — descrito anteriormente — el **responsable del tratamiento es Spaarkly s.r.l.**: se aplica la [Política de Privacidad ARShades](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/es/) (contacto: privacy@spaarkly.com), presentada junto con las presentes Condiciones AR PD Meter. Nosotros no accedemos a los datos tratados por AR PD Meter ni al tratamiento correspondiente: recibimos de Spaarkly exclusivamente datos agregados y anonimizados; por ello Spaarkly sigue siendo responsable del tratamiento.

Para los tratamientos que realizamos nosotros en calidad de responsables — cuentas, pedidos, asistencia y cualquier otro tratamiento vinculado a {{website_url}} — se aplica nuestra [política de privacidad]({{client_privacy_url}}).
<!-- /BLOCK privacy -->

<!-- BLOCK ip [CORE] -->
## Propiedad intelectual

AR PD Meter — software, algoritmos e interfaces — y los correspondientes derechos de propiedad intelectual son y siguen siendo de **Spaarkly o de sus licenciantes**. Al Usuario no se le transfiere ningún derecho de propiedad; quedan prohibidos la ingeniería inversa (salvo en lo permitido por normas imperativas) y cualquier uso no autorizado de la funcionalidad.
<!-- /BLOCK ip -->

<!-- BLOCK terzo-beneficiario [CORE] -->
## Spaarkly como tercero beneficiario

Las previsiones de las presentes Condiciones AR PD Meter relativas a la tecnología, a la naturaleza de la estimación, al tratamiento de los datos, a la propiedad intelectual y a las exclusiones y limitaciones vinculadas a ellas se pactan, en interés del Cliente, también a favor de Spaarkly, en virtud del artículo 1411 del Código Civil italiano, y Spaarkly puede hacerlas valer directamente frente al Usuario. La presente cláusula no perjudica los derechos reconocidos al Usuario por normas imperativas.
<!-- /BLOCK terzo-beneficiario -->

<!-- BLOCK rapporto-documenti [CORE] -->
## Relación con los demás documentos

Las presentes Condiciones AR PD Meter se aplican exclusivamente al uso de la funcionalidad AR PD Meter. Las compras y cualquier otra relación comercial con nosotros siguen rigiéndose por nuestros [Términos y Condiciones]({{client_terms_url}}), que regulan también la ley aplicable y el fuero competente. Para el tratamiento de datos personales del que Spaarkly es responsable se aplica la [Política de Privacidad ARShades](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/es/). Nada en las presentes Condiciones AR PD Meter excluye, limita o perjudica los derechos reconocidos al Usuario por normas imperativas, incluidos los derechos de los consumidores.
<!-- /BLOCK rapporto-documenti -->

<!-- BLOCK contatti [CLIENT] -->
## Contacto

Para consultas sobre la experiencia de compra: **{{support_email}}**.

Para cuestiones relativas a AR PD Meter: **legal@spaarkly.com**; para la privacidad ARShades: **privacy@spaarkly.com**.
<!-- /BLOCK contatti -->

---

Al marcar la casilla de aceptación o al utilizar AR PD Meter, el Usuario declara haber leído y comprendido las presentes Condiciones AR PD Meter, las acepta y presta su consentimiento expreso al tratamiento descrito.
