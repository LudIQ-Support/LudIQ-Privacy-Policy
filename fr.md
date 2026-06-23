# Politique de Confidentialité — Dicea

[🇬🇧 English Version](README.md)

| Métadonnées | Valeur |
| :--- | :--- |
| **Application** | Dicea |
| **Dernière mise à jour** | 20 juin 2026 |

---

## 1. Présentation

**Dicea** est une application mobile gratuite destinée aux joueurs de jeux de société. Elle a été conçue pour respecter la vie privée de ses utilisateurs et fonctionne principalement hors ligne.

* **Stockage local exclusif :** Vos données personnelles restent sur votre appareil. Votre collection de jeux, vos parties et vos scores, vos profils de joueurs (noms et photos) ainsi que vos préférences sont enregistrés localement, dans la mémoire de votre téléphone. Aucun serveur ne conserve de copie de ces informations.
* **Sans compte ni publicité :** L'utilisation de l'application ne nécessite ni création de compte, ni adresse e-mail. L'application ne contient aucune publicité, aucun traceur publicitaire et ne procède à aucune revente de données.
* **Flux réseau minimaux :** Les informations qui quittent votre appareil sont les requêtes techniques adressées à BoardGameGeek pour afficher les fiches de jeux, le téléchargement des images de jeux depuis le réseau de diffusion d'images de BoardGameGeek, et le texte des descriptions de jeux transmis à un service de traduction lorsque vous utilisez l'application en français. 

🔒 **Nuance importante (Contenu vs Métadonnées) :** Le contenu de ces requêtes ne comporte aucune des données que vous avez saisies dans l'application : ni votre nom, ni vos profils de joueurs, ni vos statistiques. Cependant, comme toute connexion à Internet, ces requêtes transmettent obligatoirement des données techniques de connexion, telles que votre **adresse IP**, qui peuvent constituer une donnée personnelle au sens du RGPD. Elles sont utilisées uniquement pour acheminer la requête par les infrastructures intermédiaires et ne servent ni à vous identifier personnellement ni à établir un profil.

---

## 2. Responsable du traitement

L'éditeur de l'application Dicea est responsable du traitement de vos données au sens du Règlement général sur la protection des données (RGPD).

> 📋 **Informations sur l'éditeur :**
> * **Éditeur :** GODINEAU Savinien
> * **Statut :** Développeur individuel
> * **Numéro d'identification :** Non applicable
> * **Adresse de contact :** Dicea.support@gmail.com

Pour toute question relative à la présente politique ou à la gestion de vos données, vous pouvez nous écrire directement à l'adresse e-mail indiquée ci-dessus.

---

## 3. Données concernées

Dicea agit comme un compagnon de jeu de table. Pour fonctionner, l'application traite des catégories de données bien précises, dont la très grande majorité ne quitte jamais votre terminal.

### 3.1. Données stockées localement sur votre appareil
Les données suivantes sont enregistrées exclusivement dans l'espace de stockage privé et cloisonné de l'application. Elles ne sont ni transmises à l'éditeur, ni accessibles par ce dernier ou par un tiers :
* **Votre collection de jeux :** Jeux possédés, autres jeux, liste d'envies, extensions et favoris.
* **Vos parties :** Sessions de jeu enregistrées, dates, durées, formats et joueurs présents.
* **Vos scores et statistiques :** Résultats détaillés par joueur, historique et bilans graphiques.
* **Profils de joueurs :** Les noms ou pseudonymes que vous saisissez manuellement et les photos ou avatars locaux que vous choisissez pour vos profils.
* **Vos préférences :** Langue de l'interface, réglages d'affichage, filtres et mémoire de l'onglet Explorer.

✏️ **Contrôle utilisateur :** Vous conservez le contrôle total de ces données. Vous pouvez les modifier ou les supprimer à tout moment directement dans l'application, ou les exporter vous-même au format **JSON**. La désinstallation de l'application efface définitivement et irréversible de toutes ces données de votre appareil.

### 3.2. Données échangées avec des services tiers
Certaines fonctionnalités connectées nécessitent une communication avec des services en ligne. Le détail rigoureux de ces échanges figure à l'**Article 5**.

---

## 4. Permissions de l'appareil

L'application peut vous demander l'accès à certaines fonctions de votre système. Cet accès est systématiquement déclenché par une action explicite de votre part et reste strictement cantonné à sa finalité.

