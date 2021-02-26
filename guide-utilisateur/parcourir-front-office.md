# Parcourir le front-office

Le front-office correspond à ce que les clients voient en parcourant votre boutique et tout le long du processus d’achat. 

En tant que marchand, vous devez connaître le front-office comme votre poche, afin de comprendre ce à quoi vos clients font face, comment se déroule une expérience d’achat type, quels sont les points de blocage, etc. 

Même si vous pensez connaître votre front-office par cœur, n’oubliez pas d’y retourner de temps en temps, comme si vous étiez un utilisateur qui visite le site pour la première fois. Parcourez votre boutique, achetez un produit, contactez le service client… mettez vous dans la peau de vos clients ! Vous pourriez faire des découvertes et noter quelques points à améliorer.  


## Le thème par défaut 

![](../.gitbook/assets/image%20%2829%29.png)

PrestaShop est livré avec un thème par défaut. Ce thème utilise un design simple et épuré, avec du blanc et du gris. Cette simplicité visuelle permet de s'adapter à presque tous les secteurs d'activité : voitures, photographies, antiquités, ou n'importe quoi d'autre ! Il a été conçu pour être facile à parcourir, ergonomique, conforme aux normes et adapté à toutes les tailles d'écran et à tous les appareils. 

Si vous avez installé PrestaShop avec ses données de démonstration, vous verrez des produits vestimentaires et des accessoires de maison. 

Notez que cette page de la documentation sera basée uniquement sur le thème par défaut et les paramètres et modules par défaut. En effet, l'activation d'autres modules ou l'utilisation d'un autre thème pourrait changer radicalement l'expérience d'achat. 

