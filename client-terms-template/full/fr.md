---
published: false
---

# CONDITIONS GÉNÉRALES D'UTILISATION — FONCTIONNALITÉS ARSHADES

*{{client_trade_name}} — {{website_url}}* </br> *Conditions de {{client_legal_name}}, présentées au lancement de l'expérience — générées à partir du modèle Spaarkly «Client ARShades Integration Terms — Servizi VTO» v{{template_version}} du {{generated_date}}*

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
## Qui fournit quoi

**«{{client_trade_name}}»**, **«nous»** ou **«notre»** désigne {{client_legal_name}}, dont le siège est situé à {{client_registered_office}} ({{client_country}}), {{client_vat}}, qui exploite {{website_url}} et propose l'expérience commerciale : catalogues et collections, prix, disponibilité, commandes, assistance{{#prescription_sales_enabled}}, gestion des prescriptions{{/prescription_sales_enabled}} et l'intégralité du parcours d'achat.

**«Spaarkly»** désigne Spaarkly s.r.l. (P. IVA IT02077620769), qui développe et fournit les solutions logicielles de réalité augmentée **ARShades** intégrées à notre expérience. Spaarkly n'est pas le vendeur des produits présentés, n'exploite pas de marketplace et n'est ni un opticien, ni un optométriste, ni un autre professionnel qualifié de la vision.

Les présentes conditions («Conditions») sont présentées à l'Utilisateur, avec la [Politique de confidentialité ARShades](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/fr/), avant le lancement de l'expérience et en régissent l'utilisation. En cliquant sur «Accepter» (ou en accomplissant une action équivalente), l'Utilisateur les accepte ; à défaut d'acceptation, l'expérience n'est pas lancée. Pendant l'expérience, l'Utilisateur peut à tout moment relire les documents et révoquer son consentement depuis les paramètres.
<!-- /BLOCK ruoli -->

<!-- BLOCK funzionalita [CORE] -->
## Les fonctionnalités ARShades disponibles

