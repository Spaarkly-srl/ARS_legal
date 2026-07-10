---
published: false
---

# CONDITIONS GÉNÉRALES D'UTILISATION — AR PD METER

*{{client_trade_name}} — {{website_url}}* </br> *Conditions de {{client_legal_name}}, présentées avant la mesure — générées à partir du modèle Spaarkly «Client ARShades Integration Terms — AR PD Meter» v{{template_version}} du {{generated_date}}*

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
## Qui fournit quoi

**«{{client_trade_name}}»**, **«nous»** ou **«notre»** désigne {{client_legal_name}}, dont le siège est situé à {{client_registered_office}} ({{client_country}}), {{client_vat}}, qui exploite {{website_url}} et propose l'expérience commerciale.

**«Spaarkly»** désigne Spaarkly s.r.l. (P. IVA IT02077620769), qui développe et fournit **AR PD Meter**, la fonctionnalité ARShades décrite ci-après, et est **responsable du traitement** des données à caractère personnel traitées par cette fonctionnalité. Spaarkly n'est pas le vendeur des produits présentés, n'exploite pas de marketplace et n'est ni un opticien, ni un optométriste, ni un autre professionnel qualifié de la vision.

Les présentes conditions («Conditions AR PD Meter») sont présentées à l'Utilisateur, avec la [Politique de confidentialité ARShades](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/fr/), avant le lancement de la mesure. En cochant la case d'acceptation, l'Utilisateur les accepte et donne son consentement exprès au traitement décrit ci-dessous ; à défaut d'acceptation, la mesure n'est pas lancée. L'Utilisateur peut révoquer son consentement à tout moment en interrompant la mesure ou en révoquant l'accès à la caméra ; la révocation ne porte pas atteinte aux traitements déjà effectués.
<!-- /BLOCK ruoli -->

<!-- BLOCK cos-e [CORE] -->
## Qu'est-ce qu'AR PD Meter

