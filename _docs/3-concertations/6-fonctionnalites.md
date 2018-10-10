---
title: 3.6 Configurer les fonctionnalités d'une concertation
category: 3. Concertations
order: 7
---

Les fonctionnalités sont les modules de participation que vous pous pouvez activer sur chacun des processus. Il existe 9 modules participatifs. Vous pouvez en activer autant que vous le souhaitez (et même plusieurs du même type sur un seul processus participatif). Ils sont tous configurables individuellement.


> Pour configurer les fonctionnalités, cliquez sur **"Fonctionnalités"** dans le sous-menu de la concertation. Une liste apparait montrant les fonctionnalités déjà activées. Les icônes de chaque fonctionnalité permettent de suivre les actions suivantes : gérer, publier/dépublier, configurer, gérer les permissions, détruire.

> Pour ajouter une fonctionnalité, cliquez sur **“Ajouter une fonctionnalité”**.

> La plupart des fonctionnalités se configurent à deux niveaux :
- Au niveau général : cette configuration s'appliquera à n'importe quelle étape de la concertation.
- Par étape : cette configuration ne s'appliquera que lorsque cette étape est activée. C'est le cas des **messages d'annonces. Les annonces par étapes viendront se substituer à l’annonce générale quand l’étape est active.**


___

#### Cliquez sur le titre de la fonctionnalité pour accéder à son mode d'emploi :

