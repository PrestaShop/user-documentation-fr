# Paramètres des produits

Cette page contient les préférences se rattachant à la manière dont vos produits sont gérés et affichés par PrestaShop.

## Préférences générales <a href="#parametresdesproduits-preferencesgenerales" id="parametresdesproduits-preferencesgenerales"></a>

![](../../../.gitbook/assets/64225331.png)

* **Mode catalogue**. Activer le mode catalogue signifie que vous transformez votre boutique en une simple galerie de produits, n'offrant aucune possibilité d'achat.
* **Nombre de jours durant lesquels un produit est considéré comme "nouveau"**. Quand vous ajoutez un produit à votre boutique, il est considéré comme étant nouveau, et se trouve dans la page "Nouveaux produits". Ce champ vous permet de préciser le nombre de jours durant lesquels un produit est considéré comme nouveau. Cette option vous permet donc de mieux contrôler la manière dont vous gérez les nouveautés de votre boutique. La page des nouveaux produits est surtout visitée par les clients réguliers.
* **Taille maximale du récapitulatif**. Votre produit dispose de deux descriptions : un récapitulatif et une description classique. Le récapitulatif, qui est une description courte, apparaît dans les moteurs de recherche et dans la page catégorie, est limitée à 800 caractères par défaut, mais cette option vous permet de changer cette valeur. 0 signifie qu'il n'y a pas de limite.
* **Remises des quantités basées sur**. Définit sur quelle base (produits ou déclinaisons) sont calculées les remises de quantité.
* **Forcer la mise à jour des URL simplifiées.** Activée, cette option permet la mise à jour automatique des URL simplifiées des produits lorsqu'une modification intervient.
* **Activer par défaut**. Avec cette option activée, un nouveau produit est automatiquement activé à sa création.

## Pagination <a href="#parametresdesproduits-pagination" id="parametresdesproduits-pagination"></a>

![](../../../.gitbook/assets/64225332.png)

* **Produits par page**. Indique le nombre de produits affichés sur les pages de vos catégories.
* **Tri par défaut**. Indique l'ordre des produits dans les catégories de votre boutique. 8 choix sont possibles :\

  * _Nom du produit._ Affiche vos produits par ordre alphabétique de leurs noms.
  * _Prix du produit._ Affiche vos produits en fonction de leurs prix.
  * _Date d'ajout._ Affiche vos produits en fonction de leurs dates d'ajout.
  * _Date de modification._ Quand vous modifiez un produit, sa date de modification est changée. Cette option les fait apparaître par ordre de modification.
  * _Position dans la catégorie._ Affiche vos produits tels qu'ils sont positionnés au sein de la catégorie, dans le catalogue. La position d'un produit peut être changée directement dans le catalogue de votre boutique en utilisant les flèches de positionnement. Ainsi, vous pouvez placer vos produits de la manière la plus à même de provoquer une vente.
  * _Marque._ Affiche vos produits par ordre alphabétique du nom de leurs marques.
  * _Quantité du produit._ Affiche vos produits en fonction de la quantité présente en stock.
  * _Référence du produit._ Affiche vos produits par ordre alphabétique et/ou numérique de référence.
* **Ordre par défaut**. L'option ci-dessus peut être arrangée par ordre croissant ou décroissant.

## Page produit <a href="#parametresdesproduits-pageproduit" id="parametresdesproduits-pageproduit"></a>

![](../../../.gitbook/assets/64225333.png)

