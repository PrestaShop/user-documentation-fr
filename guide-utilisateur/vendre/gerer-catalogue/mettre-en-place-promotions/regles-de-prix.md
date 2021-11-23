# Règles de prix catalogue

Les règles de prix catalogue vous permettent d'assigner des réductions par catégorie, marque, fournisseur, attribut ou caractéristique. Comme son nom le sous-entend, ce type de règle s'applique à un ensemble de produits ; il ne peut être utilisé pour un seul produit. Si vous avez besoin d'appliquer une promotion à un seul produit, vous devez passer par une règle panier ou un prix spécifique (dans l'onglet "Prix" de la page de modification du produit).

Par exemple, vous pouvez créer une règle qui spécifiera que les clients espagnols appartenant au groupe "Bons clients" ont droit à 10% de réduction sur la catégorie "Matériel électronique" et tous les produits Sony pendant la première semaine du mois de juillet.

La page "Règles de prix catalogue" liste les règles actuellement en place, que vous pouvez activer ou désactiver. Si vous souhaitez désactiver une règle, changez simplement sa date de fin pour la mettre à la veille.

## Créer une nouvelle règle de prix catalogue <a href="reglesdeprixcatalogue-creerunenouvelleregledeprixcatalogue" id="reglesdeprixcatalogue-creerunenouvelleregledeprixcatalogue"></a>

La page du formulaire de création dispose de deux sections, vous permettant de construire précisément vos règles.

### Règles de prix catalogue <a href="reglesdeprixcatalogue-reglesdeprixcatalogue.1" id="reglesdeprixcatalogue-reglesdeprixcatalogue.1"></a>

Le premier formulaire est facile à comprendre.

![](../../../../.gitbook/assets/52298241.png)

C'est ici que vous indiquez qui profite de la règle, quel en sera la réduction, et d'autres détails.

* **Nom**. Le nom apparaîtra pour le public, donc restez sobre.
* **Boutique**. _Seulement en mode multiboutique_. La règle ne s'applique que si le client achète en passant par une boutique donnée. Disponible uniquement si vous avez au moins deux boutiques.
* **Devise**. La règle ne s'applique que si le client a choisi de payer avec une monnaie donnée.
* **Pays**. La règle ne s'applique que si le client est d'un pays donné.
* **Groupe**. La règle ne s'applique que si le client appartient à un groupe donné.
* **À partir de la quantité**. La règle ne s'applique que si la commande a au moins un nombre donné de produits correspondants.
* **Montant HT**. Le nouveau prix du ou des produits. Vous pouvez ainsi remplacer le prix public des produits qui correspond aux règles mises en place. Par défaut, la règle s'applique sur le prix de vente initial.
* **Du** et **Au**. La règle ne s'applique que durant cette période.
* **Type de réduction**. La réduction peut soit être un montant précis, soit un pourcentage du montant total de la commande.
* **Réduction avec ou sans taxes.** La réduction peut au choix inclure la tax, ou la laisser telle qu'elle est.
* **Réduction**. La valeur de la réduction. En fonction du type de réduction ci-dessus, indiquer "10.0" signifiera soit "10€ en moins" (en fonction de la devise par défaut), soit "10% en moins". La réduction sera indiquée dans la facture finale.

Vous pouvez bien sûr combiner toutes ces règles.

### Conditions <a href="reglesdeprixcatalogue-conditions" id="reglesdeprixcatalogue-conditions"></a>

La section "Conditions" est là où vous définissez les produits auxquels la règle de prix catalogue s'appliquent. Elle n'apparaît que si vous cliquez sur le bouton "Ajouter un nouveau groupe de conditions".

Si aucune condition n'est définie, la règle de prix catalogue s'appliquera à TOUS les produits de votre catalogue. Veillez à ne pas oublier les conditions !

![](../../../../.gitbook/assets/52298242.png)

Les conditions sont construites à partir de groupes de conditions, ce qui signifie que vos réglages de la section "Règles de prix catalogue" ci-dessus peuvent être appliqués à de nombreuses gammes de produits. Les conditions se regroupées de manière inclusive : il faut que toutes les conditions s'appliquent pour que la règle de prix catalogue s'applique. Ce qui explique la mention "ET". En revanche, les groupes de conditions sont exclusifs : il suffit qu'un seul groupe s'applique pour que la règle de prix catalogue s'applique. Ce qui explique la mention "OU".

Le groupe de conditions par défaut est vide. Vous pouvez ajouter des conditions à l'aide des menus déroulants dans la partie inférieure de la section :

* Choisissez une catégorie ou tout autre type de sélection, puis cliquez sur le bouton "Ajouter la condition".
* La condition s'affichera dans le groupe de conditions. Vous pouvez mettre de nombreuses conditions dans un groupe de conditions.
* Une fois qu'un groupe est terminé et que vous voulez créer un nouveau groupe de conditions, cliquez sur "Ajouter un nouveau groupe de conditions". Un nouveau groupe apparaît alors, que vous pouvez remplir de la même manière.

Par défaut, les nouvelles conditions sont ajoutées au groupe de conditions qui a été créé en dernier. Si vous avez besoin d'ajouter des conditions à un groupe précédent, cliquez sur ce groupe pour le mettre en surbrillance, puis ajoutez vos conditions.

Vous ne pouvez pas pour le moment supprimer un groupe des conditions.
