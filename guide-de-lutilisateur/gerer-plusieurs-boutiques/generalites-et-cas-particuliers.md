# Généralités et cas particuliers

## Gestion du catalogue en multiboutique

En mode multiboutique, certaines des pages d'administration de PrestaShop présentent un menu déroulant bien visible, intitulé "Configuration multiboutique pour". Ce menu vous donne le contexte de ce que vous êtes en train de faire : il vous permet de déterminer le groupe ou la boutique pour lesquelles les modifications du catalogue seront effectuées.

Par exemple, lors de la création d'un produit, la sélection de ce menu déterminera si ce produit est disponible pour toutes les boutiques, les boutiques d'un groupe ou une seule boutique.

Lors de la modification d'un produit, PrestaShop affiche des notifications qui vous aident à comprendre l'étendu de vos modifications. Par exemple, lors de la modification d'un produit dans un contexte "Boutique A", la notification indiquera "Attention, si vous modifiez la valeur des champs qui ont une icône orange, la valeur sera changé dans toutes les boutiques pour ce produit", avec l'icône orange placée en face des champs touchés, tels que "Type", "Référence", les mesures de l'emballage, etc.

De la même manière, si vous modifiez un produit dans le contexte "Toutes les boutiques" ou un contexte de groupe de boutiques, certains champs seront désactivés afin que vous ne puissiez pas les modifier du fait de leur impact global. Si vous avez réellement besoin de modifier son contenu, chaque champ dispose d'une case que vous pouvez cocher pour modifier toutes les boutiques appartenant à ce contexte.

Si vous modifiez un champ désactivé, le produit sera créé dans toutes les boutiques du contexte qui n'ont pas déjà ce produit dans leur catalogue. Faites donc attention au contexte en cours lors de votre action.

## Échange de données entre boutique

### Dupliquer les données entre les boutiques

Les données dupliquées dans PrestaShop sont mises en place durant la configuration de n'importe quelle boutique individuelle, en important tout ou partie du contenu d'une boutique existante dans la nouvelle. Le contenu qui peut être importé est varié : produits, catégories, employés, modules, règles panier, fournisseurs, etc. L'import des données se fait une fois pour toute : une fois que la boutique a été créé, vous ne pouvez pas réimporter des données en provenance d'une autre boutique – du moins pas simplement.

### Partager des données entre boutiques et groupes de boutique

Les boutiques peuvent partager des données. Les données partagées sont fondamentalement gérées au niveau du groupe de boutiques : l'un des aspects important à comprendre du mode multiboutique de PrestaShop est que toutes les boutiques au sein d'un même groupe de boutiques peuvent partager leurs données – ou plus précisément, trois types de contenu : les clients, les quantités disponibles, et les commandes. Une fois qu'un groupe de boutique est mis en place, le partage des données entre ses boutiques est terminé : même si vous pouvez changer la configuration pour la quantité de produits, vous ne pouvez plus changer les réglages des clients et des commandes à partir du moment où l'une des boutiques de ce groupe accepte au moins un client ou une commande.

### Partager les produits et les catégories

Lorsque vous créez une nouvelle boutique au sein d'un groupe, vous pouvez faire en sorte que toutes ou une partie des catégories dans la nouvelle boutique soient des copies exactes des catégories d'une autre boutique de votre installation de PrestaShop.

Lors de la création d'une catégorie, soit pour une boutique précise ou pour toutes les boutiques de votre installation de PrestaShop, PrestaShop enregistre la catégorie pour toutes les boutiques – elle est simplement cachée des boutiques pour lesquelles elle n'a pas été configurée.

En associant les nouvelles boutiques à une catégorie donnée, chaque modification dans cette catégorie aura une répercussion sur toutes les boutiques auxquelles elle a été associée, même si les boutiques viennent de différents groupes de boutiques. Vous pouvez donc changer le contenu de la catégorie une fois pour toutes les boutiques, y compris pour ses produits.

### Partager les clients et les groupes de clients

Comme indiqué ci-dessus, les boutiques au sein d'un même groupe de boutiques peuvent partager leurs clients : vous devez simplement régler la bonne option lors de la création du groupe de boutiques.

Les groupes sont moins détaillés : si vous changez l'un des groupes de clients par défaut dans une boutique, la modification sera appliquée à toutes les autres boutiques, quels que soient leurs groupes de boutiques.

Si vous souhaitez avoir un groupe de clients différent pour chaque boutique, vous devez créer un nouveau groupe et utiliser le sélecteur "Configuration multiboutique pour" pour associer le groupe à la boutique actuelle ou au groupe de boutiques actuel.

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

Si une page est créée dans un contexte de groupe de boutiques, toutes les boutiques de ce groupe afficheront cette page, et pourtant celle-ci sera unique : la modifier pour une boutique fera qu'elle sera modifiée pour toutes les boutiques de ce groupe.  
Sur la page de création, une section apparaît avec une liste, indiquant lesquelles seront touchées.

## Gérer les promotions en mode multiboutique

Lors de la création de promotions panier ou catalogue dans un contexte multiboutique, une condition supplémentaire apparaît et permet de choisir les boutiques sur lesquelles apparaît la promotion.

## Multiboutique et webservice

L'accès au webservice est lui aussi entièrement paramétrable au niveau de la boutique ou du groupe de boutiques. Lors de la création d'une clé pour le webservice vous pouvez choisir de l'associer soit à toutes les boutiques, soit à des groupes de boutiques, soit à des boutiques individuelles.

