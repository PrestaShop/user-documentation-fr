# Généralités et cas particuliers

## Échange de données entre boutique

### Partager les produits et les catégories

Lorsque vous créez une nouvelle boutique au sein d'un groupe, vous pouvez faire en sorte que toutes ou une partie des catégories dans la nouvelle boutique soient des copies exactes des catégories d'une autre boutique de votre installation de PrestaShop.

Lors de la création d'une catégorie, soit pour une boutique précise ou pour toutes les boutiques de votre installation de PrestaShop, PrestaShop enregistre la catégorie pour toutes les boutiques – elle est simplement cachée des boutiques pour lesquelles elle n'a pas été configurée.

En associant les nouvelles boutiques à une catégorie donnée, chaque modification dans cette catégorie aura une répercussion sur toutes les boutiques auxquelles elle a été associée, même si les boutiques viennent de différents groupes de boutiques. Vous pouvez donc changer le contenu de la catégorie une fois pour toutes les boutiques, y compris pour ses produits.

### Partager les clients et les groupes de clients

Comme indiqué ci-dessus, les boutiques au sein d'un même groupe de boutiques peuvent partager leurs clients : vous devez simplement régler la bonne option lors de la création du groupe de boutiques.

Les groupes sont moins détaillés : si vous changez l'un des groupes de clients par défaut dans une boutique, la modification sera appliquée à toutes les autres boutiques, quels que soient leurs groupes de boutiques.

Si vous souhaitez avoir un groupe de clients différent pour chaque boutique, vous devez créer un nouveau groupe et utiliser le sélecteur "Configuration multiboutique pour" pour associer le groupe à la boutique actuelle ou au groupe de boutiques actuel.

### Partager les commandes

&#x20;Il est possible pour les boutiques d'un même groupe de partager des commandes : il suffit de définir l'option appropriée lors de la création du groupe de boutiques. Si l'option "Partager les commandes" a été désactivée, votre liste de commandes devra être vide avant que vous puissiez l'activer. Si vous préférez conserver vos commandes, vous pouvez procéder comme suit :&#x20;

* Allez dans votre logiciel de gestion de base de données tel que phpMyAdmin.&#x20;
* Recherchez la table ps\_order. Elle peut être différente, selon le préfixe de votre base de données.&#x20;
* Exportez cette table.&#x20;
* Videz la table. Ne la déposez PAS. Si vous souhaitez la supprimer, veillez à recréer la table par la suite.&#x20;
* Retournez dans les paramètres multi-magasins pour le groupe de magasins.&#x20;
* Activez l'option "Partager les commandes".&#x20;
* Importez la table.&#x20;

Le partage des commandes entre le groupe de boutiques est maintenant activé sans perte d'informations sur les commandes.

### Utiliser un thème différent pour chaque boutique ou groupe de boutiques

Une fois que le thème a été installé sur votre PrestaShop, vous pouvez utiliser la page "Thème & Logo" du menu "Apparence" pour modifier le thème de la boutique actuelle, ou du groupe de boutiques actuel, en fonction de la manière dont le sélecteur "Configuration multiboutique pour" est réglé.

### Utiliser des réglages spécifiques pour chaque boutique ou groupe de boutiques

Le sélecteur "Configuration multiboutique pour" est l'option sur laquelle se rendre lorsque vous voulez que vos modifications s'appliquent à une boutique ou ensemble de boutiques en particulier. C'est même le premier endroit à regarder lorsque l'écran d'administration se charge, car PrestaShop modifiera les options disponibles en fonction du contexte dans lequel vous vous trouvez : boutique, groupe de boutiques ou toutes les boutiques.

Ainsi, il est possible de :

* Utiliser un format d'image différent pour chaque boutique/groupe de boutiques
* Activer/configurer un module par boutique
* Positionner/afficher des blocs front-office par boutique
* ...et bien plus encore !

## Gérer les pages statiques en mode multiboutique

Lorsque vous affichez la liste de pages de contenu dans le contexte "Toutes les boutiques", toutes les pages sont affichées. De la même manière, lorsque vous vous trouvez dans un contexte de groupe de boutiques, les pages de toutes les boutiques de ce groupe sont affichées.

Si une page est créée dans un contexte de groupe de boutiques, toutes les boutiques de ce groupe afficheront cette page, et pourtant celle-ci sera unique : la modifier pour une boutique fera qu'elle sera modifiée pour toutes les boutiques de ce groupe.\
Sur la page de création, une section apparaît avec une liste, indiquant lesquelles seront touchées.

## Gérer les promotions en mode multiboutique

Lors de la création de promotions panier ou catalogue dans un contexte multiboutique, une condition supplémentaire apparaît et permet de choisir les boutiques sur lesquelles apparaît la promotion.

## Multiboutique et webservice

L'accès au webservice est lui aussi entièrement paramétrable au niveau de la boutique ou du groupe de boutiques. Lors de la création d'une clé pour le webservice vous pouvez choisir de l'associer soit à toutes les boutiques, soit à des groupes de boutiques, soit à des boutiques individuelles.
