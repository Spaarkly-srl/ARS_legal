# SITE WEB ARSHADES — POLITIQUE RELATIVE AUX COOKIES

*Site marketing ARShades* </br> *Version 1.0.1 — Dernière mise à jour : 23 juillet 2026 — Date d'entrée en vigueur : 22 juillet 2026*

La présente Politique relative aux cookies complète la [Politique de confidentialité du Site](../privacy-website/en.md) et décrit les cookies et technologies similaires (y compris le *localStorage*) utilisés par le **site marketing ARShades** de **Spaarkly s.r.l.** Elle concerne exclusivement le site web de présentation des solutions ARShades ; les cookies et technologies employés au sein des expériences de produit ARShades (par exemple le Virtual Try-On lancé par l'Utilisateur) sont décrits dans la Politique de confidentialité des solutions ARShades.

## 1. Que sont les cookies

Les cookies sont de petits fichiers texte qu'un site enregistre sur votre appareil. Des technologies similaires — comme le *localStorage* du navigateur — sauvegardent des informations de manière analogue. La réglementation européenne (directive ePrivacy, art. 122 du Code de la protection des données personnelles et RGPD) exige le consentement préalable pour tout cookie ou technologie similaire qui **n'est pas** strictement nécessaire au fonctionnement du site.

## 2. Catégories utilisées

- **Strictement nécessaires / techniques** — indispensables au fonctionnement du Site : votre choix concernant les cookies, les préférences de thème et de langue, ainsi que les cookies d'authentification de l'espace administratif réservé. Ils ne requièrent pas de consentement.
- **Analytics** — cookies de mesure de **Google Analytics 4**, utilisés exclusivement pour des statistiques agrégées d'utilisation du Site. **Ils ne sont installés que si vous activez la catégorie « Analytics » dans le bandeau.** L'analytics est configuré en mode respectueux de la vie privée : consentement refusé par défaut (Google Consent Mode v2), anonymisation de l'adresse IP activée, aucun Google Signals, aucune fonctionnalité publicitaire ou de remarketing, aucun profilage cross-site.
- **Fonctionnels** — technologies chargées **uniquement à votre demande explicite** (par exemple l'autocomplétion de l'adresse dans le formulaire d'inscription ou le lancement d'une démo interactive). Étant donné qu'elles ne s'activent qu'à la suite d'une de vos actions, elles ne figurent pas dans le bandeau initial mais sont décrites au §5.
- **Marketing** — catégorie prévue mais **actuellement non utilisée** : le Site n'installe aucun cookie publicitaire ni de profilage. En cas d'introduction, le bandeau et le tableau seront mis à jour et le consentement à nouveau demandé.

## 3. Base légale et consentement

Les cookies techniques reposent sur l'**intérêt légitime** (art. 6, par. 1, point f, RGPD) ; toutes les autres catégories reposent exclusivement sur votre **consentement** (art. 6, par. 1, point a, RGPD), recueilli au moyen du bandeau lors de la première visite, avec une mise en évidence équivalente entre « Tout accepter » et « Tout refuser ».

Votre choix — y compris le refus — est conservé pendant **12 mois** dans le cookie first-party `ars_consent`. Une preuve minimale du consentement (identifiant aléatoire, horodatage, version et langue de l'information affichée dans le bandeau, catégories et action — **sans adresse IP ni user-agent**) est enregistrée sur nos serveurs pendant le temps nécessaire à démontrer le consentement (jusqu'à **26 mois**) puis supprimée automatiquement. En cas de refus, un nouveau consentement ne vous sera pas demandé pendant au moins **6 mois**, sauf modifications substantielles de l'information.

## 4. Liste des cookies

<!-- cookie-table:start -->

| Nom | Fournisseur | Finalité | Durée | Catégorie |
|---|---|---|---|---|
| `ars_consent` | Spaarkly (first-party) | Mémorise votre choix de consentement aux cookies (catégories, version, date). | 12 mois | Strictement nécessaires |
| `NEXT_LOCALE` | Spaarkly (first-party) | Défini par le routage linguistique du site pour mémoriser la langue détectée/sélectionnée. | Session | Strictement nécessaires |
| `theme` | Spaarkly (first-party) | Mémorise votre préférence de thème clair/sombre. | Persistant (localStorage) | Strictement nécessaires |
| `_ga` | Google LLC (Google Analytics 4) | Google Analytics 4 — distingue les utilisateurs. | 2 ans | Analytique |
| `_ga_<container>` | Google LLC (Google Analytics 4) | Google Analytics 4 — conserve l'état de session. | 2 ans | Analytique |
| `__admin_session` | Spaarkly (first-party) | Authentification de l'espace d'administration réservé (pages admin uniquement). | 5 jours | Strictement nécessaires |
| `__admin_access` | Spaarkly (first-party) | Contrôle d'accès à l'espace d'administration réservé (pages admin uniquement). | 1 an | Strictement nécessaires |

<!-- cookie-table:end -->

Les cookies analytics (`_ga`, `_ga_<container>`) sont installés par Google uniquement après votre consentement ; ils sont supprimés lors de la révocation. Les données au niveau de l'utilisateur et de l'événement collectées par Google Analytics 4 sont conservées pendant un maximum de **14 mois** ; les rapports statistiques agrégés, qui ne contiennent pas de données personnelles, peuvent être conservés plus longtemps.

Outre les cookies listés, le Site utilise certains **services chargés uniquement à votre demande explicite** qui n'installent pas de cookies : ils sont décrits au §5.

## 5. Cookies et technologies de tiers

Le seul tiers susceptible d'installer des cookies de mesure sur ce Site est **Google LLC** (Google Analytics 4), et uniquement après votre consentement. Google LLC adhère à l'**EU–U.S. Data Privacy Framework** ; pour les détails relatifs aux transferts internationaux de données, voir la [Politique de confidentialité du Site](../privacy-website/en.md).

Certains **services chargés uniquement à votre demande explicite** n'installent ni ne persistent de cookies sur ce Site (ils ne figurent donc pas dans le tableau du §4, qui liste les cookies et les technologies de stockage) :

- **Démos interactives Virtual Try-On** servies par *webvto.it* (service Spaarkly) : l'embed ne se charge que lorsque vous cliquez pour lancer la démo et dure le temps de la session.
- **API Google Maps Places**, utilisée par le champ d'autocomplétion d'adresse du formulaire d'inscription : elle ne se charge que lorsque vous commencez à saisir dans ce champ. Pour ce service, Google agit en qualité de responsable du traitement autonome ; les détails figurent dans la [Politique de confidentialité du Site](../privacy-website/en.md).

L'espace administratif réservé et le formulaire d'inscription utilisent en outre **Firebase Authentication** (Google/Firebase) pour la gestion de l'accès : ce service mémorise des données techniques de session dans le navigateur (IndexedDB) à seule fin de maintenir l'authentification, sans finalité de traçage ni de profilage.

## 6. Gestion des préférences

- Utilisez le lien **« Préférences cookies »** présent dans le pied de page de chaque page pour revoir ou modifier vos choix à tout moment ; la révocation du consentement Analytics entraîne également la suppression des cookies `_ga*`.
- Vous pouvez par ailleurs supprimer ou bloquer les cookies depuis les paramètres du navigateur (cela peut avoir une incidence sur des fonctions techniques comme la persistance du thème et de la langue).

## 7. Mises à jour de la présente Politique relative aux cookies

Les modifications substantielles de la présente Politique (nouveaux cookies, nouvelles finalités, nouveaux tiers) entraînent une nouvelle demande de consentement au moyen du bandeau. La version de l'information que vous avez acceptée est enregistrée avec votre choix.

## 8. Contacts

Spaarkly s.r.l. — Via della Tecnica n. 18, 85100 Potenza (Italie) — privacy@spaarkly.com.

---

© Spaarkly s.r.l. Tous droits réservés.
