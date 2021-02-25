# Parcourir le front-office

Le front-office correspond à ce que les clients voient en parcourant votre boutique et tout le long du processus d’achat. 

En tant que marchand, vous devez connaître le front-office comme votre poche, afin de comprendre ce à quoi vos clients font face, comment se déroule une expérience d’achat type, quels sont les points de blocage, etc. 

Même si vous pensez connaître votre front-office par cœur, n’oubliez pas d’y retourner de temps en temps, comme si vous étiez un utilisateur qui visite le site pour la première fois. Parcourez votre boutique, achetez un produit, contactez le service client… mettez vous dans la peau de vos clients ! Vous pourriez faire des découvertes et noter quelques points à améliorer.  


## Le thème par défaut 

PrestaShop est livré avec un thème par défaut. Ce thème utilise un design simple et épuré, avec du blanc et du gris. Cette simplicité visuelle permet de s'adapter à presque tous les secteurs d'activité : voitures, photographies, antiquités, ou n'importe quoi d'autre ! Il a été conçu pour être facile à parcourir, ergonomique, conforme aux normes et adapté à toutes les tailles d'écran et à tous les appareils. 

Si vous avez installé PrestaShop avec ses données de démonstration, vous verrez des produits vestimentaires et des accessoires de maison. 

Notez que cette page de la documentation sera basée uniquement sur le thème par défaut et les paramètres et modules par défaut. En effet, l'activation d'autres modules ou l'utilisation d'un autre thème pourrait changer radicalement l'expérience d'achat. 

