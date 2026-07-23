# SITIO WEB ARSHADES — POLÍTICA DE COOKIES

*Sitio web de marketing ARShades* </br> *Versión 1.0.1 — Última actualización: 23 de julio de 2026 — Fecha de entrada en vigor: 22 de julio de 2026*

La presente Política de Cookies complementa la [Política de Privacidad del Sitio](../privacy-website/en.md) y describe las cookies y las tecnologías similares (incluido el *localStorage*) utilizadas por el **sitio web de marketing ARShades** de **Spaarkly s.r.l.** Concierne exclusivamente al sitio web de presentación de las soluciones ARShades; las cookies y las tecnologías empleadas dentro de las experiencias de producto ARShades (por ejemplo, el Virtual Try-On iniciado por el Usuario) se describen en la Política de Privacidad de las soluciones ARShades.

## 1. Qué son las cookies

Las cookies son pequeños archivos de texto que un sitio web almacena en tu dispositivo. Tecnologías similares —como el *localStorage* del navegador— guardan información de forma análoga. La normativa europea (Directiva ePrivacy, art. 122 del Código de Privacidad y RGPD) exige el consentimiento previo para cada cookie o tecnología similar que **no** sea estrictamente necesaria para el funcionamiento del sitio.

## 2. Categorías utilizadas

- **Estrictamente necesarias / técnicas** — imprescindibles para el funcionamiento del Sitio: tu elección sobre las cookies, las preferencias de tema y de idioma, y las cookies de autenticación del área administrativa reservada. No requieren consentimiento.
- **Analytics** — cookies de medición de **Google Analytics 4**, utilizadas exclusivamente para estadísticas agregadas de uso del Sitio. **Se instalan únicamente si habilitas la categoría "Analytics" en el banner.** La analítica está configurada en modo respetuoso con la privacidad: consentimiento denegado de forma predeterminada (Google Consent Mode v2), anonimización de la dirección IP activa, sin Google Signals, sin funcionalidades publicitarias o de remarketing, sin elaboración de perfiles cross-site.
- **Funcionales** — tecnologías cargadas **solo a petición expresa tuya** (por ejemplo, el autocompletado de la dirección en el formulario de registro o el inicio de una demo interactiva). Dado que se activan únicamente tras una acción tuya, no aparecen en el banner inicial pero están descritas en el §5.
- **Marketing** — categoría prevista pero **actualmente no utilizada**: el Sitio no instala cookies publicitarias ni de elaboración de perfiles. En caso de introducción, el banner y la tabla se actualizarán y se solicitará de nuevo el consentimiento.

## 3. Base jurídica y consentimiento

Las cookies técnicas se fundamentan en el **interés legítimo** (art. 6, apdo. 1, letra f, RGPD); todas las demás categorías se fundamentan exclusivamente en tu **consentimiento** (art. 6, apdo. 1, letra a, RGPD), recabado mediante el banner en la primera visita, con igual evidencia entre "Aceptar todo" y "Rechazar todo".

Tu elección —incluido el rechazo— se conserva durante **12 meses** en la cookie first-party `ars_consent`. Una prueba mínima del consentimiento (identificador aleatorio, marca temporal, versión e idioma de la política visualizada en el banner, categorías y acción —**sin dirección IP ni user-agent**—) se registra en nuestros servidores durante el tiempo necesario para demostrar el consentimiento (hasta **26 meses**) y después se elimina automáticamente. En caso de rechazo, no se te solicitará un nuevo consentimiento durante al menos **6 meses**, salvo modificaciones sustanciales de la política.

## 4. Lista de cookies

<!-- cookie-table:start -->

