---
description: >-
  Depuis la page commande, vous pouvez accéder aux détails de la commande et les
  modifier.
---

# Modifier une commande

## Mettre à jour l'état de la commande

&#x20;Il y a deux endroits sur la page commande où vous pouvez mettre à jour son statut :

* Dans le coin supérieur gauche de la page, à côté des boutons d'action.&#x20;
* Dans l'onglet "État"&#x20;

Sélectionnez l'état souhaité dans la liste déroulante et cliquez sur le bouton "Mettre à jour l'état".&#x20;

![](<../../../../.gitbook/assets/image (7).png>)

Vous avez le choix entre plusieurs états :

![](<../../../../.gitbook/assets/image (8).png>)

{% hint style="info" %}
D'autres états pourraient être disponibles dans cette liste en fonction des modules installés sur votre boutique.&#x20;
{% endhint %}

Afin d'avoir un meilleur aperçu de l'activité de la commande, chaque changement d'état est enregistré dans l'onglet "État" de la section administrative, ainsi que son auteur et la date/heure de mise à jour.

![](<../../../../.gitbook/assets/image (9).png>)

{% hint style="warning" %}
**L'état d'une commande ne doit être mis à jour que lorsqu'il est** **clairement confirmé**. Par exemple, ne marquez pas une commande comme "Livré" lorsque vous n'avez fait qu'envoyer le colis, utilisez plutôt "Expédié".
{% endhint %}

:incoming\_envelope:Pour certaines mises à jour d'état, un e-mail est envoyé au client. Vous pouvez renvoyer cet e-mail en cliquant sur le bouton à côté de l'état de la commande, dans l'onglet État. Si vous avez modifié la commande à un moment donné, le client recevra un e-mail actualisé.

## Accéder aux documents de la commande

Vous pouvez obtenir de nombreux documents PDF à partir de la page commande. Lorsqu'ils sont disponibles, ils sont répertoriés dans l'onglet Documents de la section administrative.&#x20;

* **Imprimer/télécharger la commande **

Vous pouvez imprimer ou télécharger la commande au format PDF en cliquant sur le bouton "Imprimer la commande" en haut de la page.&#x20;

* **Télécharger/générer une facture**&#x20;

Vous pouvez télécharger la facture en cliquant sur le bouton "Voir la facture" en haut de la page. Vous pouvez également accéder à la facture ou la générer dans l'onglet "Documents".

:arrow\_right:Dans l'onglet Documents, vous pouvez ajouter une note à la facture qui apparaîtra juste en dessous du tableau des taxes sur la facture.

{% hint style="success" %}
Voici un conseil pour les commerçants les plus à l'aise en informatique : Vous pouvez personnaliser la présentation de la facture ! Les fichiers modèles PDF se trouvent dans le dossier /pdf. Ces fichiers .tpl sont en fait des fichiers HTML avec des balises Smarty pour les données dynamiques. Vous pouvez modifier la présentation de la facture en éditant le fichier nommé "invoice.tpl".&#x20;
{% endhint %}

* **Télécharger le bon de livraison **

Si l'état de la commande est en cours de préparation, un bon de livraison au format PDF est automatiquement généré. Vous pouvez le télécharger à partir de l'onglet Documents ou cliquer sur le bouton "Afficher le bon de livraison" en haut de la page.

## Modifier le contenu de la commande

### &#x20;Ajouter un produit à la commande

![](<../../../../.gitbook/assets/image (10).png>)

En bas de la liste des produits :&#x20;

* Cliquez sur le bouton "Ajouter un produit"
* Entrez le nom du produit
* Sélectionnez le produit que vous souhaitez ajouter&#x20;
* Ajustez la quantité&#x20;
* Choisissez sur quelle facture vous souhaitez faire apparaître le produit et cliquez sur le bouton "Ajouter"

{% hint style="warning" %}
Si une facture a déjà été envoyée au client, vous ne devez pas y ajouter de nouveaux produits. Créez plutôt une autre facture : lorsque vous ajoutez un nouveau produit, choisissez "Créer une nouvelle facture" dans la liste déroulante.
{% endhint %}

Vous ne pouvez pas ajouter plus de produits que ceux disponibles en stock. Lorsque vous sélectionnez un produit, le nombre d'articles en stock apparaît dans la colonne "Disponible".

:arrow\_right:Pour ajouter un produit qui est déjà présent dans la commande, cliquez sur le bouton "Modifier" et ajustez simplement la quantité.

### Retirer un produit de la commande

Pour retirer un produit de la commande, allez dans la liste des produits et supprimez le en cliquant sur le bouton "Supprimer".&#x20;

:arrow\_right:Si vous ne souhaitez supprimer qu'une certaine quantité de produits, cliquez sur le bouton "Modifier" et ajustez la quantité.

{% hint style="success" %}
Vous pouvez également supprimer ou modifier la quantité de plusieurs produits en même temps.

Pour cela, cliquez sur le bouton "Annuler les produits", en haut de la page, et sélectionnez les produits ou la quantité que vous souhaitez supprimer. Ce bouton n'est disponible que si les retours de marchandises sont activés sur la page SAV > Retours produits et si la commande n'est pas déjà payée.
{% endhint %}