{% hint style="success" %}
Si vous souhaitez changer de thème, choisissez en un parmi le large choix de thèmes disponibles sur [PrestaShop Addons](https://addons.prestashop.com/). 
{% endhint %}

## Parcourir la boutique

### L'en-tête

L'en-tête est une fine barre de contenu en haut de la page, accessible depuis n'importe quelle page du front-office. 

![En-t&#xEA;te](../.gitbook/assets/image%20%2820%29.png)

L'en-tête est séparé en deux. 

La partie supérieure de l'en-tête contient :

* **Un lien vers la page de contact** 
* **Un sélecteur de langue :** Si plus d'une langue est disponible sur la boutique, le client peut choisir en quelle langue il souhaite afficher les pages du front-office.
* **Un sélecteur de devises :** Si plus d'une devise est disponible sur la boutique, le client peut choisir en quelle devise il souhaite voir s'afficher les prix des produits. Cela peut s'avérer très pratique au moment de comparer les prix avec d'autres boutiques à l'international. 
* **Un lien vers la page d'authentification :** Une fois connecté, le client a accès à son compte, et un lien "Déconnexion" apparaît à côté de son nom. 
* **Un lien vers le panier du client :** En un coup d'oeil, le client peut savoir combien d'articles il a dans son panier. Il peut également cliquer sur le bouton" Panier" pour accéder au contenu du panier et finaliser sa commande. 

![Partie sup&#xE9;rieure de l&apos;en-t&#xEA;te ](../.gitbook/assets/image%20%2821%29.png)

La partie inférieure de l'en-tête, plus large, contient :

* **Le logo de la boutique :** En cliquant sur ce logo, le client sera redirigé vers la page d'accueil de la boutique, peu importe la page sur laquelle il se trouve. N'oubliez pas de changer le logo par défaut en le remplaçant par votre propre logo personnalisé ! 
* **Le menu :** Par défaut, les catégories "Vêtements", "Accessoires" et "Art" sont affichées, et des sous-catégories apparaîssent au survol de la souris. Pour personnaliser le menu avec vos propres catégories, vous devez configurer le module "Menu principal". 
* **La barre de recherche :** La barre de recherche facilite la recherche sur votre boutique : une recherche à la bonne place et vos clients trouveront rapidement les articles qu'ils recherchent !

![Partie inf&#xE9;rieure de l&apos;en-t&#xEA;te](../.gitbook/assets/image%20%2818%29.png)

### Le pied de page

Le pied de page est séparé en deux parties.

![](../.gitbook/assets/image%20%2819%29.png)

➡La partie supérieure du pied de page contient un **bloc d'inscription à la newsletter** de votre boutique, permettant au client de recevoir des offres spéciales. Ce formulaire d'abonnement est géré par le module "Inscription à la newsletter". 

![Bloc d&apos;inscription &#xE0; la newsletter ](../.gitbook/assets/image%20%2822%29.png)

{% hint style="warning" %}
Veuillez noter que l'envoi de la newsletter est de votre ressort. Grâce au module "Newsletter", vous pourrez générer un fichier .csv contenant tous les clients enregistrés et leurs e-mails. Vous pourrez ensuite importer ce fichier .csv dans n'importe quel système d-e-mailing. 
{% endhint %}

➡La partie inférieure du pied de page donne accès à des pages qui pourraient être très utiles pour vos clients :

**Le bloc "Produits" permet d'accéder rapidement aux pages :**

* Promotions
* Nouveaux produits 
* Meilleures ventes

**Le bloc "Notre société" renvoie vers des pages d'informations :**

* Livraison
* Mentions légales
* Conditions d'utilisation
* A propos
* Paiement sécurisé
* Contactez-nous
* Plan du site
* Magasins

**Le bloc "Votre compte" contient des liens vers les pages principales du compte client \(ou la page d'authentification, s'il n'est pas connecté\).**  

* Informations personnelles 
* Retours produits
* Commandes
* Avoirs 
* Adresses

**Le bloc "Informations" contient toutes les informations relatives à votre boutique :**

* Le nom de la boutique
* L'adresse 
* Le numéro de téléphone
* L'e-mail 

### La colonne de gauche

La colonne de gauche du thème par défaut n'apparaît que sur une page de catégorie, lorsqu'elle est activée depuis le back office. 

#### Le bloc "Catégories"

Une catégorie est une façon hiérarchique de trier les produits : elle peut contenir un nombre illimité de sous-catégories, ce qui permet de passer facilement des listes de catégories générales aux produits plus spécifiques en suivant un chemin logique.

Une boutique PrestaShop peut avoir autant de catégories et de sous-catégories que nécessaire, avec un nombre infini de produits dans un niveau de catégorie donné. 

A noter : Toutes les catégories sont en fait des sous-catégories de la catégorie racine, "Accueil".

#### Le bloc "Filter par"

Filtrer leur recherche permet aux clients de trouver le produit qu'ils recherchent plus rapidement. Sur la colonne de gauche d'une page de catégorie, il est possible de préciser sa recherche en filtrant principalement par attributs, caractéristiques ou encore fourchette de prix. 

### La section centrale

La section centrale change en fonction des choix des clients. 

#### La page d'accueil 

La page d'accueil par défaut donne au client un large aperçu du magasin et de ses possibilités. Cette page d'accueil doit être pensée à destination de nouveaux clients. Que souhaitez-vous mettre en avant ? 

En haut de la page, il y a un carrousel d'images : trois images défilent. Vous pouvez utilisez ce carrousel pour mettre en avant vos nouvelles collections, des promotions à ne pas louper, etc. 

En dessous, sont affichés les produits populaires de votre boutique. 

Vous pouvez également personnaliser une bannière, ou encore ajouter un bloc de texte. N'hésitez pas à consulter la documentation pour apprendre à [configurer la page d'accueil de votre boutique](https://prestashop.gitbook.io/documentation-francaise-1-7/guide-utilisateur/optimiser-boutique/personnaliser-apparence-boutique/theme-et-logo#configuration-page-daccueil). 

Page de liste de produits 

Catégories, tags, marques, fournisseurs, recherche, page des promotions, page des meilleures ventes ou page des nouveaux produits : PrestaShop propose de nombreux chemins vers un produit. Et à chaque fois  une liste de produits est présentée. 

Malgré les différences de contenu, ces listes sont très similaires, afin de rester familières même pour les nouveaux venus. Ils affichent tous une liste de produits concernés organisée en grille, avec : Une vignette, Les drapeaux de rabais ou d'état en haut à gauche, Nom du produit Prix du produit Cette vue en liste permet au client de voir en un coup d'œil les principales informations sur les produits alors qu'il sait déjà tout ce dont il a besoin sur un produit, ce qui permet un processus de décision plus rapide. Le survol du produit déclenche une animation rapide, affichant les différentes combinaisons et un lien "Quick view". En cliquant sur le lien "Quick view", une fenêtre pop-up s'ouvre avec les principales informations sur le produit et un bouton "Ajouter au panier".