| Permission | Usage dans Dicea | Transmission des données |
| :--- | :--- | :--- |
| **Photos & Appareil photo** | Permet de choisir un avatar pour un joueur ou pour votre profil. | L'image sélectionnée est copiée localement dans l'application. **Aucune photo n'est transmise à un serveur.** |
| **Enregistrement Galerie** | Permet de sauvegarder dans votre stockage une image de bilan partageable que vous générez vous-même. | L'image est créée localement sur le téléphone et enregistrée uniquement à votre demande expresse. |
| **Accès aux fichiers** | Permet d'exporter ou d'importer votre sauvegarde au format JSON via la fonction de partage native. | Vous choisissez vous-même le fichier concerné. L'application n'explore pas le reste de vos documents. |

*Vous pouvez refuser ou révoquer ces permissions à tout moment dans les réglages de votre système d'exploitation. Le cas échéant, les fonctionnalités correspondantes seront simplement indisponibles.*

---

## 5. Services tiers et destinataires des données

L'application s'appuie sur un nombre limité d'infrastructures pour fonctionner. Ce tableau détaille, pour chacune d'elles, la nature des flux, leur destinataire et leur finalité.

| Service / Prestataire | Données transmises | Finalité des flux | Prestataire & Politique |
| :--- | :--- | :--- | :--- |
| **BoardGameGeek (API)** | Termes de recherche et identifiants des jeux consultés. *(Zéro donnée utilisateur)*. Requête via proxy Cloudflare. | Récupérer en temps réel les fiches techniques des jeux (nom, note, description, classements). | BoardGameGeek<br>🔗 [Politique de confidentialité](https://boardgamegeek.com/privacy) |
| **Réseau d'images BGG** | Requête HTTP directe vers le domaine `geekdo-images.com`. Expose votre **adresse IP** et les visuels consultés. | Télécharger en direct sur votre écran les couvertures et vignettes des jeux de société. | Geekdo, LLC (États-Unis)<br>*(Flux direct sans passer par le proxy de l'éditeur)* |
| **Catalogue de jeux** | Requêtes de lecture seule sur les classements publics (top 10000 BGG). *(Zéro donnée utilisateur)*. | Alimenter la fonctionnalité de découverte et de suggestions au sein de l'onglet **Explorer**. | Opéré par l'éditeur<br>*(Base hébergée chez Supabase, requêtes via Cloudflare)* |
| **Service de traduction** | Texte brut de la description du jeu (en anglais). *(Zéro donnée utilisateur. Flux inactif si l'app est en anglais)*. | Traduction automatique instantanée des descriptions de fiches de jeux en français. | DeepL API<br>🔗 [Politique de confidentialité](https://www.deepl.com/privacy) |
| **Hébergement technique** | Métadonnées de connexion standard (adresse IP notamment) nécessaires à l'acheminement du trafic. | Routage sécurisé (HTTPS) des requêtes de l'application et mise en cache de performance des données publiques. | Cloudflare Workers<br>🔗 [Politique de confidentialité](https://www.cloudflare.com/privacypolicy/) |

### 🔒 Garantie d'absence de pistage
Pour être parfaitement complet, l'application Dicea n'utilise aucun outil de mesure d'audience, aucun outil de pistage comportemental, aucun outil tiers de rapport de plantage (comme Firebase Crashlytics), aucun service de la suite Google Firebase, et aucune publicité.

### 5.5. Protection assurée par les tiers
Nous ne faisons appel qu'à des prestataires présentant des garanties appropriées en matière de protection des données. Lorsque des informations techniques ou des métadonnées de connexion transitent vers l'un de ces tiers, celui-ci est tenu de leur assurer un niveau de protection équivalent à celui décrit dans la présente politique et conforme aux obligations légales applicables.

---

## 6. Bases légales des traitements

Conformément à l'**Article 6 du RGPD**, les traitements mis en œuvre reposent sur les bases légales suivantes :
1. **Exécution du service / Contrat :** Le stockage local de votre collection, de vos parties, de vos profils de joueurs et de vos préférences est nécessaire pour vous fournir le service et les fonctionnalités que vous activez.
2. **Intérêt légitime :** L'affichage des informations de jeux (incluant le téléchargement direct des images), l'interrogation du catalogue Explorer et la traduction automatisée répondent à notre intérêt légitime à vous offrir un confort de lecture et une expérience fluide, enrichie et localisée.
3. **Consentement :** L'accès aux fonctionnalités matérielles de l'appareil (photos, appareil photo, galerie) repose exclusivement sur votre consentement, donné via la demande de permission native du système lors de l'action que vous initiez.

---

## 7. Transferts hors de l'Union européenne

Selon les prestataires d'infrastructure utilisés, certaines des données de connexion techniques décrites à l'Article 5 (notamment l'adresse IP et les requêtes techniques de routage) sont traitées en dehors de l'Espace économique européen, en particulier aux États-Unis par les sociétés **Cloudflare, Inc.** et **Geekdo, LLC**.

Ces transferts portent exclusivement sur ces métadonnées techniques indispensables à l'acheminement des flux, à l'exclusion stricte de toute donnée saisie par l'utilisateur. Ils sont rigoureusement encadrés par des garanties appropriées au sens du RGPD, notamment les **Clauses Contractuelles Types (CCT)** adoptées par la Commission européenne ainsi que les mécanismes de conformité propres à ces prestataires.

---

## 8. Durée de conservation

* **Données locales :** Les données décrites à l'Article 3.1 restent stockées sur votre appareil tant que vous ne les supprimez pas manuellement et que l'application reste installée. Elles sont définitivement effacées lors de la désinstallation de Dicea.
* **Requêtes réseau :** Les requêtes techniques adressées à BoardGameGeek, au réseau d'images, au catalogue, au service de traduction et aux proxies intermédiaires sont éphémères et ne sont rattachées à aucun profil utilisateur. Les caches de données publiques relatives aux jeux sont temporaires.

---

## 9. Vos droits

Conformément au RGPD, vous disposez d'un droit d'accès, de rectification, d'effacement, de limitation, d'opposition et de portabilité concernant vos données.

En raison de l'architecture décentralisée ("local-first") de Dicea, **vous pouvez exercer l'immense majorité de ces droits de manière totalement autonome**, sans notre intervention :
* **Accès & Portabilité :** Vous pouvez consulter toutes vos données directement dans les écrans de l'application et les exporter au format JSON à tout moment.
* **Rectification :** Vous pouvez modifier manuellement vos jeux, vos sessions de parties, vos scores et vos profils de joueurs directement dans les réglages.
* **Effacement :** Vous pouvez supprimer un élément un par un, réinitialiser la mémoire locale de l'onglet Explorer, ou désinstaller l'application pour purger instantanément l'intégralité des enregistrements de votre terminal.

Vous pouvez à tout moment **retirer un consentement** que vous avez précédemment accordé, par exemple en révoquant une permission dans les réglages système de votre appareil, ce qui rendra simplement les fonctionnalités associées indisponibles. Pour toute demande d'exercice de droit nécessitant une action de notre part, vous pouvez nous contacter à l'adresse **Dicea.support@gmail.com**. Nous vous répondrons dans le délai légal d'un mois.

Vous disposez également du droit d'introduire une réclamation auprès de l'autorité de contrôle compétente. En France, il s'agit de la **CNIL** (Commission nationale de l'informatique et des libertés) via son site [www.cnil.fr](https://www.cnil.fr).

---

## 10. Sécurité

Vos données locales bénéficient des mécanismes de sécurité natifs du système d'exploitation de votre appareil, notamment le cloisonnement des applications (sandbox) et, si vous l'avez activé, le chiffrement matériel de l'appareil. Les échanges réseau décrits à l'Article 5 s'effectuent exclusivement au moyen de connexions chiffrées de bout en bout (**HTTPS**).

*Conseil : Aucun système n'étant infaillible, nous vous recommandons vivement de sécuriser l'accès à votre téléphone (code de verrouillage, schéma ou authentification biométrique) et d'effectuer des exports JSON réguliers si vos statistiques vous sont précieuses.*

---

## 11. Protection des mineurs

Dicea est une application tout public. Elle n'est pas destinée spécifiquement aux enfants et ne collectera jamais sciemment de données personnelles les concernant. Si vous estimez qu'un enfant nous a communiqué des données par e-mail, nous vous invitons à nous contacter pour que nous procédions à leur suppression.

Les noms et avatars de joueurs que vous saisissez peuvent concerner des tiers (famille, amis, y compris des enfants). Ces informations **demeurent uniquement sur votre appareil**. En les saisissant, vous vous engagez à n'enregistrer que des informations que vous êtes légalement en droit de renseigner localement.

---

## 12. Modifications de la politique

La présente politique de confidentialité peut être mise à jour afin de refléter une évolution de l'application ou des réglementations applicables. Toute évolution de cette nature fera l'objet d'une révision du présent document en amont de son entrée en vigueur. En cas de modification importante, nous l'indiquerons au sein de l'application ou sur la page d'hébergement web du document. La date de dernière mise à jour figurant en tête fait foi.

---

## 13. Contact

Pour toute question relative à la présente politique ou à vos données :

* **Adresse e-mail :** Dicea.support@gmail.com
* **Éditeur :** GODINEAU Savinien
* **URL du document :** https://Dicea-support.github.io/Dicea-Privacy-Policy/