## Modifier les détails de la commande

### Modifier les détails d'expédition

Dans la section administrative, cliquez sur l'onglet Transporteurs. Ensuite, cliquez sur le bouton "Modifier" pour modifier le numéro de suivi et le transporteur.&#x20;

:arrow\_right:Notez que le transporteur ne peut être modifié que si la commande n'a pas encore été expédiée.

### Modifier l'adresse de livraison ou de facturation

L'**adresse de livraison** est l'adresse où le colis sera envoyé, tandis que l'**adresse de facturation** correspond à l'adresse de l'acheteur. Elles peuvent être différentes (dans le cas d'un client qui commande un cadeau pour un ami, par exemple).

Si un client vous demande de modifier l'une de ces deux adresses, allez dans la section Client et cliquez sur le menu latéral à côté du champ "Adresse de livraison" ou "Adresse de facturation". Vous pouvez modifier l'adresse existante ou sélectionner une autre adresse, dans la liste des adresses fournies par le client.

![](<../../../../.gitbook/assets/image (11).png>)

Si l'adresse que vous souhaitez associer à la commande n'est pas déjà enregistrée dans PrestaShop, vous devez d'abord la créer :

* Dans la section Client de la page Commande, accédez au dossier personnel du client, en cliquant sur "Plus de détails"
* En bas de la page, cliquez sur le "+" dans la section Adresses.
* Remplissez le formulaire et sauvegardez
* Retournez à la page des détails de la commande et sélectionnez l'adresse que vous venez d'ajouter dans la liste déroulante.

![Section Addresses de la page Client](<../../../../.gitbook/assets/image (12).png>)

## Gérer les paiements et les réductions

### Enregistrer un nouveau paiement

Pour enregistrer un nouveau paiement, allez à la section Paiements de la page Commande.&#x20;

* Sélectionnez la date de paiement et entrez le mode de paiement utilisé
* Saisissez l'identifiant de la transaction&#x20;
* Entrez le montant et sélectionnez la devise&#x20;
* Sélectionnez la facture sur laquelle vous souhaitez que ce paiement apparaisse&#x20;
* Cliquez sur le bouton "Ajouter" pour sauvegarder

![](<../../../../.gitbook/assets/image (13).png>)

### Ajouter une réduction

Dans la section Produits, en dessous de la liste des produits commandés, cliquez sur le bouton "Ajouter une réduction", et remplissez le formulaire :

![](<../../../../.gitbook/assets/image (14).png>)

* **Nom :** Donnez un nom à la réduction. Celui-ci sera visible par le client
* **Type :** Choisissez le type de réduction : "pourcentage", "montant" ou "livraison gratuite"
* **Valeur :** Pour les types "pourcentage" ou "montant", définissez la valeur de la réduction
* **Facture :** Sélectionnez la facture sur laquelle vous souhaitez appliquer cette réduction. Lorsqu'il y a plusieurs factures, vous pouvez cocher la case pour appliquer la remise à toutes les factures.

{% hint style="info" %}
La réduction n'est pas appliquée aux frais de port, sauf si vous cochez la case "livraison gratuite".
{% endhint %}

## Gérer les messages de la commande et les commentaires privés

### Ajouter un commentaire privé :lock\_with\_ink\_pen:&#x20;

Dans la section Client de la page commande, vous pouvez ajouter un commentaire privé à propos d'un client qui ne sera visible que par vous et votre équipe. Cela peut s'avérer très utile pour échanger des informations entre collègues à propos du client : s'agit-il d'un client régulier ? Faut-il lui accorder une attention particulière en raison d'un incident antérieur ?

### Attacher un message à la commande :e-mail:&#x20;

Vous pourriez avoir besoin d'envoyer un message à votre client pour le tenir informé de l'avancement de sa commande ou lui faire part d'un imprévu. **La communication est la clé d'une bonne expérience client ! **Et la bonne nouvelle, c'est que vous pouvez le faire très facilement à partir de la page de commande :&#x20;

Écrivez votre message dans le champ message et envoyez-le.&#x20;

* [x] Si vous souhaitez que votre client reçoive le message, n'oubliez pas de cocher la case "Montrer au client".\

* [ ] Si vous souhaitez garder ce message privé, c'est également possible : il suffit de ne pas cocher la case "Montrer au client".

### Envoyer des messages prédéfinis

Vous pouvez sélectionner un message prédéfini dans la liste déroulante. Vous pouvez ensuite y apporter des modifications avant de l'envoyer si nécessaire.

Si vous souhaitez écrire des messages prédéfinis personnalisés, cliquez sur le bouton "Configurer les messages prédéfinis". Vous serez alors redirigé vers la page des messages prédéfinis, sous le menu SAV.&#x20;

Pour en savoir plus :

{% content-ref url="../../gerer-service-client/messages-predefinis.md" %}
[messages-predefinis.md](../../gerer-service-client/messages-predefinis.md)
{% endcontent-ref %}