* **Afficher les quantités disponibles sur la page produit**. En activant cette fonctionnalité, vos visiteurs peuvent voir la quantité disponible en stock de chaque produit. Vous pouvez utiliser cette information pour doper les ventes quand le stock est bas. Les quantités affichées sont pour les attributs et déclinaisons sélectionnés.
* **Afficher les dernières quantités lorsque celles-ci sont inférieures à**. Vous pouvez choisir d'afficher une notification quand le stock disponible d'un produit atteint une certaine limite. Cette option se montre particulièrement utile pour pousser à l'achat. Le texte et la position de la notification dépendent du thème ; dans le thème par défaut, la notification annonce "Derniers articles en stock", et est affiché à côté du bouton "Ajouter au panier".
* **Afficher les attributs indisponibles sur la fiche produit**. Votre produit peut être fait de nombreux attributs et déclinaisons : couleur, taille, capacité, etc. Les attributs peuvent être modifiés dans la page "Attributs" de votre menu "Catalogue". Quand au moins un attribut n'est plus disponible, vous avez deux possibilités :
  * _Premièrement :_ laisser cette préférence active. Par exemple : le produit "iPod Shuffle" n'est plus disponible en couleur "Bleu". En laissant cette option activée, la déclinaison du produit restera visible sur votre boutique. Un message indique alors que le produit n'est plus disponible pour l'option choisie, et invite les clients à en choisir une autre. Si vous avez activé l'option "Autoriser la commande de produits hors stock" (voir ci-dessous), alors ils pourront malgré tout commander cette déclinaison.
  * _Deuxièmement :_ désactiver cette préférence. Si la déclinaison "Bleu" du produit "iPod Shuffle" n'est plus disponible, cette sélection n'est plus affichée sur le front-office, et les clients ne peuvent donc plus la sélectionner. Cette option vous aide à clairement afficher la disponibilité de vos produits.
* **Afficher le bouton "Ajouter au panier" lorsque le produit a des attributs**. Cette option empêche vos clients d'ajouter des produits directement depuis la page de catégorie, si le produit a des déclinaisons. Cela oblige le client à se rendre sur la page du produit et à choisir une déclinaison, au lieu d'ajouter celle par défaut au panier. Notez que les produits qui n'ont pas de déclinaisons auront toujours un bouton "Ajouter au panier" sur la page de catégorie.
* **Séparateur des attributs dans les liens des produits**. Choisissez le séparateur, entre "-" et ",".
* **Afficher le prix réduction comprise**. Dans le tableau récapitulatif des réductions en fonction du volume, afficher le prix après réduction au lieu d'afficher le pourcentage de réduction.

## Stocks produit <a href="#parametresdesproduits-stocksproduit" id="parametresdesproduits-stocksproduit"></a>

![](../../../.gitbook/assets/64225336.png)

* **Autoriser la commande de produits en rupture de stock**. Si un produit n'est plus disponible en stock, le client peut quand même le commander.
* **Activer la gestion des stocks**. Cette option vous donne à accès un gestionnaire de stock basique : vous pouvez régler la quantité actuelle d'un produit, et laisser PrestaShop diminuer ce nombre à chaque commande, et en rajouter à chaque commande annulée et produit retourné. Par défaut, vous devriez laisser cette fonctionnalité activée. En effet, la désactivation affecte l'intégralité du gestionnaire d'inventaire de votre boutique. À ne désactiver que si vous n'avez aucun inventaire physique – par exemple, si vous ne vendez que des produits dématérialisés.\

* **Etiquette pour produits en stock.** Affiche une mention pour les produits en stock.
* **Etiquette pour produits en rupture de stock avec réassort autorisé.** Affiche une mention pour les produits hors stock avec réassort autorisé.
* **Etiquette pour produits en rupture de stock sans réassort autorisé.** Affiche une mention pour les produits hors stock sans réassort autorisé.
* **Délai de livraison des produits en stock.** Cette option est recommandée pour les marchands européens afin de se mettre en conformité avec la réglementation.
* **Délai de livraison des produits en rupture de stock avec réassort autorisé.** Cette option est recommandée pour les marchands européens afin de se mettre en conformité avec la réglementation.
* **Gestion des stocks de packs par défaut.** Quand vous vendez des packs de produits, la gestion de vos stocks dépend de cette option. Vous avez trois possibilités :
  * _Décrémenter uniquement le pack._ Quand un pack est vendu, seul le stock du pack est modifié.
  * _Décrémenter uniquement les produits du pack._ Quand un pack est vendu, seul le stock de chaque produit est modifié.
  * _Décrémenter les deux._ Quand un pack est vendu, le stock du pack et le stock des produits qui le composent sont modifiés.\
    \
    Cette option peut être changée individuellement pour chacun de vos packs dans leur propre page de gestion, dans l'onglet "Quantités".