**AR PD Meter** fournit une **estimation de la distance pupillaire (PD)** de l'Utilisateur au moyen de la caméra de l'appareil et de la détection des points de repère faciaux. Il constitue une **estimation numérique préliminaire**, proposée en appui de la sélection des lunettes pendant l'expérience d'achat : **il n'est pas un dispositif médical**, il n'a pas de finalité médicale, clinique ou diagnostique et **ne remplace pas une mesure effectuée par un professionnel qualifié de la vision** (tel qu'un opticien, un optométriste ou un médecin ophtalmologiste). L'exactitude peut être influencée par l'éclairage, la qualité de la caméra, la distance, l'angle, la position du visage et les mouvements.
<!-- /BLOCK cos-e -->

<!-- BLOCK consenso-dati [CORE] -->
## Consentement et traitement des données

Le lancement de la mesure requiert le **consentement exprès de l'Utilisateur, donné à Spaarkly** en qualité de responsable du traitement, au moyen de la case d'acceptation présentée avant la mesure. Le parcours de consentement indique la version et la date des présentes Conditions AR PD Meter en vigueur et récapitule les données traitées, la finalité, la conservation et les modalités de révocation.

Le consentement est géré sous forme de **gating local in-experience** : la mesure ne se lance qu'après le consentement explicite et la révocation est toujours disponible, avec interruption immédiate du traitement en cours. Étant donné que Spaarkly n'identifie pas l'Utilisateur final, **aucune preuve du consentement rattachable à l'Utilisateur n'est conservée** : le lancement même de la mesure, subordonné au consentement, en constitue la preuve.

Les images de la caméra sont traitées sur l'appareil de l'Utilisateur et **ne sont ni transmises à Spaarkly ni conservées par Spaarkly**. Seules des données techniques dérivées (coordonnées des points de repère faciaux, données d'orientation du visage, informations sur l'appareil) — non utilisées pour identifier l'Utilisateur et insusceptibles, à elles seules, de l'identifier — sont transmises, chiffrées, au backend de Spaarkly dans l'**Union européenne**, utilisées exclusivement pour calculer et restituer la mesure et **définitivement supprimées immédiatement après le traitement**.{{#mirror_enabled}} Lorsque la mesure est effectuée sur un appareil **Mirror** dans nos points de vente ou showrooms, le traitement s'effectue sur le backend local de l'appareil, sans aucune transmission vers des serveurs cloud.{{/mirror_enabled}}

Lorsque les lois applicables en matière de confidentialité biométrique l'exigent, l'acceptation affirmative de l'Utilisateur constitue le consentement écrit / l'autorisation écrite au traitement décrit, donné avant toute capture. Les détails complets figurent dans la [Politique de confidentialité ARShades](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/fr/), dont Spaarkly est responsable.
<!-- /BLOCK consenso-dati -->

<!-- BLOCK eta [CORE] -->
## Âge

AR PD Meter est destiné aux utilisateurs âgés d'**au moins 18 ans**. L'Utilisateur de moins de 18 ans ne peut l'utiliser qu'avec le consentement et sous la supervision d'un parent ou d'un tuteur légal.
<!-- /BLOCK eta -->

<!-- BLOCK uso-vendita [CLIENT] -->
## Utilisation dans notre processus de vente

{{#prescription_sales_enabled}}L'estimation AR PD Meter ne constitue pour nous qu'une **donnée préliminaire d'appoint** et **n'est jamais utilisée comme mesure définitive** pour la fourniture de verres correcteurs : avant la réalisation de lunettes de vue, la distance pupillaire et les autres paramètres nécessaires sont vérifiés ou confirmés par un professionnel qualifié de la vision, conformément à notre processus de vente et à la réglementation applicable. La responsabilité de cette vérification nous incombe, et non à Spaarkly.{{/prescription_sales_enabled}}{{^prescription_sales_enabled}}Nous ne vendons pas de verres correcteurs par l'intermédiaire de {{website_url}} : l'estimation AR PD Meter est utilisée exclusivement comme aide à la sélection de montures et de lunettes non correctrices.{{/prescription_sales_enabled}}
<!-- /BLOCK uso-vendita -->

<!-- BLOCK privacy [CORE] -->
## Confidentialité

Pour le traitement effectué par AR PD Meter — décrit ci-dessus — le **responsable du traitement est Spaarkly s.r.l.** : la [Politique de confidentialité ARShades](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/fr/) (contact : privacy@spaarkly.com), présentée avec les présentes Conditions AR PD Meter, s'applique. Nous n'accédons ni aux données traitées par AR PD Meter ni au traitement correspondant : nous recevons de Spaarkly exclusivement des données agrégées et anonymisées ; c'est pourquoi Spaarkly demeure responsable du traitement.

Pour les traitements que nous effectuons en qualité de responsables — comptes, commandes, assistance et tout autre traitement lié à {{website_url}} — notre [politique de confidentialité]({{client_privacy_url}}) s'applique.
<!-- /BLOCK privacy -->

<!-- BLOCK ip [CORE] -->
## Propriété intellectuelle

AR PD Meter — logiciel, algorithmes et interfaces — ainsi que les droits de propriété intellectuelle correspondants sont et demeurent la propriété de **Spaarkly ou de ses concédants de licence**. Aucun droit de propriété n'est transféré à l'Utilisateur ; l'ingénierie inverse (sauf dans les limites autorisées par des dispositions impératives) et tout usage non autorisé de la fonctionnalité sont interdits.
<!-- /BLOCK ip -->

<!-- BLOCK terzo-beneficiario [CORE] -->
## Spaarkly en qualité de tiers bénéficiaire

Les stipulations des présentes Conditions AR PD Meter relatives à la technologie, à la nature de l'estimation, au traitement des données, à la propriété intellectuelle ainsi qu'aux exclusions et limitations qui y sont liées sont convenues, dans l'intérêt du Client, également au bénéfice de Spaarkly, en vertu de l'article 1411 du code civil italien, et Spaarkly peut les faire valoir directement à l'encontre de l'Utilisateur. La présente clause ne porte pas atteinte aux droits reconnus à l'Utilisateur par des dispositions impératives.
<!-- /BLOCK terzo-beneficiario -->

<!-- BLOCK rapporto-documenti [CORE] -->
## Articulation avec les autres documents

Les présentes Conditions AR PD Meter s'appliquent exclusivement à l'utilisation de la fonctionnalité AR PD Meter. Les achats et toute autre relation commerciale avec nous demeurent régis par nos [Conditions générales]({{client_terms_url}}), qui régissent également la loi applicable et le tribunal compétent. Pour le traitement de données à caractère personnel dont Spaarkly est responsable, la [Politique de confidentialité ARShades](https://spaarkly-srl.github.io/ARS_legal/privacy-policy/fr/) s'applique. Rien dans les présentes Conditions AR PD Meter n'exclut, ne limite ni ne porte atteinte aux droits reconnus à l'Utilisateur par des dispositions impératives, y compris les droits des consommateurs.
<!-- /BLOCK rapporto-documenti -->

<!-- BLOCK contatti [CLIENT] -->
## Contact

Pour toute question relative à l'expérience d'achat : **{{support_email}}**.

Pour les questions relatives à AR PD Meter : **legal@spaarkly.com** ; pour la confidentialité ARShades : **privacy@spaarkly.com**.
<!-- /BLOCK contatti -->

---

En cochant la case d'acceptation ou en utilisant AR PD Meter, l'Utilisateur déclare avoir lu et compris les présentes Conditions AR PD Meter, les accepte et donne son consentement exprès au traitement décrit.