**[Rencontres](#rencontres)** : Agenda de rencontres publiques. Seuls les administrateurs du processus participatif peuvent créer des rencontres. Les rencontres peuvent être associées à des catégories.

**[Propositions](#propositions)** : Selon la configuration, espace ouvert aux propositions des utilisateurs et/ou espace de consultation pour l’institution.

**[Budget](#budget)** : Pour paramétrer la mise en place d’un budget participatif avec un dépôt et un vote de propositions par les utilisateurs dans le cadre d’enveloppes budgétaires définies par l'institution.

**[Enquête](#enquete)** : Réalisation d'enquêtes à l’aide de formulaires web complètement personnalisables. 5 options de champs : réponse courte, réponse longue, choix unique, choix multiples et tri parmi des options.

**[Page](#page)** : Page statique, qui est utile pour mettre à disposition des informations complémentaires sur la concertation ou son objet. Il est possible d'ajouter un espace de commentaire.

**[Suivi](#suivi)** : Pour communiquer les résultats de la concertation et l'avancée des réalisations. Seuls les administrateurs peuvent en publier. Ils peuvent les associer à des catégories et lier des propositions qui ont émergé pendant le processus.

**[Débats](#débats)** : Pour conduire des débats libres initiés par l'administrateur et/ou par les citoyens à travers un fil de commentaire.

**[Tirage au sort](#tirage-au-sort)** : Pour tirer au sort de manière aléatoire une ou des propositions parmi d'autres.

**[Actualités](#actualités)** : Pour éditer des articles sous un format "blog de la concertation".



### Rencontres

Pour ajouter des rencontres, vous devez d'abord configurer le module "Rencontres". Pour cela, vous devez l'ajouter depuis le sous-menu "Fonctionnalités". L'écran de configuration du module "Rencontres" s'ouvre :

![config-rencontres]({{site.baseurl}}/uploads/3-6-4-back-config-rencontres.png)

Vous devez renseigner un titre, un rang d'affichage dans la barre de navigation, une annonce globale et par étape (facultatif), cocher "Activer le module commentaire" si vous souhaitez laisser les utilisateurs commenter les rencontres, et ensuite cocher "Bloquer les commentaires" si vous souhaitez empêcher les utilisateurs de continuer à commenter les rencontres (les commentaires laissés précédemment restent visibles).

Une fois que le module "Rencontres" a été configuré, vous pouvez créer des rencontres.
Pour cela, cliquez sur le module "Rencontres" dans le sous-menu à gauche.
Les icônes du tableau de bord des rencontres permettent d'effectuer les actions suivantes :

![config-rencontres]({{site.baseurl}}/uploads/3-6-5-dashboard-rencontre.png)

Pour créer une rencontre, cliquez sur "Nouvelle" puis l'écran de configuration d'une rencontre s'ouvre :

![config-rencontres]({{site.baseurl}}/uploads/3-6-6-back-creation-rencontre.png)

Les champs à renseigner sont :
- **Titre***
- **Description***
- **Adresse*** : numéro, nom de rue, code postal et ville (⚠️ il faut strictement respecter ce format). Les adresses sont ensuite géocodées via le service here.com qui utilise les fonds de cartes founis par Open Street Map.
- **Lieu** : nom du bâtiment, de la salle de réunion, etc.
- **Données de localisation** : Si besoin, des informations sur comment accéder à la salle (par exemple, "Utiliser l'accès sud"), etc.
- **Heure de début et heure de fin**.
- **Catégorie**, si pertinent (exemple : une rencontre limitée aux projets liés aux écoles dans un budget participatif généraliste).

*Visualisez la rencontre [ici](https://demo.decidim.opensourcepolitics.eu/processes/modules-decidim/f/3/meetings/1)*

Pour activer une rencontre, vous devez vous rendre sur le tableau de bord des rencontres, cliquer sur l'icône **"Inscriptions"**, cocher **"Activer les inscriptions"**, renseigner le nombre de places disponibles (laisser à 0 pour un nombre illimité de places), le nombre de places réservées (pré-réservation, entrée sur place sans réservation, etc.) et indiquer les **"Conditions d'inscription"** (par exemple, "Entrée libre").

![config-rencontres]({{site.baseurl}}/uploads/3-6-9-back-config-inscription.png)

Sur cette fenêtre, via le menu "Exporter", il est également possible d'exporter la liste des inscriptions aux formats CSV, JSON ou EXCEL.

### Propositions

Pour configurer un module "Proposition", vous devez aller dans le sous-menu des fonctionnalités et cliquer sur "Ajouter une fonctionalité". Nous vous montrons la correspondance entre les éléments à renseigner dans l'écran de configuration et la page accessible au public (nous consulter pour plus de détails) :

![config-propositions]({{site.baseurl}}/uploads/3-6-1-back-config-prop.png)

![config-propositions]({{site.baseurl}}/uploads/3-6-2-front-config-prop.png)

Pour gérer les propositions - c'est-à-dire pour accepter/rejeter des propositions, cliquez sur le module "Proposition" dans le sous-menu de gauche. Les trois actions possibles sont "Notes privées" (des notes qui ne sont visibles que par les administrateurs), "Répondre" (attribuer un statut à la proposition et expliquer pourquoi elle est acceptée ou non) et "Visualiser" (voir [7.3 Evaluer des propositions]({{site.baseurl}}/7-animation-plateforme/3-evaluation-propositions) pour des compléments).

Vous pouvez exporter les propositions aux formats CSV, JSON, EXCEL en cliquant sur "Exporter".

Il est également possible de faire des propositions officielles en cliquant sur "Nouvelle proposition".
Vous pouvez enfin importer des propositions d'un autre module proposition dans celui-ci en cliquant sur "Importer depuis une autre fonctionnalité". Un double de la proposition importée sera créée, sans les commentaires/votes de la proposition originale, et restera lié à la proposition originale.

![config-propositions]({{site.baseurl}}/uploads/3-6-3-back-gestion-prop.png)

### Budget

*Nous préparons une notice détaillée pour la mise en place d'un budget participatif sur Decidim (nous consulter).*

### Enquête

⚠️ Vous devez commencer par configurer le module "Enquête" en indiquant à quelle(s) étape(s) l'utilisateur peut répondre à l'enquête.
Pour configurer l'enquête en elle-même, cliquez sur "Enquête" dans la barre des fonctionnalités sur la gauche ou sur l'icône "Crayon" dans le tableau de bord du module "Enquête".

Il n'est possible de configurer qu'une enquête par module "Enquête" et toutes les questions se suivent sur une seule page. Plusieurs types de questions sont accessibles. Vous pouvez définir pour chaque question s'il est obligatoire d'y répondre ou non.
- **Option unique** : il faut indiquer plusieurs options de réponse ; l'utilisateur ne peut choisir qu'une seule réponse.
- **Option multiple** : il faut indiquer plusieurs options de réponse ; l'utilisateur peut choisir plusieurs réponses ; vous pouvez configurer le nombre de réponse maximum. Vous pouvez également configurer des champs qui resteront libres et que l'utilisateur devra remplir.
- **Réponse courte** : champ de texte court.
- **Réponse longue** : champ de texte long.
- **Tri** : il faut indiquer plusieurs choix ; l'utilisateur devra les classer dans l'ordre souhaité.

⚠️ **Il est impossible de modifier une enquête dès qu'elle a reçu au moins une réponse (y compris la vôtre en phase de test).**

![config-enquete]({{site.baseurl}}/uploads/3-6-7-back-config-enquete.png)


### Page

Vous pouvez éditer des pages qui renseignent l'utilisateur sur la concertation en cours, les méthodes de participation, les objectifs, etc. Pour ajouter une page, cliquer sur "Ajouter une fonctionnalité" dans le menu des fonctionnalités. Vous n'avez accès qu'à un champ de texte classique.

![config-page]({{site.baseurl}}/uploads/3-6-8-back-config-page.png)

### Suivi

Le module "Suivi" permet aux utilisateurs de suivre l'avancement des réalisations (à l'échelle globale, par catégorie et/ou par sous-catégorie) de l'action liée à une concertation. Cette action correspond aux propositions dont la réalisation a été décidée suite à la médiation opérée à travers Decidim, soit directement (via un vote), soit indirectement (via des rencontres, des assemblées ou l'intervention des équipes politiques et techniques).

Les réalisations peuvent être transformées en projets ou décomposées en sous-projets, qui décrivent avec plus de détail la mise en oeuvre, et pour lesquels un statut d'exécution peut être défini.
Vous pouvez définir plusieurs statuts pour vos résultats qui permettront de rendre compte de l’état d’avancement. Le  nom ne sera visible que dans la partie administrateur, il vous permet de l’intégrer dans certaines étapes. À l’inverse, la  description est le texte qui sera visible par les utilisateurs. Vous avez la possibilité de réaliser deux sortes d’actions : modifier ou supprimer.
Vous pouvez associer vos résultats à des catégories et des propositions qui les ont inspirés.

Pour sélectionner plusieurs propositions :
- sous Windows ou Linux : Ctrl + clic gauche
- sous Mac : Cmd + clic

Pour réaliser une frise chronologique, vous devez cliquer sur l'icône 'horloge'. Ainsi vous voyez apparaître une fenêtre qui affiche les étapes déjà en cours si elles ont été créées. Pour ajouter une nouvelle étape dans la chronologie cliquez sur **[Nouveau élément de chronologie]**.

Les réalisations, projets et états peuvent être mis à jour manuellement par un fichier CSV via l'interface d'administration.

Pour configurer le module "Suivi", cliquer sur "Ajouter une fonctionnalité", sélectionner "Suivi" pour ouvrir le menu de configuration du module :

Pour ajouter un nouveau résultat, cliquez sur "Nouveau résultat" dans le tableau de bord du module "Suivi".

### Débats

Vous devez d'abord créer et configurer un module "Débats" en indiquant à quelle(s) étape(s) l'utilisateur peut créer un débat et/ou commenter (= participer) les débats.

Pour créer un débat d'origine officielle, cliquer sur la fonctionnalité "Débats" dans la barre des fonctionnalités sur la gauche ou sur l'icône "Crayon" dans le tableau de bord du module "Débats", puis cliquez sur "Nouveau débat".

![creer-debat]({{site.baseurl}}/uploads/3-6-10-creer-debat.png)

Vous pouvez choisir dans les options de configuration si les utilisateurs de la plateforme ont aussi la possibilité de créer leurs propres débats ou simplement de participer aux débats officiels.

### Tirage au sort

La fonctionnalité "Tirage au sort" vous permet de sélectionner de manière aléatoire un certain nombre de propositions depuis un groupe de propositions. Pour configurer un module "Tirage au sort", vous devez aller dans le sous-menu des fonctionnalités et cliquer sur "Ajouter une fonctionalité". L'écran de configuration du module "Tirage au sort" s'ouvre :

![ajouter_tirage_au_sort]({{site.baseurl}}/uploads/3-6-12-ajouter_tirage_au_sort.png)

Vous devez renseigner un titre, un rang d’affichage dans la barre de navigation et vous pouvez activer les commentaires sur le module.

Une fois que le module “Tirage au sort” a été configuré, vous pouvez effectuer un tirage sort des propositions. Pour cela, cliquez sur le module “Tirage au sort” dans le sous-menu à gauche. N'oubliez pas de publier le module afin que celui-ci apparaisse dans les étapes de la concertation.

Pour effectuer un tirage au sort, cliquez sur “NOUVEAU TIRAGE AU SORT” puis l’écran de configuration s’ouvre :

![nouveau_tirage]({{site.baseurl}}/uploads/3-6-13-nouveau_tirage.png)

![effectuer_tirage]({{site.baseurl}}/uploads/3-6-14-effectuer_tirage.png)

Les champs à renseigner et à sélectionner sont :
- **Titre***
- **Ensemble de propositions*** : groupe de propositions au sein duquel vous souhaitez tirer au sort des propositions.
- **Catégories des propositions sur lesquelles vous souhaitez appliquer le tirage au sort*** :
- **Nombre de propositions à sélectionner*** : indiquez le nombre de propositions que vous voulez tirer au sort parmi celles du groupe de propositions que vous avez choisi précédemment.
- **Témoins*** :
- **Information sur le tirage au sort**
- **Résultat de votre tirage au dé.*** : tirez au sort un nombre de 1 à 6, soit à l'aide d'un dé à 6 faces soit par tout autre moyen, et entrez ici le nombre obtenu devant témoin(s). Cette procédure contribue à garantir la sincérité et le caractère aléatoire du résultat.

Une fois les champs renseignés et sélectionnés, cliquez sur "Créer". Une boîte de dialogue s'ouvrira pour confirmer l'exécution du tirage au sort. Effectuer un tirage au sort est irréversible et le résultat est automatiquement publié au sein de votre concertation.

![bd_tirage]({{site.baseurl}}/uploads/3-6-15-bd_tirage.png)

Une fois confirmé, le résultat apparaît dans l'interface d'administrateur ainsi que dans la concertation concernée.

![tirage_admin]({{site.baseurl}}/uploads/3-6-16-tirage_admin.png)
![tirage_publie]({{site.baseurl}}/uploads/3-6-17-tirage_publie.png)


### Actualités

La fonctionnalité "Actualités" permet de créer des articles mettant en lumière des derniers développements de la plateforme, actualités de la concertation, etc.
Les articles les plus commentés sont mis en avant sur la plateforme.

Vous devez d'abord créer un module "Actualités" et le configurer en autorisant ou non les commentaires des utilisateurs.

Pour créer un article, cliquez sur le module "Actualités" dans le menu de gauche et renseignez le contenu grâce à l'éditeur de texte.

![creer-debat]({{site.baseurl}}/uploads/3-6-11-creer-debat.png)

--

*Suite : [Rassembler un groupe de concertations]({{site.baseurl}}/3-concertations/7-groupes-concertations/)*

