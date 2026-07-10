---
published: false
---

# TÉRMINOS Y CONDICIONES DE USO — FUNCIONALIDADES ARSHADES

*{{client_trade_name}} — {{website_url}}* </br> *Condiciones de {{client_legal_name}}, presentadas al inicio de la experiencia — generadas a partir del modelo Spaarkly «Client ARShades Integration Terms — Servizi VTO» v{{template_version}} de {{generated_date}}*

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
## Quién proporciona qué

**«{{client_trade_name}}»**, **«nosotros»** o **«nuestro»** hace referencia a {{client_legal_name}}, con domicilio en {{client_registered_office}} ({{client_country}}), {{client_vat}}, que gestiona {{website_url}} y ofrece la experiencia comercial: catálogos y colecciones, precios, disponibilidad, pedidos, asistencia{{#prescription_sales_enabled}}, gestión de las prescripciones{{/prescription_sales_enabled}} y todo el proceso de compra.

**«Spaarkly»** hace referencia a Spaarkly s.r.l. (P. IVA IT02077620769), que desarrolla y suministra las soluciones de software de realidad aumentada **ARShades** integradas en nuestra experiencia. Spaarkly no es el vendedor de los productos presentados, no gestiona un marketplace ni es un óptico, un optometrista u otro profesional del cuidado de la visión.

Las presentes condiciones («Condiciones») se presentan al Usuario, junto con la [Política de Privacidad ARShades](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/es/), antes del inicio de la experiencia y regulan su uso. Al hacer clic en «Aceptar» (o realizar una acción equivalente) el Usuario las acepta; a falta de aceptación la experiencia no se inicia. Durante la experiencia el Usuario puede en cualquier momento releer los documentos y revocar su consentimiento desde los ajustes.
<!-- /BLOCK ruoli -->

<!-- BLOCK funzionalita [CORE] -->
## Las funcionalidades ARShades disponibles

{{#vto_enabled}}- **Virtual Try-On (VTO)** — la prueba virtual de las gafas en realidad aumentada mediante la cámara del dispositivo.{{/vto_enabled}}
{{#viewer_3d_enabled}}- **3D Viewer** — la visualización tridimensional que permite la exploración en 360° de los modelos de gafas (rotación y zoom) y, cuando el dispositivo lo admita, su visualización en realidad aumentada.{{/viewer_3d_enabled}}
{{#vto_explorer_enabled}}- **VTO Explorer** — vistas previas personalizadas de varios modelos a partir de un número limitado de imágenes captadas durante la sesión y procesadas localmente en el dispositivo.{{/vto_explorer_enabled}}
{{#mirror_enabled}}- **Mirror** — la experiencia de prueba virtual en un dispositivo dedicado en nuestros puntos de venta o showrooms; la disponibilidad y las condiciones materiales de uso del dispositivo son responsabilidad nuestra.{{/mirror_enabled}}
{{#gateway_enabled}}- **Gateway** — la plataforma ARShades que ofrece experiencias de prueba virtual y un acceso unificado a las experiencias ARShades y a las tiendas de las marcas; puede utilizar opcionalmente la geolocalización, previo consentimiento.{{/gateway_enabled}}
{{#campaign_catalogue_enabled}}- **Campaign Catalogue** — el catálogo digital curado con el que presentamos colecciones o campañas seleccionadas; los productos, los precios y la información comercial son elegidos y gestionados por nosotros.{{/campaign_catalogue_enabled}}

{{#mobile_app_enabled}}Las funcionalidades ARShades están disponibles también dentro de nuestra aplicación móvil; la descarga y el uso de la app están sujetos también a los términos de la app store aplicable (Apple App Store o Google Play).{{/mobile_app_enabled}}

Requisitos mínimos para las funcionalidades basadas en la cámara: conexión a Internet estable, dispositivo dotado de cámara y autorización de acceso a la cámara durante toda la experiencia. Las imágenes de la cámara se procesan en tiempo real en el dispositivo del Usuario para posicionar las gafas virtuales: no se almacenan ni se transmiten a los servidores de Spaarkly.
<!-- /BLOCK funzionalita -->

<!-- BLOCK natura [CORE] -->
## Naturaleza de la experiencia virtual

La prueba virtual y la visualización de los modelos son una **ayuda visual**: por limitaciones técnicas la representación (aspecto, colores, ajuste, dimensiones) puede diferir del producto físico y varía en función del dispositivo, la cámara, la iluminación y el entorno. Las decisiones de compra corresponden al Usuario; la experiencia virtual no constituye garantía de idoneidad, disponibilidad o aspecto del producto. Salvo indicación en contrario, las funcionalidades ARShades se ofrecen a los Usuarios de forma gratuita.
<!-- /BLOCK natura -->

{{#shoot_share_enabled}}
<!-- BLOCK shoot-share [CORE] -->
## Fotos y «Shoot & Share»

Las imágenes que eventualmente se capten durante una sesión de VTO Explorer se procesan localmente en el dispositivo empleado para la experiencia y **no se cargan automáticamente** en los servidores de Spaarkly. Si la experiencia tiene lugar en un dispositivo instalado en un punto de venta, un showroom, la sede de un evento u otro lugar abierto al público y el Usuario decide obtener, descargar o compartir las fotos finales («Shoot & Share» o funciones equivalentes), **únicamente las fotos finales seleccionadas por el Usuario** se cargan temporalmente en los servidores de Spaarkly, con la única finalidad de ponerlas a disposición del Usuario, y se eliminan a más tardar en un plazo de 24 horas (antes, si el Usuario las elimina).
<!-- /BLOCK shoot-share -->
{{/shoot_share_enabled}}

<!-- BLOCK privacy [CORE] -->
## Privacidad

Para los tratamientos de datos personales realizados por las funcionalidades ARShades — incluidos los puntos de referencia faciales (landmarks) procesados **en tiempo real y localmente en el dispositivo** con la única finalidad de posicionar las gafas virtuales, sin almacenamiento ni transmisión — el **responsable del tratamiento es Spaarkly s.r.l.**: se aplica la [Política de Privacidad ARShades](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/es/) (contacto: privacy@spaarkly.com), presentada junto con las presentes Condiciones. Nosotros no accedemos a los datos personales tratados por las funcionalidades ARShades ni al tratamiento correspondiente: recibimos de Spaarkly exclusivamente datos agregados y anonimizados; por ello Spaarkly sigue siendo responsable del tratamiento para los tratamientos ARShades.

Para los tratamientos que realizamos nosotros en calidad de responsables — cuentas, pedidos, pagos, asistencia, marketing y cualquier otro tratamiento vinculado a {{website_url}} — se aplica nuestra [política de privacidad]({{client_privacy_url}}).
<!-- /BLOCK privacy -->

<!-- BLOCK venditore [CLIENT] -->
## Nuestras responsabilidades como vendedor

Somos nosotros — y no Spaarkly — los responsables de los productos presentados y vendidos en {{website_url}}: precios, disponibilidad, descripciones y declaraciones sobre los productos, conformidad, entrega, garantía legal, devoluciones y asistencia, conforme a nuestros [Términos y Condiciones]({{client_terms_url}}).{{#prescription_sales_enabled}} La dispensación de lentes graduadas se realiza bajo nuestra responsabilidad, respetando la normativa aplicable.{{/prescription_sales_enabled}} Las compras u otras operaciones que el Usuario concluya con nosotros se rigen exclusivamente por nuestros términos.
<!-- /BLOCK venditore -->

<!-- BLOCK ip [CORE] -->
## Propiedad intelectual

Las soluciones ARShades — software, algoritmos e interfaces — y los correspondientes derechos de propiedad intelectual son y siguen siendo de **Spaarkly o de sus licenciantes**. Los modelos 3D y los contenidos visualizados pueden ser nuestros, de Spaarkly o de los respectivos licenciantes y se facilitan únicamente con fines de visualización. En particular, queda prohibido copiar, reproducir, extraer o recopilar mediante scraping los modelos 3D y los contenidos, descompilar o someter a ingeniería inversa el software (salvo en lo permitido por normas imperativas) y cualquier uso comercial no autorizado de las soluciones ARShades.
<!-- /BLOCK ip -->

<!-- BLOCK minori [CLIENT] -->
## Menores

{{#minors_enabled}}Las funcionalidades ARShades están destinadas a un público general: los Usuarios de edad inferior a aquella en la que pueden prestar válidamente el consentimiento en relación con los servicios de la sociedad de la información en su país de residencia (en Italia, 14 años) solo pueden utilizarlas con el consentimiento o la autorización de un progenitor o de un tutor legal, cuando así lo exija la legislación aplicable.{{/minors_enabled}}{{^minors_enabled}}La experiencia de compra en {{website_url}} está destinada a usuarios mayores de edad.{{/minors_enabled}}
<!-- /BLOCK minori -->

<!-- BLOCK terzo-beneficiario [CORE] -->
## Spaarkly como tercero beneficiario

Las previsiones de las presentes Condiciones relativas a la tecnología ARShades, a la naturaleza de la experiencia virtual, a la propiedad intelectual y a las exclusiones y limitaciones vinculadas a ellas se pactan, en interés del Cliente, también a favor de Spaarkly, en virtud del artículo 1411 del Código Civil italiano, y Spaarkly puede hacerlas valer directamente frente al Usuario. La presente cláusula no perjudica los derechos reconocidos al Usuario por normas imperativas.
<!-- /BLOCK terzo-beneficiario -->

<!-- BLOCK rapporto-documenti [CORE] -->
## Relación con los demás documentos

Las presentes Condiciones se aplican al uso de las funcionalidades ARShades dentro de nuestra experiencia. Las compras y cualquier otra relación comercial con nosotros siguen rigiéndose por nuestros [Términos y Condiciones]({{client_terms_url}}), que regulan también la ley aplicable y el fuero competente. Para los tratamientos de datos personales de los que Spaarkly es responsable se aplica la [Política de Privacidad ARShades](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/es/). Nada en las presentes Condiciones excluye, limita o perjudica los derechos reconocidos al Usuario por normas imperativas, incluidos los derechos de los consumidores.
<!-- /BLOCK rapporto-documenti -->

<!-- BLOCK contatti [CLIENT] -->
## Contacto

Para consultas sobre la experiencia de compra: **{{support_email}}**.

Para cuestiones relativas a las funcionalidades ARShades: **legal@spaarkly.com**; para la privacidad ARShades: **privacy@spaarkly.com**.
<!-- /BLOCK contatti -->

---

Al hacer clic en «Aceptar», o al utilizar las funcionalidades ARShades tras haber tenido la posibilidad de consultarlas, el Usuario declara haber leído y comprendido las presentes Condiciones y aceptarlas.