{% hint style="success" %}
Si vous souhaitez changer de thème, choisissez en un parmi le large choix de thèmes disponibles sur [PrestaShop Addons](https://addons.prestashop.com/). 
{% endhint %}

## Parcourir la boutique

### L'en-tête

L'en-tête est une fine barre de contenu en haut de la page, accessible depuis n'importe quelle page du front-office. 

![En-t&#xEA;te](../.gitbook/assets/image%20%2824%29.png)

L'en-tête est séparé en deux. 

La partie supérieure de l'en-tête contient :

* **Un lien vers la page de contact** 
* **Un sélecteur de langue :** Si plus d'une langue est disponible sur la boutique, le client peut choisir en quelle langue il souhaite afficher les pages du front-office.
* **Un sélecteur de devises :** Si plus d'une devise est disponible sur la boutique, le client peut choisir en quelle devise il souhaite voir s'afficher les prix des produits. Cela peut s'avérer très pratique au moment de comparer les prix avec d'autres boutiques à l'international. 
* **Un lien vers la page d'authentification :** Une fois connecté, le client a accès à son compte, et un lien "Déconnexion" apparaît à côté de son nom. 
* **Un lien vers le panier du client :** En un coup d'oeil, le client peut savoir combien d'articles il a dans son panier. Il peut également cliquer sur le bouton" Panier" pour accéder au contenu du panier et finaliser sa commande. 

![Partie sup&#xE9;rieure de l&apos;en-t&#xEA;te ](../.gitbook/assets/image%20%2825%29.png)

La partie inférieure de l'en-tête, plus large, contient :

* **Le logo de la boutique :** En cliquant sur ce logo, le client sera redirigé vers la page d'accueil de la boutique, peu importe la page sur laquelle il se trouve. N'oubliez pas de changer le logo par défaut en le remplaçant par votre propre logo personnalisé ! 
* **Le menu :** Par défaut, les catégories "Vêtements", "Accessoires" et "Art" sont affichées, et des sous-catégories apparaîssent au survol de la souris. Pour personnaliser le menu avec vos propres catégories, vous devez configurer le module "Menu principal". 
* **La barre de recherche :** La barre de recherche facilite la recherche sur votre boutique : une recherche à la bonne place et vos clients trouveront rapidement les articles qu'ils recherchent !

![Partie inf&#xE9;rieure de l&apos;en-t&#xEA;te](../.gitbook/assets/image%20%2818%29.png)

### Le pied de page

Le pied de page est séparé en deux parties.

![](../.gitbook/assets/image%20%2823%29.png)

➡La partie supérieure du pied de page contient un **bloc d'inscription à la newsletter** de votre boutique, permettant au client de recevoir des offres spéciales. Ce formulaire d'abonnement est géré par le module "Inscription à la newsletter". 

![Bloc d&apos;inscription &#xE0; la newsletter ](../.gitbook/assets/image%20%2828%29.png)

{% hint style="warning" %}
Veuillez noter que l'envoi de la newsletter est de votre ressort. Grâce au module "Newsletter", vous pourrez générer un fichier .csv contenant tous les clients enregistrés et leurs e-mails. Vous pourrez ensuite importer ce fichier .csv dans n'importe quel système d-e-mailing. 
{% endhint %}

➡La partie inférieure du pied de page contient 4 blocs donnant accès à des pages qui pourraient être très utiles pour vos clients :

{% tabs %}
{% tab title="PRODUITS" %}
**Le bloc "Produits" permet d'accéder rapidement aux pages suivantes :**

* Promotions
* Nouveaux produits 
* Meilleures ventes
{% endtab %}

{% tab title="NOTRE SOCIETE" %}
**Le bloc "Notre société" renvoie vers des pages d'informations :**

* Livraison
* Mentions légales
* Conditions d'utilisation
* A propos
* Paiement sécurisé
* Contactez-nous
* Plan du site
* Magasins
{% endtab %}

{% tab title="VOTRE COMPTE" %}
**Le bloc "Votre compte" contient des liens vers les pages principales du compte client \(ou la page d'authentification, si le client n'est pas connecté\).**  

* Informations personnelles 
* Retours produits
* Commandes
* Avoirs 
* Adresses
{% endtab %}

{% tab title="INFORMATIONS" %}
**Le bloc "Informations" contient toutes les informations relatives à votre boutique :**

* Le nom de la boutique
* L'adresse 
* Le numéro de téléphone
* L'e-mail 
{% endtab %}
{% endtabs %}

### Les pages de catégories

#### La colonne de gauche: 

La colonne de gauche du thème par défaut n'apparaît que sur les pages de catégories, lorsqu'elle est activée depuis le back office. 

* **Le bloc "Catégories"**

Une catégorie est une façon hiérarchique de trier les produits : elle peut contenir un nombre illimité de sous-catégories, ce qui permet de passer facilement des listes de catégories générales aux produits plus spécifiques en suivant un chemin logique.

Une boutique PrestaShop peut avoir autant de catégories et de sous-catégories que nécessaire, avec un nombre infini de produits dans un niveau de catégorie donné. 

A noter : Toutes les catégories sont en fait des sous-catégories de la catégorie racine, "Accueil".

* **Le bloc "Filter par"**

Filtrer leur recherche permet aux clients de trouver le produit qu'ils recherchent plus rapidement. Sur la colonne de gauche d'une page de catégorie, il est possible de préciser sa recherche en filtrant principalement par attributs, caractéristiques ou encore fourchette de prix. 

### La section centrale

La section centrale change en fonction des choix des clients. 

#### La page d'accueil 

La page d'accueil par défaut donne au client un large aperçu du magasin et de ses possibilités. Cette page d'accueil doit être pensée à destination de nouveaux clients. Que souhaitez-vous mettre en avant ? 

En haut de la page, il y a un carrousel d'images : trois images défilent. Vous pouvez utiliser ce carrousel pour mettre en avant vos nouvelles collections, des promotions à ne pas louper, etc. 

![](https://media.giphy.com/media/2oUFsps8xUl4H2TK80/giphy.gif)

En dessous, sont affichés les produits populaires de votre boutique. 

Vous pouvez également personnaliser une bannière, ou encore ajouter un bloc de texte. N'hésitez pas à consulter la documentation pour apprendre à [configurer la page d'accueil de votre boutique](https://prestashop.gitbook.io/documentation-francaise-1-7/guide-utilisateur/optimiser-boutique/personnaliser-apparence-boutique/theme-et-logo#configuration-page-daccueil). 

### Listes de produits 

Toutes les listes de produits sur PrestaShop se ressemblent, peu importe la page sur laquelle elles se trouvent \(Nouveaux produits, meilleures ventes, catégories, etc.\)

Les produits sont organisés sous forme de grille, avec :

* Une image  miniature
* Les bandeaux de promotion ou d'état, en haut à gauche de l'image
* Le nom du produit
* Le prix du produit 

![Exemple de liste de produits ](../.gitbook/assets/image%20%2822%29.png)

Cette présentation sous forme de liste permet au client de voir en un coup d'œil les principales informations sur les produits, accélérant alors le processus de décision. 

Au survol de la souris, le client peut accéder à un "aperçu rapide" du produit. Il aura alors accès, en plus des informations précédemment énoncées, à la description du produit, et pourra ajouter le produit à son panier après avoir choisi les attributs \(s'il y en a\) et saisi la quantité souhaitée. 

![](../.gitbook/assets/image%20%2831%29.png)

En-tête de la catégorie :

Les catégories peuvent comporter une image d'en-tête avec un message d'introduction, tel que défini par le propriétaire du magasin. 

Tri des produits 

Les produits d'une catégorie peuvent être triés selon le prix \(croissant ou décroissant\), le nom \(de A à Z ou de Z à A\) ou par pertinence. 

Page du produit 

C'est là que toutes les informations saisies par le propriétaire du magasin sont à la disposition de l'utilisateur. Selon la conception du thème, une page de produit peut être très complète, avec des informations détaillées, ou simplement présenter les faits les plus essentiels. Le thème par défaut est typique en ce sens que sa caractéristique la plus importante est les images de produits, avec un outil en dessous qui permet aux clients de visualiser les différentes images disponibles. A côté des images, il y a deux blocs : Un bloc "résumé", présentant les faits principaux du produit en cours. Le bloc "Ajouter au panier", avec la possibilité de choisir parmi les combinaisons disponibles \(telles que définies par le propriétaire du magasin\) et la quantité à commander. Sous le bloc "panier", vous trouverez un bloc "rassurant", pour informer vos clients des différents avantages d'acheter sur votre boutique, ou pour être plus transparent sur vos politiques de paiement et de livraison. Au bas de la page du produit se trouve un onglet. Les plus courants sont les suivants : Description. Elle donne la description complète du produit, telle qu'elle a été saisie par le propriétaire du magasin. Détails du produit. Cet onglet n'apparaît que si le propriétaire du magasin a saisi des données dans la fiche "Caractéristiques" du produit. Cette fiche donne toutes les caractéristiques détaillées qui ont été saisies dans la base de données. Le contenu de cet onglet est très peu écrit : il s'agit de faits bruts, loin de la description du produit. La page du panier En cliquant sur le lien "Panier : XX produits" dans l'en-tête, le client accède à la page de résumé du panier, qui est la première étape du processus de commande, avant d'entrer dans la page de paiement. Elle résume le panier et affiche à nouveau le bloc de rassurance. C'est là que le client s'assure que la commande ne contient que les produits souhaités, ni plus, ni moins. En cliquant sur le bouton "Commander", l'utilisateur est redirigé vers la page de commande, divisée en 4 sections : Informations personnelles. Où le client non enregistré est invité à se connecter ou à créer un compte. Cette étape est ignorée si le client est déjà connecté. Toutefois, elle reste disponible si le client souhaite se connecter avec un autre compte. Adresses. Lorsque le client se voit présenter ses adresses actuellement enregistrées dans PrestaShop, il doit choisir celle où la livraison doit être effectuée. Mode de livraison. Lorsque le client a choisi les options de livraison. Paiement. Lorsque le client se voit présenter le prix final de la commande \(qui inclut maintenant le prix de l'expédition\), et qu'il est invité à choisir un mode de paiement. Le client peut revenir à l'étape précédente en cliquant sur son titre. La page de paiement a été volontairement dépouillée de toute distraction telle que la colonne de gauche, le pied de page et d'autres liens qui peuvent éloigner le client de l'achat. Il est toujours possible de quitter le processus de paiement en cliquant sur le logo de la boutique dans l'en-tête.

## Créer un compte client

Afin de limiter au maximum les pertes dans le tunnel de conversion, PrestaShop permet aux visiteurs d'une boutique de se créer une compte simplement et rapidement ! 

En cliquant sur "Connexion" dans l'en-tête, le visiteur est redirigé vers la page d'authentification, où il peut se connecter. 

S'il a besoin de créer un nouveau compte, il peut cliquer sur "Pas de compte ? Créez-en un". 

Le formulaire de création de compte se compose de deux parties :

* **Informations personnelles** : Le client doit y remplir ses informations personnelles : prénom, nom, adresse électronique, mot de passe et date de naissance. 
* **Abonnements :** Le client peut choisir de s'abonner à votre newsletter et de recevoir ou non vos offres partenaires. Veillez à n'afficher ces champs que si vous envoyez effectivement ce type de contenu. 

Une fois inscrit, le client pourra accéder à son compte client, où de nombreuses options sont accessibles. Le client pourra notamment ajouter une première adresse. Il s'agira de son adresse par défaut, mais il peut y avoir d'autres ! Si le client n'a qu'une seule adresse enregistrée, elle sera utilisée à la fois comme adresse de livraison et de facturation. Au cours du processus de commande, le client pourra toujours choisir d'utiliser une adresse différente. 

![](../.gitbook/assets/image%20%2832%29.png)

{% hint style="success" %}
La commande express permet aux visiteurs d'acheter des produits sans devoir forcément créer un compte. PrestaShop a toujours besoin de certaines informations essentielles pour la livraison ou le paiement, mais l'utilisateur n'aura jamais à créer de mot de passe.

Vous pouvez désactiver la commande express dansle back-office, sur la page paramètres de commande.
{% endhint %}

## Acheter un produit

Le processus d'achat sur un site PrestaShop peut suivre différent cheminements, mais ils amènent toujours à la même conclusion, appelée le "tunnel de conversion" dans le jargon de l'e-commerce : à partir du moment où le panier est plein et le client commence à lancer sa commande, il doit valider une suite d'écrans jusqu'à ce que sa commande soit validée et en cours de traitement.

On appelle cela un entonnoir de conversion parce que de nombreuses boutiques en ligne perdent des clients à cause de ce processus, qui peut s'avérer être long, compliqué ou se faire sur un trop grand nombre d'écrans de validation. Lisez la page de Wikipédia en anglais à ce sujet: [http://en.wikipedia.org/wiki/Conversion\_funnel](http://en.wikipedia.org/wiki/Conversion_funnel).

Ce processus est lancé quand le client clique soit sur le bouton "Commander" dans le panier \(sur n'importe quelle page\), soit sur le bouton "Suivant" sur le récapitulatif de commande \(sur la page "Mon panier"\), et suivra toujours la même séquence d'écrans.

Lorsqu'un client a ajouté tous les produits qu'il souhaite acheter à son panier et clique sur "Commander" le processus d'achat peut commencer. Si le client n'est pas connecté, il peut choisir de commander en tant qu'invité, de se créer un compte ou de se connecter. 

1. **Informations personnelles** : Si le client n'est pas connecté, il peut choisir de commander en tant qu'invité, de se créer un compte ou de se connecter.  
2. **Adresses** : Si aucune adresse n'a été préalablement enregistrée, le client devra remplir le formulaire de création d'adresse. Sinon, il pourra sélectionner l'adresse à laquelle il souhaite se faire livrer. Dans le cas où l'adresse de livraison et l'adresse de facturation seraient différentes, le client peut décocher la case "Utiliser la même adresse pour la facturation" et, au choix, sélectionner une adresse parmi celles déjà saisies, ou bien en saisir une nouvelle. 
3. **Mode de livraison** : C'est ici que le client doit choisir parmi les options de livraison et d'emballage. 
   * En fonction de ce que la boutique propose, le client peut choisir un paquet en matière recyclée et un emballage cadeau pour la commande. 
   * Le client peut profiter de cette étape s'il souhaite partager un message à propos de sa commande 
4. **Paiement** : Le client peut choisir plusieurs options de paiement, en fonction de ce que le vendeur a mis en place. Le client clique sur la méthode choisie, et en fonction de celle-ci, il est soit envoyé vers le gestionnaire du fournisseur tiers, ou bien vers une page de PrestaShop où l'utilisateur peut saisir les détails nécessaires, comme la validation avant d'afficher le chèque ou les informations bancaires.

   Les chèques et les cartes de crédit sont les options les plus courantes, mais PrestaShop facilite l'ajout de méthodes de paiement utilisant PayPal, Hipay ou d'autres fournisseurs tiers. Rendez-vous dans la page "Modules" du back-office pour découvrir tous les modules de paiement disponibles par défaut, et découvrez-en de nombreux autres sur le site Addons : [http://addons.prestashop.com/](http://addons.prestashop.com/).

5. **Validation et résumé** : Une fois que le client a tout validé et accepté les conditions générales de vente, sa commande est confirmée et il peut accéder au résumé de sa commande.  En fonction de la méthode de paiement choisie, certaines informations finales peuvent être envoyées au client, avec une notification de la confirmation par e-mail et un lien vers la page de support. Le client **doit** cliquer sur "Je confirme ma commande" afin de la voir validée.



