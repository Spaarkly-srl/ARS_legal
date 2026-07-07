# Política de Privacidad de ARShades VTO for Shopify

Versión preliminar para el envío a Shopify  
Última actualización: 6 de julio de 2026

La presente Política de Privacidad describe cómo **Spaarkly s.r.l.** («Spaarkly», «ARShades», «nosotros» o «nuestro») trata los datos personales y demás información relacionados con la aplicación **ARShades VTO for Shopify** (la «Aplicación de Shopify» o la «Aplicación»).

Esta política es específica de la Aplicación de Shopify y se circunscribe a los datos tratados en relación con Shopify (datos del comerciante, de la tienda, de los productos, de configuración y de atribución). El tratamiento efectuado por los servicios de ARShades dirigidos al usuario final —tales como Virtual Try-On, 3D/AR Viewer y AR PD Meter—, que pueden iniciarse a través de la Aplicación, no queda comprendido en esta política y se rige por la **Política de Privacidad principal de ARShades** (versión 5.3), disponible en [https://github.com/Spaarkly-srl/ARS_legal](https://github.com/Spaarkly-srl/ARS_legal/blob/main/privacy-policy/es.md) y mostrada a los compradores dentro de las experiencias de ARShades.

## 1. Responsable del tratamiento

Spaarkly s.r.l. actúa como responsable del tratamiento independiente respecto de los datos personales tratados a través de la Aplicación de Shopify.

**Responsable del tratamiento:** Spaarkly s.r.l.  
**Domicilio social:** Via della Tecnica n. 18, 85100 Potenza, Italy  
**Contacto en materia de privacidad:** privacy@spaarkly.com

## 2. Qué hace la Aplicación de Shopify

La Aplicación de Shopify conecta la tienda Shopify de un comerciante con la plataforma ARShades. Permite a los comerciantes:

* conectar un token de licencia de ARShades a una tienda Shopify;
* crear o conectar un catálogo de ARShades;
* asociar productos y variantes de Shopify con activos 3D/VTO de ARShades mediante SKU, EAN u otros identificadores de producto similares;
* añadir theme blocks para Virtual Try-On, 3D/AR Viewer y AR PD Meter;
* personalizar colores, estilos de botones, configuraciones de ventanas modales y determinados activos de marca;
* utilizar eventos de Shopify Web Pixel para la atribución y las analíticas de conversión de VTO/3D.

La Aplicación es de instalación gratuita en Shopify. El servicio subyacente de ARShades puede requerir una suscripción de ARShades independiente, contratada fuera de Shopify.

## 3. Categorías de datos que tratamos

### 3.1 Datos del comerciante y del panel de administración de Shopify

Cuando un comerciante instala o utiliza la Aplicación, podemos tratar:

* el dominio de la tienda Shopify y la URL de la tienda;
* los datos de sesión de OAuth de Shopify;
* el token de acceso y los scopes autorizados;
* los identificadores de usuario administrador de Shopify y, cuando Shopify los facilite, nombre, apellidos, dirección de correo electrónico, configuración regional (locale), condición de colaborador, condición de titular de la cuenta y estado de verificación del correo electrónico;
* el estado de instalación, configuración y uso de la Aplicación.

Estos datos se emplean para autenticar al comerciante, operar la Aplicación integrada, mantener la sesión de la Aplicación y prestar soporte y seguridad.

### 3.2 Datos de licencia, catálogo y configuración de ARShades

Tratamos la información necesaria para conectar la tienda Shopify con ARShades, entre ella:

* el token de licencia o el identificador de suscripción de ARShades;
* el ID de catálogo, el nombre del catálogo y el estado del catálogo de ARShades;
* el ID del 3D viewer y las capacidades del servicio de ARShades, tales como la disponibilidad de VTO o de AR PD Meter;
* la configuración de la Aplicación guardada como metafields de Shopify, incluidos `licenseId`, `catalogueId`, `viewerId`, `webDomain`, `studioDomain`, `has_vto` y `has_arpd`;
* los ajustes de estilo, como colores, configuraciones de ventanas modales y ajustes de botones;
* los activos de marca cargados por el comerciante, como un logotipo utilizado en las pantallas de permisos o de políticas de ARShades.

### 3.3 Datos de productos y variantes de Shopify

Para asociar productos con activos de ARShades y mostrar las funciones VTO/3D únicamente cuando estén disponibles, la Aplicación puede leer y tratar:

* el ID de producto, el título, el handle y la URL de la imagen destacada de Shopify;
* el ID de variante de Shopify;
* SKU, barcode, EAN o UPC;
* los valores de metafield de ARShades existentes;
* los identificadores de producto y variante del catálogo de ARShades.

La Aplicación puede escribir metafields técnicos de ARShades en las variantes de Shopify, incluidos `catalogueVariantId` y `catalogueProductId`. Estos metafields son utilizados por los theme blocks del escaparate (storefront) para determinar si un producto o una variante puede iniciar ARShades VTO o el 3D/AR Viewer.

### 3.4 Datos del escaparate tratados por la Aplicación

Cuando un comprador utiliza VTO o el 3D/AR Viewer en el escaparate del comerciante, la Aplicación puede tratar los siguientes datos técnicos, que no constituyen datos de perfil:

* los identificadores de producto y variante;
* los identificadores de catálogo de ARShades;
* los identificadores de la variante seleccionada o de la última probada;
* información de dispositivo, navegador, idioma y sesión;
* eventos técnicos que indican que se ha abierto una sesión de VTO o 3D.

Estos datos se utilizan para mostrar la experiencia correcta en el escaparate y para sustentar las analíticas de atribución descritas en el apartado 3.6.

### 3.5 Experiencias de ARShades para el usuario final (VTO, 3D/AR Viewer, AR PD Meter)

El tratamiento basado en la cámara que tiene lugar dentro de las experiencias de ARShades iniciadas desde el escaparate —incluidos el renderizado de Virtual Try-On y el cálculo de la distancia pupilar de AR PD Meter— es efectuado por los servicios de ARShades, no por la Aplicación de Shopify, y se rige por la Política de Privacidad principal de ARShades.

En síntesis, y según se describe en dicha política: las imágenes y las secuencias de vídeo de la cámara no se almacenan; no se crean plantillas faciales ni identificadores biométricos; y, en el caso de AR PD Meter, los datos técnicos derivados de la cámara que no identifican al comprador pueden transmitirse temporalmente al backend de ARShades ubicado en la Unión Europea, utilizarse únicamente para devolver el resultado de la medición y descartarse una vez concluido el tratamiento. La propia Aplicación de Shopify no accede a los datos de la cámara, ni los almacena ni los recibe.

### 3.6 Shopify Web Pixel y analíticas de conversión

La Aplicación utiliza un Shopify Web Pixel para medir la atribución y el rendimiento de conversión de VTO/3D. El pixel puede tratar:

* el dominio de la tienda;
* el tipo de evento y la marca temporal;
* un ID de sesión de VTO/3D seudonimizado;
* los identificadores de producto y variante;
* los identificadores de producto y variante del catálogo de ARShades;
* los identificadores de carrito para la atribución de la adición al carrito;
* los identificadores de checkout/pedido, el precio total, la moneda y los metadatos de las líneas de pedido para la atribución de la compra;
* si la compra se produjo tras una sesión de VTO/3D o sin una sesión de VTO/3D, a efectos de analíticas comparativas.

El pixel está diseñado para no enviar al backend de analíticas de ARShades datos directos de perfil del comprador, tales como el nombre, la dirección de correo electrónico, el número de teléfono o la dirección de envío.

El pixel del escaparate puede utilizar el almacenamiento local del navegador para recordar una sesión de VTO/3D activa a efectos de atribución. Estos datos de sesión locales caducan transcurridos 7 días o se eliminan tras una compra objeto de seguimiento.

El pixel es cargado por el gestor de pixels de Shopify únicamente cuando el consentimiento del visitante coincide con las categorías de consentimiento declaradas por la Aplicación (como `analytics`), de conformidad con la Customer Privacy API de Shopify y la configuración de consentimiento del comerciante. Respetamos estas señales de consentimiento y no tratamos eventos del pixel recabados sin el consentimiento requerido.

## 4. Finalidades y bases jurídicas

Tratamos los datos anteriormente descritos con las siguientes finalidades:

* instalar, autenticar y operar la Aplicación de Shopify;
* conectar la tienda del comerciante con una licencia y un catálogo de ARShades;
* sincronizar los metadatos de productos y variantes con ARShades;
* habilitar VTO, el 3D/AR Viewer y AR PD Meter en el escaparate;
* mantener los metafields de Shopify y la configuración de la Aplicación;
* medir la atribución de VTO/3D, los eventos de adición al carrito y las analíticas de conversión de compra;
* proteger la Aplicación, prevenir usos indebidos y resolver incidencias técnicas;
* cumplir los requisitos de revisión de aplicaciones, privacidad y conformidad de Shopify;
* atender las solicitudes en materia de privacidad y las obligaciones legales.

En función del contexto y de la legislación aplicable, las bases jurídicas pueden comprender la ejecución de un contrato, el interés legítimo, el cumplimiento de obligaciones legales y el consentimiento cuando resulte necesario, incluidos los requisitos de consentimiento para el acceso a la cámara o para las analíticas.

## 5. Conservación de los datos

Conservamos los datos únicamente durante el tiempo necesario para las finalidades descritas en esta política.

* La configuración activa de la Aplicación, los metafields de Shopify, las asociaciones de productos/variantes y las sesiones de OAuth se conservan mientras la Aplicación permanezca instalada y los datos sean necesarios para operar el servicio.
* Los datos de la Aplicación específicos de la tienda se suprimen o anonimizan cuando Shopify envía un webhook de conformidad `shop/redact` válido, salvo que la ley o intereses legítimos de seguridad exijan su conservación.
* Las analíticas del pixel, los eventos de conversión, los registros técnicos, los datos de sesión y demás datos históricos similares se conservan durante un máximo de 14 meses y, a continuación, se agregan o anonimizan.
* Los activos de marca cargados por el comerciante y los ajustes de estilo se conservan mientras sean necesarios para el servicio activo y se eliminan o anonimizan tras la supresión, la desinstalación o el vencimiento del plazo de conservación aplicable.
* Los datos tratados dentro de las experiencias de ARShades para el usuario final (incluida AR PD Meter) se conservan según se describe en la Política de Privacidad principal de ARShades.

## 6. Webhooks de privacidad y conformidad de Shopify

La Aplicación implementa los endpoints de los webhooks de privacidad y conformidad de Shopify para:

* `customers/data_request`;
* `customers/redact`;
* `shop/redact`.

Las solicitudes de webhook se verifican mediante la firma HMAC de Shopify; las solicitudes con una firma no válida se rechazan. Completamos las acciones de solicitud y supresión de datos en un plazo de 30 días desde la recepción del webhook.

La base de datos de la Aplicación no almacena datos directos de perfil del cliente final, tales como el nombre del comprador, la dirección de correo electrónico, el número de teléfono o la dirección de envío. Para las solicitudes relativas a clientes concretos, verificamos el webhook de Shopify y respondemos con arreglo a los datos que obran en poder de la Aplicación.

Shopify envía `shop/redact` 48 horas después de la desinstalación de la Aplicación. Una vez recibido, suprimimos los datos de la Aplicación almacenados de la tienda, incluidas las sesiones de Shopify, las asociaciones de variantes sincronizadas y los ajustes del pixel de la tienda, sin perjuicio de los requisitos legales o de seguridad en materia de conservación.

## 7. Comunicación de datos y subencargados del tratamiento

Comunicamos datos únicamente en la medida necesaria para operar, proteger y dar soporte a la Aplicación y a los servicios de ARShades.

Los proveedores de servicios y la infraestructura confirmados que se utilizan para la Aplicación de Shopify y los servicios de ARShades relacionados incluyen:

* Shopify, para la infraestructura de instalación de aplicaciones, OAuth, Admin API, theme extensions, Customer Events y Web Pixel;
* Vercel, para el alojamiento de la Aplicación de Shopify;
* Neon/Vercel Postgres, para el alojamiento de la base de datos de la Aplicación;
* Google Cloud/Firebase, para las funciones de backend y el tratamiento analítico de ARShades, con datos tratados en regiones de la Unión Europea;
* Cloudways CDN, para el suministro de los activos del bundle de escaparate de ARShades.

Estos proveedores tratan los datos con arreglo a sus propias condiciones y a los compromisos de tratamiento de datos aplicables. No vendemos ni compartimos (según se define en la California Consumer Privacy Act) datos personales de los compradores. No utilizamos los datos de la Aplicación de Shopify para publicidad ajena a la finalidad, reconocimiento facial, identificación biométrica ni entrenamiento de modelos de IA, y no llevamos a cabo decisiones automatizadas que produzcan efectos jurídicos o efectos significativos de modo similar.

Se pone a disposición de los comerciantes, previa solicitud a privacy@spaarkly.com, un acuerdo de tratamiento de datos (DPA) que cubre el tratamiento realizado por la Aplicación.

## 8. Transferencias internacionales

La Aplicación de Shopify y los servicios de analítica y tratamiento de ARShades están configurados para tratar y almacenar los datos pertinentes en la Unión Europea cuando resulte aplicable.

Si un proveedor de servicios trata datos personales fuera del Espacio Económico Europeo (EEE), aplicamos las garantías adecuadas exigidas por la legislación aplicable, tales como las Cláusulas Contractuales Tipo (CCT) o mecanismos de transferencia equivalentes.

## 9. Seguridad

Aplicamos medidas técnicas y organizativas diseñadas para proteger los datos tratados por la Aplicación, entre ellas:

* HTTPS/TLS para los datos en tránsito;
* cifrado en reposo de la base de datos de la Aplicación;
* controles de acceso y autenticación;
* verificación de OAuth y de los webhooks de Shopify;
* controles de acceso a la base de datos;
* minimización de los scopes de Shopify solicitados;
* registro y monitorización operativos con fines de seguridad y resolución de incidencias.

Ningún método de transmisión o almacenamiento es completamente seguro, si bien trabajamos para mantener garantías adecuadas a la naturaleza de los datos y a los riesgos concurrentes.

### Respuesta ante incidentes de seguridad

Si un incidente de seguridad afecta a datos tratados por la Aplicación, evaluaremos el incidente conforme al artículo 33 del RGPD, lo mitigaremos con la mayor rapidez posible y lo notificaremos a la autoridad de control competente en un plazo de 72 horas cuando así se exija. Dado que disponemos de los datos de contacto de los comerciantes, notificaremos directamente y sin dilación indebida a los comerciantes afectados, y cooperaremos con los procesos de gestión de incidentes de Shopify cuando proceda.

## 10. Permisos de cámara del comprador

El acceso a la cámara es solicitado por el navegador o el sistema operativo del dispositivo del comprador únicamente dentro de las experiencias de ARShades (VTO, AR PD Meter). Los compradores pueden denegar o revocar el acceso a la cámara a través de la configuración del navegador o del dispositivo; en caso de denegación, dichas experiencias pueden no funcionar. La propia Aplicación de Shopify no accede a la cámara.

El modo en que se tratan los datos de la cámara dentro de las experiencias de ARShades se describe en la Política de Privacidad principal de ARShades.

## 11. Privacidad de los menores

La Aplicación está destinada al uso por comerciantes de Shopify y por los compradores de sus escaparates. Los servicios de ARShades no están destinados a recabar deliberadamente datos personales de menores por debajo de la edad de consentimiento digital aplicable sin el consentimiento adecuado de un progenitor o tutor.

Si considera que un menor ha facilitado datos personales a través de ARShades sin el consentimiento adecuado, póngase en contacto con nosotros en privacy@spaarkly.com.

## 12. Sus derechos

En función de su ubicación, es posible que le asistan derechos de acceso, rectificación, supresión, limitación, oposición o a recibir una copia de sus datos personales.

Los comerciantes pueden ponerse en contacto con nosotros en privacy@spaarkly.com. Los compradores también pueden dirigirse al comerciante cuya tienda hayan visitado, o contactar directamente con Spaarkly cuando Spaarkly actúe como responsable del tratamiento de los datos de ARShades.

Es posible que necesitemos información como el dominio de la tienda, la fecha/hora aproximadas, los identificadores de eventos, los datos de dispositivo/sesión u otra información para localizar los registros pertinentes.

Asimismo, le asiste el derecho a presentar una reclamación ante una autoridad de control, como el Garante per la Protezione dei Dati Personali italiano ([www.garanteprivacy.it](https://www.garanteprivacy.it)) o la autoridad competente en su país de residencia.

## 13. Modificaciones de esta política

Podemos actualizar esta Política de Privacidad para reflejar cambios en la Aplicación de Shopify, en los servicios de ARShades, en los requisitos legales o en las prácticas operativas. Cuando actualicemos la política, revisaremos la fecha de «Última actualización».

## 14. Contacto

Para consultas o solicitudes en materia de privacidad, contacte con:

**Spaarkly s.r.l.**  
Via della Tecnica n. 18  
85100 Potenza, Italy  
Email: privacy@spaarkly.com
