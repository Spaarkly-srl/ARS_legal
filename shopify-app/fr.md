# Politique de confidentialité d'ARShades VTO for Shopify

Version préliminaire pour soumission à Shopify  
Dernière mise à jour : 6 juillet 2026

La présente Politique de confidentialité décrit la manière dont **Spaarkly s.r.l.** (« Spaarkly », « ARShades », « nous » ou « notre ») traite les données à caractère personnel et d'autres informations dans le cadre de l'application **ARShades VTO for Shopify** (l'« application Shopify » ou l'« App »).

La présente politique est propre à l'application Shopify et se limite aux données traitées en lien avec Shopify (données relatives au marchand, à la boutique, aux produits, à la configuration et à l'attribution). Les traitements réalisés par les services destinés aux utilisateurs finaux d'ARShades — tels que Virtual Try-On, le 3D/AR Viewer et l'AR PD Meter — susceptibles d'être lancés via l'App ne sont pas couverts par la présente politique et sont régis par la **Politique de confidentialité principale d'ARShades** (version 5.3), disponible à l'adresse [https://github.com/Spaarkly-srl/privacy-policies](https://github.com/Spaarkly-srl/privacy-policies/blob/main/core/fr.md) et présentée aux acheteurs au sein des expériences ARShades.

## 1. Responsable du traitement

Spaarkly s.r.l. agit en qualité de responsable de traitement autonome pour les données à caractère personnel traitées au moyen de l'application Shopify.

**Responsable du traitement :** Spaarkly s.r.l.  
**Adresse du siège social :** Via della Tecnica n. 18, 85100 Potenza, Italy  
**Contact confidentialité :** privacy@spaarkly.com

## 2. Fonctionnement de l'application Shopify

L'application Shopify relie la boutique Shopify d'un marchand à la plateforme ARShades. Elle permet aux marchands de :

* associer un jeton de licence ARShades à une boutique Shopify ;
* créer ou associer un catalogue ARShades ;
* faire correspondre les produits et variantes Shopify avec les assets 3D/VTO d'ARShades à l'aide du SKU, de l'EAN ou d'identifiants produit similaires ;
* ajouter des theme blocks pour Virtual Try-On, le 3D/AR Viewer et l'AR PD Meter ;
* personnaliser les couleurs, les styles de boutons, les paramètres des fenêtres modales et certains éléments de marque ;
* utiliser les événements du Web Pixel de Shopify pour l'attribution VTO/3D et les analyses de conversion.

L'App est gratuite à installer sur Shopify. Le service ARShades sous-jacent peut nécessiter un abonnement ARShades distinct souscrit en dehors de Shopify.

## 3. Catégories de données que nous traitons

### 3.1 Données du marchand et de l'administration Shopify

Lorsqu'un marchand installe ou utilise l'App, nous sommes susceptibles de traiter :

* le domaine de la boutique Shopify et l'URL de la boutique ;
* les données de session OAuth de Shopify ;
* le jeton d'accès et les scopes autorisés ;
* les identifiants de l'utilisateur administrateur Shopify et, lorsque Shopify les communique, le prénom, le nom, l'adresse e-mail, la langue (locale), le statut de collaborateur, le statut de propriétaire du compte et le statut de vérification de l'e-mail ;
* l'état d'installation, de configuration et d'utilisation de l'App.

Ces données servent à authentifier le marchand, à exploiter l'App intégrée, à maintenir la session de l'App ainsi qu'à fournir l'assistance et la sécurité.

### 3.2 Données de licence, de catalogue et de configuration ARShades

Nous traitons les informations nécessaires pour relier la boutique Shopify à ARShades, notamment :

* le jeton de licence ARShades ou l'identifiant d'abonnement ;
* l'ID de catalogue ARShades, le nom du catalogue et l'état du catalogue ;
* l'ID du 3D viewer et les capacités du service ARShades, telles que la disponibilité du VTO ou de l'AR PD Meter ;
* la configuration de l'App enregistrée sous forme de metafields Shopify, notamment `licenseId`, `catalogueId`, `viewerId`, `webDomain`, `studioDomain`, `has_vto` et `has_arpd` ;
* les paramètres de style tels que les couleurs, les paramètres des fenêtres modales et les paramètres des boutons ;
* les éléments de marque téléchargés par le marchand, tels qu'un logo utilisé dans les écrans d'autorisation ou de politique d'ARShades.

### 3.3 Données relatives aux produits et variantes Shopify

Afin de faire correspondre les produits avec les assets ARShades et d'afficher les fonctionnalités VTO/3D uniquement là où elles sont disponibles, l'App peut lire et traiter :

* l'ID de produit Shopify, le titre, le handle et l'URL de l'image mise en avant ;
* l'ID de variante Shopify ;
* le SKU, le barcode, l'EAN ou l'UPC ;
* les valeurs de metafield ARShades existantes ;
* les identifiants de produit et de variante du catalogue ARShades.

L'App peut écrire des metafields techniques ARShades sur les variantes Shopify, notamment `catalogueVariantId` et `catalogueProductId`. Ces metafields sont utilisés par les theme blocks de la vitrine (storefront) pour déterminer si un produit ou une variante peut lancer ARShades VTO ou le 3D/AR Viewer.

### 3.4 Données de la vitrine traitées par l'App

Lorsqu'un acheteur utilise le VTO ou le 3D/AR Viewer sur la vitrine du marchand, l'App peut traiter les données techniques suivantes, dépourvues de profil :

* les identifiants de produit et de variante ;
* les identifiants de catalogue ARShades ;
* les identifiants de la variante sélectionnée ou de la dernière variante essayée ;
* les informations relatives à l'appareil, au navigateur, à la langue et à la session ;
* les événements techniques indiquant qu'une session VTO ou 3D a été ouverte.

Ces données servent à afficher l'expérience appropriée sur la vitrine et à alimenter les analyses d'attribution décrites à la Section 3.6.

### 3.5 Expériences ARShades destinées aux utilisateurs finaux (VTO, 3D/AR Viewer, AR PD Meter)

Les traitements fondés sur la caméra qui interviennent au sein des expériences ARShades lancées depuis la vitrine — y compris le rendu Virtual Try-On et le calcul de la distance pupillaire de l'AR PD Meter — sont réalisés par les services ARShades, et non par l'application Shopify, et sont régis par la Politique de confidentialité principale d'ARShades.

En résumé, et comme le décrit ladite politique : les images et flux vidéo issus de la caméra ne sont pas conservés ; aucun gabarit facial ni identifiant biométrique n'est créé ; et, pour l'AR PD Meter, des données techniques dérivées de la caméra qui n'identifient pas l'acheteur peuvent être transmises temporairement au backend ARShades situé dans l'Union européenne, utilisées uniquement pour renvoyer le résultat de la mesure, puis supprimées après traitement. L'application Shopify elle-même n'accède pas aux données de la caméra, ne les conserve pas et ne les reçoit pas.

### 3.6 Web Pixel de Shopify et analyses de conversion

L'App utilise un Web Pixel de Shopify pour mesurer l'attribution VTO/3D et les performances de conversion. Le pixel peut traiter :

* le domaine de la boutique ;
* le type d'événement et l'horodatage ;
* un ID de session VTO/3D pseudonymisé ;
* les identifiants de produit et de variante ;
* les identifiants de produit et de variante du catalogue ARShades ;
* les identifiants de panier pour l'attribution des ajouts au panier ;
* les identifiants de commande/paiement, le prix total, la devise et les métadonnées des lignes d'article pour l'attribution des achats ;
* le fait que l'achat soit survenu à la suite d'une session VTO/3D ou sans session VTO/3D, à des fins d'analyses comparatives.

Le pixel est conçu pour ne pas transmettre au backend d'analyse d'ARShades de données de profil directes des acheteurs telles que le nom, l'adresse e-mail, le numéro de téléphone ou l'adresse de livraison.

Le pixel de la vitrine peut recourir au stockage local du navigateur pour mémoriser une session VTO/3D active à des fins d'attribution. Ces données de session locales expirent au bout de 7 jours ou sont effacées après un achat suivi.

Le pixel n'est chargé par le gestionnaire de pixels de Shopify que lorsque le consentement du visiteur correspond aux catégories de consentement déclarées par l'App (telles que `analytics`), conformément à la Customer Privacy API de Shopify et à la configuration de consentement du marchand. Nous respectons ces signaux de consentement et ne traitons pas les événements de pixel collectés sans le consentement requis.

## 4. Finalités et bases légales

Nous traitons les données décrites ci-dessus aux fins suivantes :

* installer, authentifier et exploiter l'application Shopify ;
* relier la boutique du marchand à une licence et à un catalogue ARShades ;
* synchroniser les métadonnées de produits et de variantes avec ARShades ;
* activer le VTO, le 3D/AR Viewer et l'AR PD Meter sur la vitrine ;
* maintenir les metafields Shopify et la configuration de l'App ;
* mesurer l'attribution VTO/3D, les événements d'ajout au panier et les analyses de conversion des achats ;
* sécuriser l'App, prévenir les usages abusifs et résoudre les problèmes techniques ;
* respecter les exigences de revue d'application, de confidentialité et de conformité de Shopify ;
* répondre aux demandes en matière de protection des données et aux obligations légales.

Selon le contexte et le droit applicable, les bases légales peuvent inclure l'exécution d'un contrat, l'intérêt légitime, le respect d'obligations légales ainsi que le consentement lorsqu'il est requis, y compris les exigences de consentement relatives à l'accès à la caméra ou aux analyses.

## 5. Conservation des données

Nous ne conservons les données que pendant la durée nécessaire aux finalités décrites dans la présente politique.

* La configuration active de l'App, les metafields Shopify, les correspondances produit/variante et les sessions OAuth sont conservés tant que l'App demeure installée et que les données sont nécessaires à l'exploitation du service.
* Les données d'App propres à une boutique sont supprimées ou anonymisées lorsque Shopify envoie un webhook de conformité `shop/redact` valide, sauf si leur conservation est requise par la loi ou à des fins légitimes de sécurité.
* Les analyses de pixel, les événements de conversion, les journaux techniques, les données de session et les données historiques similaires sont conservés pendant une durée maximale de 14 mois, puis agrégés ou anonymisés.
* Les éléments de marque téléchargés par le marchand et les paramètres de style sont conservés tant qu'ils sont nécessaires au service actif et sont supprimés ou anonymisés après suppression, désinstallation ou expiration de la durée de conservation applicable.
* Les données traitées au sein des expériences ARShades destinées aux utilisateurs finaux (y compris l'AR PD Meter) sont conservées selon les modalités décrites dans la Politique de confidentialité principale d'ARShades.

## 6. Webhooks de confidentialité et de conformité de Shopify

L'App met en œuvre les points de terminaison de webhooks de confidentialité et de conformité de Shopify pour :

* `customers/data_request` ;
* `customers/redact` ;
* `shop/redact`.

Les requêtes de webhook sont vérifiées au moyen de la signature HMAC de Shopify ; les requêtes dont la signature est invalide sont rejetées. Nous accomplissons les actions de demande de données et d'effacement dans les 30 jours suivant la réception du webhook.

La base de données de l'App ne stocke pas de données de profil directes des clients finaux telles que le nom, l'adresse e-mail, le numéro de téléphone ou l'adresse de livraison de l'acheteur. Pour les demandes au niveau du client, nous vérifions le webhook Shopify et répondons en fonction des données détenues par l'App.

Le webhook `shop/redact` est envoyé par Shopify 48 heures après la désinstallation de l'App. Dès réception, nous supprimons les données d'App stockées de la boutique, y compris les sessions Shopify, les correspondances de variantes synchronisées et les paramètres du pixel de la boutique, sous réserve des exigences légales ou de sécurité en matière de conservation.

## 7. Partage et sous-traitants ultérieurs

Nous ne partageons les données que dans la mesure nécessaire pour exploiter, sécuriser et prendre en charge l'App et les services ARShades.

Les prestataires de services et les infrastructures confirmés utilisés pour l'application Shopify et les services ARShades associés comprennent :

* Shopify, pour l'installation de l'application, l'OAuth, l'Admin API, les theme extensions, les Customer Events et l'infrastructure du Web Pixel ;
* Vercel, pour l'hébergement de l'application Shopify ;
* Neon/Vercel Postgres, pour l'hébergement de la base de données de l'App ;
* Google Cloud/Firebase, pour les fonctions du backend ARShades et le traitement des analyses, avec des données traitées dans des régions de l'Union européenne ;
* Cloudways CDN, pour la diffusion des assets du bundle de vitrine d'ARShades.

Ces prestataires traitent les données selon leurs propres conditions et les engagements applicables en matière de traitement des données. Nous ne vendons ni ne partageons (au sens du California Consumer Privacy Act) les données à caractère personnel des acheteurs. Nous n'utilisons pas les données de l'application Shopify à des fins de publicité sans rapport, de reconnaissance faciale, d'identification biométrique ou d'entraînement de modèles d'IA, et nous ne procédons pas à une prise de décision automatisée produisant des effets juridiques ou des effets significatifs similaires.

Un accord de traitement des données (DPA) couvrant les traitements de l'App est mis à la disposition des marchands sur demande à l'adresse privacy@spaarkly.com.

## 8. Transferts internationaux

L'application Shopify ainsi que les services d'analyse et de traitement d'ARShades sont configurés pour traiter et stocker les données concernées au sein de l'Union européenne lorsque cela est applicable.

Si un prestataire de services traite des données à caractère personnel en dehors de l'Espace économique européen (EEE), nous recourons aux garanties appropriées exigées par le droit applicable, telles que les Clauses Contractuelles Types (CCT) ou des mécanismes de transfert équivalents.

## 9. Sécurité

Nous mettons en œuvre des mesures techniques et organisationnelles destinées à protéger les données traitées par l'App, notamment :

* le protocole HTTPS/TLS pour les données en transit ;
* le chiffrement au repos pour la base de données de l'App ;
* des contrôles d'accès et une authentification ;
* la vérification OAuth et des webhooks de Shopify ;
* des contrôles d'accès à la base de données ;
* la minimisation des scopes Shopify demandés ;
* la journalisation et la supervision opérationnelles à des fins de sécurité et de résolution des problèmes.

Aucune méthode de transmission ou de stockage n'est totalement sûre, mais nous nous employons à maintenir des garanties adaptées à la nature des données et aux risques encourus.

### Réponse aux incidents de sécurité

En cas d'incident de sécurité affectant les données traitées par l'App, nous évaluerons l'incident au titre de l'article 33 du RGPD, y remédierons dans les meilleurs délais et notifierons l'autorité de contrôle compétente dans les 72 heures lorsque cela est requis. Dans la mesure où nous détenons les coordonnées des marchands, nous notifierons directement et sans retard injustifié les marchands concernés, et nous coopérerons avec les processus de gestion des incidents de Shopify le cas échéant.

## 10. Autorisations de la caméra pour les acheteurs

L'accès à la caméra est demandé par le navigateur ou le système d'exploitation de l'appareil de l'acheteur uniquement au sein des expériences ARShades (VTO, AR PD Meter). Les acheteurs peuvent refuser ou révoquer l'accès à la caméra via les paramètres de leur navigateur ou de leur appareil ; en cas de refus, ces expériences peuvent ne pas fonctionner. L'application Shopify elle-même n'accède pas à la caméra.

La manière dont les données de la caméra sont traitées au sein des expériences ARShades est décrite dans la Politique de confidentialité principale d'ARShades.

## 11. Protection des données des enfants

L'App est destinée à être utilisée par les marchands Shopify et les acheteurs de leur vitrine. Les services ARShades n'ont pas vocation à collecter sciemment des données à caractère personnel d'enfants n'ayant pas atteint l'âge applicable du consentement numérique en l'absence du consentement approprié d'un parent ou d'un tuteur.

Si vous estimez qu'un enfant a communiqué des données à caractère personnel via ARShades sans le consentement approprié, contactez-nous à l'adresse privacy@spaarkly.com.

## 12. Vos droits

Selon votre lieu de résidence, vous pouvez disposer de droits d'accès, de rectification, d'effacement, de limitation, d'opposition ou de réception d'une copie de vos données à caractère personnel.

Les marchands peuvent nous contacter à l'adresse privacy@spaarkly.com. Les acheteurs peuvent également contacter le marchand dont ils ont visité la boutique, ou contacter directement Spaarkly lorsque Spaarkly agit en qualité de responsable du traitement pour les traitements ARShades.

Nous pourrons avoir besoin d'informations telles que le domaine de la boutique, la date/heure approximative, les identifiants d'événement, les détails relatifs à l'appareil/à la session ou d'autres informations afin de localiser les enregistrements pertinents.

Vous disposez également du droit d'introduire une réclamation auprès d'une autorité de contrôle, telle que l'autorité italienne Garante per la Protezione dei Dati Personali ([www.garanteprivacy.it](https://www.garanteprivacy.it)) ou l'autorité compétente de votre pays de résidence.

## 13. Modifications de la présente politique

Nous pouvons mettre à jour la présente Politique de confidentialité afin de tenir compte des évolutions de l'application Shopify, des services ARShades, des exigences légales ou des pratiques opérationnelles. Lorsque nous mettons la politique à jour, nous en modifions la date de « Dernière mise à jour ».

## 14. Contact

Pour toute question ou demande relative à la protection des données, contactez :

**Spaarkly s.r.l.**  
Via della Tecnica n. 18  
85100 Potenza, Italy  
Email : privacy@spaarkly.com