{{#vto_enabled}}- **Virtual Try-On (VTO)** — l'essayage virtuel des lunettes en réalité augmentée au moyen de la caméra de l'appareil.{{/vto_enabled}}
{{#viewer_3d_enabled}}- **3D Viewer** — la visualisation tridimensionnelle qui permet l'exploration à 360° des modèles de lunettes (rotation et zoom) et, lorsque l'appareil le prend en charge, leur visualisation en réalité augmentée.{{/viewer_3d_enabled}}
{{#vto_explorer_enabled}}- **VTO Explorer** — des aperçus personnalisés de plusieurs modèles à partir d'un nombre limité d'images capturées pendant la session et traitées localement sur l'appareil.{{/vto_explorer_enabled}}
{{#mirror_enabled}}- **Mirror** — l'expérience d'essayage virtuel sur un appareil dédié dans nos points de vente ou showrooms ; la disponibilité et les conditions matérielles d'utilisation de l'appareil relèvent de notre responsabilité.{{/mirror_enabled}}
{{#gateway_enabled}}- **Gateway** — la plateforme ARShades qui propose des expériences d'essayage virtuel et un accès unifié aux expériences ARShades et aux boutiques des marques ; elle peut, à titre facultatif, utiliser la géolocalisation, sous réserve de consentement.{{/gateway_enabled}}
{{#campaign_catalogue_enabled}}- **Campaign Catalogue** — le catalogue numérique organisé au moyen duquel nous présentons des collections ou des campagnes sélectionnées ; les produits, les prix et les informations commerciales sont choisis et gérés par nous.{{/campaign_catalogue_enabled}}

{{#mobile_app_enabled}}Les fonctionnalités ARShades sont également disponibles au sein de notre application mobile ; le téléchargement et l'utilisation de l'application sont également soumis aux conditions de la boutique d'applications applicable (Apple App Store ou Google Play).{{/mobile_app_enabled}}

Configuration minimale requise pour les fonctionnalités reposant sur la caméra : une connexion Internet stable, un appareil doté d'une caméra et l'autorisation d'accès à la caméra pendant toute la durée de l'expérience. Les images de la caméra sont traitées en temps réel sur l'appareil de l'Utilisateur afin de positionner les lunettes virtuelles : elles ne sont ni conservées ni transmises aux serveurs de Spaarkly.
<!-- /BLOCK funzionalita -->

<!-- BLOCK natura [CORE] -->
## Nature de l'expérience virtuelle

L'essayage virtuel et la visualisation des modèles constituent une **aide visuelle** : en raison de limites techniques, le rendu (aspect, couleurs, ajustement, dimensions) peut différer du produit physique et varie en fonction de l'appareil, de la caméra, de l'éclairage et de l'environnement. Les décisions d'achat demeurent celles de l'Utilisateur ; l'expérience virtuelle ne constitue pas une garantie d'adéquation, de disponibilité ou d'aspect du produit. Sauf indication contraire, les fonctionnalités ARShades sont offertes aux Utilisateurs à titre gratuit.
<!-- /BLOCK natura -->

{{#shoot_share_enabled}}
<!-- BLOCK shoot-share [CORE] -->
## Photos et «Shoot & Share»

Les images éventuellement capturées au cours d'une session VTO Explorer sont traitées localement sur l'appareil utilisé pour l'expérience et **ne sont pas téléversées automatiquement** vers les serveurs de Spaarkly. Si l'expérience se déroule sur un appareil installé dans un point de vente, un showroom, le lieu d'un événement ou tout autre endroit ouvert au public et que l'Utilisateur choisit d'obtenir, de télécharger ou de partager les photos finales («Shoot & Share» ou fonctions équivalentes), **seules les photos finales sélectionnées par l'Utilisateur** sont téléversées temporairement vers les serveurs de Spaarkly, aux seules fins de les mettre à la disposition de l'Utilisateur, et sont supprimées au plus tard dans un délai de 24 heures (plus tôt, si l'Utilisateur les supprime).
<!-- /BLOCK shoot-share -->
{{/shoot_share_enabled}}

<!-- BLOCK privacy [CORE] -->
## Confidentialité

Pour les traitements de données à caractère personnel effectués par les fonctionnalités ARShades — y compris les points de repère faciaux traités **en temps réel et localement sur l'appareil** aux seules fins de positionner les lunettes virtuelles, sans conservation ni transmission — le **responsable du traitement est Spaarkly s.r.l.** : la [Politique de confidentialité ARShades](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/fr/) (contact : privacy@spaarkly.com), présentée avec les présentes Conditions, s'applique. Nous n'accédons ni aux données à caractère personnel traitées par les fonctionnalités ARShades ni au traitement correspondant : nous recevons de Spaarkly exclusivement des données agrégées et anonymisées ; c'est pourquoi Spaarkly demeure responsable du traitement pour les traitements ARShades.

Pour les traitements que nous effectuons en qualité de responsables — comptes, commandes, paiements, assistance, marketing et tout autre traitement lié à {{website_url}} — notre [politique de confidentialité]({{client_privacy_url}}) s'applique.
<!-- /BLOCK privacy -->

<!-- BLOCK venditore [CLIENT] -->
## Nos responsabilités en tant que vendeur

C'est nous — et non Spaarkly — qui sommes responsables des produits présentés et vendus sur {{website_url}} : prix, disponibilité, descriptions et déclarations relatives aux produits, conformité, livraison, garantie légale, retours et assistance, conformément à nos [Conditions générales]({{client_terms_url}}).{{#prescription_sales_enabled}} La délivrance de verres correcteurs s'effectue sous notre responsabilité, dans le respect de la réglementation applicable.{{/prescription_sales_enabled}} Les achats ou autres opérations éventuellement conclus par l'Utilisateur avec nous sont régis exclusivement par nos conditions.
<!-- /BLOCK venditore -->

<!-- BLOCK ip [CORE] -->
## Propriété intellectuelle

Les solutions ARShades — logiciels, algorithmes et interfaces — ainsi que les droits de propriété intellectuelle correspondants sont et demeurent la propriété de **Spaarkly ou de ses concédants de licence**. Les modèles 3D et les contenus affichés peuvent nous appartenir, appartenir à Spaarkly ou aux concédants de licence respectifs et sont fournis à des fins de visualisation uniquement. Il est notamment interdit de copier, de reproduire, d'extraire ou de collecter par scraping les modèles 3D et les contenus, de décompiler ou de soumettre à l'ingénierie inverse le logiciel (sauf dans les limites autorisées par des dispositions impératives) ainsi que tout usage commercial non autorisé des solutions ARShades.
<!-- /BLOCK ip -->

<!-- BLOCK minori [CLIENT] -->
## Mineurs

{{#minors_enabled}}Les fonctionnalités ARShades sont destinées à un public général : les Utilisateurs dont l'âge est inférieur à celui auquel ils peuvent valablement consentir aux services de la société de l'information dans leur pays de résidence (en Italie, 14 ans) ne peuvent les utiliser qu'avec le consentement ou l'autorisation d'un parent ou d'un tuteur légal, lorsque la loi applicable l'exige.{{/minors_enabled}}{{^minors_enabled}}L'expérience d'achat sur {{website_url}} est destinée aux utilisateurs majeurs.{{/minors_enabled}}
<!-- /BLOCK minori -->

<!-- BLOCK terzo-beneficiario [CORE] -->
## Spaarkly en qualité de tiers bénéficiaire

Les stipulations des présentes Conditions relatives à la technologie ARShades, à la nature de l'expérience virtuelle, à la propriété intellectuelle ainsi qu'aux exclusions et limitations qui y sont liées sont convenues, dans l'intérêt du Client, également au bénéfice de Spaarkly, en vertu de l'article 1411 du code civil italien, et Spaarkly peut les faire valoir directement à l'encontre de l'Utilisateur. La présente clause ne porte pas atteinte aux droits reconnus à l'Utilisateur par des dispositions impératives.
<!-- /BLOCK terzo-beneficiario -->

<!-- BLOCK rapporto-documenti [CORE] -->
## Articulation avec les autres documents

Les présentes Conditions s'appliquent à l'utilisation des fonctionnalités ARShades au sein de notre expérience. Les achats et toute autre relation commerciale avec nous demeurent régis par nos [Conditions générales]({{client_terms_url}}), qui régissent également la loi applicable et le tribunal compétent. Pour les traitements de données à caractère personnel dont Spaarkly est responsable, la [Politique de confidentialité ARShades](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/fr/) s'applique. Rien dans les présentes Conditions n'exclut, ne limite ni ne porte atteinte aux droits reconnus à l'Utilisateur par des dispositions impératives, y compris les droits des consommateurs.
<!-- /BLOCK rapporto-documenti -->

<!-- BLOCK contatti [CLIENT] -->
## Contact

Pour toute question relative à l'expérience d'achat : **{{support_email}}**.

Pour les questions relatives aux fonctionnalités ARShades : **legal@spaarkly.com** ; pour la confidentialité ARShades : **privacy@spaarkly.com**.
<!-- /BLOCK contatti -->

---

En cliquant sur «Accepter», ou en utilisant les fonctionnalités ARShades après avoir eu la possibilité d'en prendre connaissance, l'Utilisateur déclare avoir lu et compris les présentes Conditions et les accepter.