| Nombre | Proveedor | Finalidad | Duración | Categoría |
|---|---|---|---|---|
| `ars_consent` | Spaarkly (first-party) | Guarda tu elección de consentimiento de cookies (categorías, versión, fecha). | 12 meses | Estrictamente necesarias |
| `NEXT_LOCALE` | Spaarkly (first-party) | Establecida por el enrutamiento de idioma del sitio para recordar el idioma detectado/seleccionado. | Sesión | Estrictamente necesarias |
| `theme` | Spaarkly (first-party) | Recuerda tu preferencia de tema claro/oscuro. | Persistente (localStorage) | Estrictamente necesarias |
| `_ga` | Google LLC (Google Analytics 4) | Google Analytics 4 — distingue a los usuarios. | 2 años | Analítica |
| `_ga_<container>` | Google LLC (Google Analytics 4) | Google Analytics 4 — mantiene el estado de la sesión. | 2 años | Analítica |
| `__admin_session` | Spaarkly (first-party) | Autenticación del área de administración reservada (solo páginas de administración). | 5 días | Estrictamente necesarias |
| `__admin_access` | Spaarkly (first-party) | Control de acceso al área de administración reservada (solo páginas de administración). | 1 año | Estrictamente necesarias |

<!-- cookie-table:end -->

Las cookies analíticas (`_ga`, `_ga_<container>`) son instaladas por Google solo tras tu consentimiento; al revocarlo, se eliminan. Los datos a nivel de usuario y de evento recabados por Google Analytics 4 se conservan durante un máximo de **14 meses**; los informes estadísticos agregados, que no contienen datos personales, pueden conservarse durante más tiempo.

Además de las cookies enumeradas, el Sitio utiliza algunos **servicios cargados solo a petición expresa tuya** que no instalan cookies: están descritos en el §5.

## 5. Cookies y tecnologías de terceros

El único tercero que puede instalar cookies de medición en este Sitio es **Google LLC** (Google Analytics 4), y solo tras tu consentimiento. Google LLC se adhiere al **EU–U.S. Data Privacy Framework**; para los detalles sobre las transferencias internacionales de datos, consulta la [Política de Privacidad del Sitio](../privacy-website/en.md).

Algunos **servicios cargados solo a petición expresa tuya** no instalan ni persisten cookies en este Sitio (por tanto, no aparecen en la tabla del §4, que enumera las cookies y las tecnologías de almacenamiento):

- **Demos interactivas Virtual Try-On** servidas por *webvto.it* (servicio de Spaarkly): el embed se carga solo cuando haces clic para iniciar la demo y dura durante la sesión.
- **API Google Maps Places**, utilizada por el campo de autocompletado de dirección del formulario de registro: se carga solo cuando empiezas a escribir en ese campo. Para este servicio, Google actúa como responsable del tratamiento independiente; los detalles están en la [Política de Privacidad del Sitio](../privacy-website/en.md).

El área administrativa reservada y el formulario de registro utilizan además **Firebase Authentication** (Google/Firebase) para la gestión del acceso: dicho servicio almacena datos técnicos de sesión en el navegador (IndexedDB) con el único fin de mantener la autenticación, sin finalidades de rastreo o de elaboración de perfiles.

## 6. Gestión de las preferencias

- Usa el enlace **"Preferencias de cookies"** presente en el pie de página de cada página para revisar o modificar tus elecciones en cualquier momento; la revocación del consentimiento Analytics conlleva también la eliminación de las cookies `_ga*`.
- Puedes además eliminar o bloquear las cookies desde la configuración del navegador (esto puede afectar a funciones técnicas como la persistencia del tema y del idioma).

## 7. Actualizaciones de la presente Política de Cookies

Las modificaciones sustanciales de la presente Política (nuevas cookies, nuevas finalidades, nuevos terceros) conllevan una nueva solicitud de consentimiento mediante el banner. La versión de la política que has aceptado se registra junto con tu elección.

## 8. Contacto

Spaarkly s.r.l. — Via della Tecnica n. 18, 85100 Potenza (Italia) — privacy@spaarkly.com.

---

© Spaarkly s.r.l. Todos los derechos reservados.
