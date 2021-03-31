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
Si vous souhaitez changer de thème, choisissez en un parmi le large choix de thèmes disponibles sur [PrestaShop Addons](https://addons.prestashop.com/fr/3-themes-prestashop). 
{% endhint %}

## Parcourir la boutique

### L'en-tête

L'en-tête est une fine barre de contenu en haut de la page, accessible depuis n'importe quelle page du front-office. 

![En-t&#xEA;te](../.gitbook/assets/image%20%2824%29.png)

L'en-tête est séparé en deux. 

La partie supérieure de l'en-tête contient :

![Partie sup&#xE9;rieure de l&apos;en-t&#xEA;te ](../.gitbook/assets/image%20%2825%29.png)

* **Un lien vers la page de contact** 
* **Un sélecteur de langue :** Si plus d'une langue est disponible sur la boutique, le client peut choisir en quelle langue il souhaite afficher les pages du front-office.
* **Un sélecteur de devises :** Si plus d'une devise est disponible sur la boutique, le client peut choisir en quelle devise il souhaite voir s'afficher les prix des produits. Cela peut s'avérer très pratique au moment de comparer les prix avec d'autres boutiques à l'international. 
* **Un lien vers la page d'authentification :** Une fois connecté, le client a accès à son compte, et un lien "Déconnexion" apparaît à côté de son nom. 
* **Un lien vers le panier du client :** En un coup d'oeil, le client peut savoir combien d'articles il y a dans son panier. Il peut également cliquer sur le bouton" Panier" pour accéder au contenu du panier et finaliser sa commande. 

La partie inférieure de l'en-tête, plus large, contient :

![Partie inf&#xE9;rieure de l&apos;en-t&#xEA;te](../.gitbook/assets/image%20%2818%29.png)

* **Le logo de la boutique :** En cliquant sur ce logo, le client sera redirigé vers la page d'accueil de la boutique, peu importe la page sur laquelle il se trouve. N'oubliez pas de changer le logo par défaut en le remplaçant par votre propre logo personnalisé ! 
* **Le menu :** Par défaut, les catégories "Vêtements", "Accessoires" et "Art" sont affichées, et des sous-catégories apparaîssent au survol de la souris. Pour personnaliser le menu avec vos propres catégories, vous devez configurer le module "Menu principal". 
* **La barre de recherche :** La barre de recherche facilite la recherche sur votre boutique : une recherche à la bonne place et vos clients trouveront rapidement les articles qu'ils recherchent !

{% hint style="success" %}
Nouveauté 1.7.7 : L'option "Fuzzy search" améliore l'expérience client et le taux de conversion de votre site en prenant en compte les entrées mal orthographiées ou erronées. Par défaut, cette option est activée dans votre back-office \(Paramètres de la boutique &gt; Rechercher\)
{% endhint %}

### La section centrale

#### La page d'accueil 

La page d'accueil par défaut donne au client un large aperçu de la boutique et de ses possibilités. Cette page d'accueil doit être pensée à destination de nouveaux clients. Que souhaitez-vous mettre en avant ? 

En haut de la page, il y a un carrousel d'images : trois images défilent. Vous pouvez utiliser ce carrousel pour mettre en avant vos nouvelles collections, des promotions à ne pas louper, etc. 

![](https://media.giphy.com/media/2oUFsps8xUl4H2TK80/giphy.gif)

En dessous, sont affichés les produits populaires de votre boutique. 

Vous pouvez également personnaliser une bannière, ou encore ajouter un bloc de texte. N'hésitez pas à consulter la documentation pour apprendre à [configurer la page d'accueil de votre boutique](https://prestashop.gitbook.io/documentation-francaise-1-7/guide-utilisateur/optimiser-boutique/personnaliser-apparence-boutique/theme-et-logo#configuration-page-daccueil). 

### Le pied de page

Le pied de page est séparé en deux parties.

![](../.gitbook/assets/image%20%2823%29.png)

➡La partie supérieure du pied de page contient un **bloc d'inscription à la newsletter** de votre boutique, permettant aux clients de recevoir des offres spéciales. Ce formulaire d'abonnement est géré par le module "Inscription à la newsletter". 

![Bloc d&apos;inscription &#xE0; la newsletter ](../.gitbook/assets/image%20%2828%29.png)

{% hint style="info" %}
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

### Les pages catégories

#### La colonne de gauche : 

![En rouge le bloc &quot;Cat&#xE9;gorie&quot;, en bleu le bloc &quot;Filtrer par&quot;](../.gitbook/assets/image%20%2832%29.png)

**Le bloc "Catégorie"**

Sur les pages catégories, dans la colonne de gauche, les clients peuvent voir dans quelle catégorie ou sous-catégorie ils se trouvent. 

Une catégorie est une façon hiérarchique de trier les produits : elle peut contenir un nombre illimité de sous-catégories, ce qui permet de passer facilement des listes de catégories générales aux produits plus spécifiques en suivant un chemin logique.

Une boutique PrestaShop peut avoir autant de catégories et de sous-catégories que nécessaire, avec un nombre infini de produits dans un niveau de catégorie donné. 

A noter : Toutes les catégories sont en fait des sous-catégories de la catégorie racine, "Accueil". Vous pouvez configurer ces catégories depuis votre back-office, sur la page Catalogue &gt; Catégories.

**Le bloc "Filter par"**

Filtrer leur recherche permet aux clients de trouver le produit qu'ils recherchent plus rapidement. Sur la colonne de gauche d'une page de catégorie, il est possible de préciser sa recherche en la filtrant par attributs, caractéristiques ou encore fourchette de prix. 

**L'en-tête de catégorie**

![](../.gitbook/assets/image%20%2833%29.png)

Les catégories peuvent comporter une image d'en-tête avec un message d'introduction**.** Vous pouvez configurer cet en-tête depuis votre back-office sur la page Catalogue &gt; Catégories.

**Le tri des produits**

Les produits d'une catégorie peuvent être triés selon le prix \(croissant ou décroissant\), le nom \(de A à Z ou de Z à A\) ou par pertinence. 

### L**es l**istes de produits 

Toutes les listes de produits sur PrestaShop se ressemblent, peu importe la page sur laquelle elles se trouvent \(Nouveaux produits, meilleures ventes, page catégories, etc.\)

Les produits sont organisés sous forme de grille, avec :

* Une image miniature
* Les bandeaux de promotion ou d'état, en haut à gauche de l'image
* Le nom du produit
* Le prix du produit 

![Exemple de liste de produits ](../.gitbook/assets/image%20%2822%29.png)

Cette présentation sous forme de liste permet au client de voir en un coup d'œil les principales informations sur les produits, accélérant alors le processus de décision. 

Au survol de la souris, le client peut accéder à un "aperçu rapide" du produit. Il aura alors accès, en plus des informations précédemment énoncées, à la description du produit, et pourra ajouter le produit à son panier après avoir choisi parmi les attributs \(s'il y en a\) et saisi la quantité souhaitée. 

![](../.gitbook/assets/image%20%2827%29%20%281%29.png)

### La page produit

![](../.gitbook/assets/image%20%2834%29.png)

La page produit met en avant les informations que vous aurez saisies depuis votre back-office, sur la page Catalogue &gt; Produits \(Edition et création\). 

Selon le thème utilisé, une page de produit peut être très complète, avec des informations détaillées, ou simplement présenter les informations essentielles. 

Le thème par défaut permet de mettre en avant une image du produit, mais vous pouvez en ajouter plusieurs ! Les visiteurs de votre boutique pourront facilement faire défiler les images disponibles sur la page. 

A côté des images, apparaissent d'autres informations essentielles relatives au produit : Le nom du produit, le prix et les éventuelles réductions, ainsi qu'un court récapitulatif.

Juste en dessous, les clients peuvent choisir parmi les combinaisons disponibles \(s'il y en a\) et sélectionner la quantité souhaitée. 

En dessous du bloc panier, le bloc "Réassurance" permet d'informer vos clients des différentes politiques de paiement, de livraison, de retours, etc. Pour modifier ces informations, vous devez configurer le module "Réassurance".

En bas de la page du produit, on peut voir des onglets. Les plus courants sont les suivants : 

Description : Ici apparaît une description complète du produit, telle qu'elle a été saisie sur la page produit du back-office.

Détails du produit : Cet onglet n'apparaît que si des caractéristiques ont été attribuées au produit depuis le back office, par exemple la marque ou la composition.

Pour plus d'informations sur la configuration de la page produit, n'hésitez pas à visiter la[ page de documentation dédiée](vendre/gerer-catalogue/gerer-produits.md).

### **Le panier**

Depuis l'en-tête, le client peut savoir combien d'articles il y a dans son panier. En cliquant sur le bouton" Panier", le client accède au contenu du panier et peut finaliser sa commande.

![Page &quot;Panier&quot;](../.gitbook/assets/image%20%2835%29.png)

Un résumé du contenu du panier s'affiche. Après avoir vérifié que le contenu de sa commande est bien correct, le client peut cliquer sur le bouton "Commander". Il est alors redirigé vers la page "Commande"

➡ Pour la suite du processus, voir[ comment acheter un produit](parcourir-front-office.md#acheter-un-produit) ci dessous. 

## Acheter un produit

Une fois le panier rempli de tous les articles souhaités et le processus de commande enclanché, le client devra valider une suite d'écrans jusqu'à la validation de sa commande. C'est ce que l'on appelle dans le jargon du e-commerce "l'entonnoir de conversion". 

On appelle cela un entonnoir de conversion parce que de nombreuses boutiques en ligne perdent des clients à cause de ce processus, qui peut s'avérer être long, compliqué ou se faire sur un trop grand nombre d'écrans de validation. 

PrestaShop fait le nécessaire pour que le processus d'achat soit **rapide et efficace**. Ce dernier se déroule en 5 étapes :

1. **Informations personnelles** : Si le client n'est pas connecté, il peut choisir de commander en tant qu'invité, de se créer un compte ou de se connecter.  
2. **Adresses** : Si aucune adresse n'a été préalablement enregistrée, le client devra remplir le formulaire de création d'adresse. Sinon, il pourra sélectionner l'adresse à laquelle il souhaite se faire livrer. Dans le cas où l'adresse de livraison et l'adresse de facturation seraient différentes, le client peut décocher la case "Utiliser la même adresse pour la facturation" et, au choix, sélectionner une adresse parmi celles déjà saisies, ou bien en saisir une nouvelle. 
3. **Mode de livraison** : C'est ici que le client doit choisir parmi les options de livraison et d'emballage. 
   * En fonction de ce que la boutique propose, le client peut choisir un paquet en matière recyclée et un emballage cadeau pour la commande. 
   * Le client peut profiter de cette étape s'il souhaite partager un message à propos de sa commande 
4. **Paiement** : Le client peut choisir plusieurs options de paiement, en fonction de ce que le vendeur a mis en place. Le client clique sur la méthode choisie, et en fonction de celle-ci, il est soit envoyé vers le gestionnaire du fournisseur tiers, ou bien vers une page de PrestaShop où il peut saisir les détails nécessaires.

   PrestaShop facilite l'ajout de méthodes de paiement comme PayPal, Hipay ou d'autres fournisseurs tiers. Rendez-vous dans la page "Modules" du back-office pour découvrir tous les modules de paiement disponibles nativement, et découvrez-en de nombreux autres sur la [marketplace Addons](http://addons.prestashop.com/).

5. **Validation et résumé** : Une fois que le client a tout validé et accepté les conditions générales de vente, sa commande est confirmée et il peut accéder au résumé de sa commande.  En fonction de la méthode de paiement choisie, certaines informations finales peuvent être envoyées au client, avec une notification de la confirmation par e-mail et un lien vers la page de support. Le client doit cliquer sur "Je confirme ma commande" afin de la voir validée.

## Créer un compte client

{% hint style="success" %}
Afin de limiter au maximum les pertes dans le tunnel de conversion, PrestaShop permet aux visiteurs d'une boutique de se créer une compte **simplement** et **rapidement** ! 
{% endhint %}

En cliquant sur "Connexion" dans l'en-tête, le visiteur est redirigé vers la page d'authentification, où il peut se connecter. 

S'il a besoin de créer un nouveau compte, il peut cliquer sur "Pas de compte ? Créez-en un". 

Le formulaire de création de compte se compose de deux parties :

* **Informations personnelles** : Le client doit y remplir ses informations personnelles : prénom, nom, adresse électronique, mot de passe et date de naissance. 
* **Abonnements :** Le client peut choisir de s'abonner à votre newsletter et de recevoir ou non vos offres partenaires. Veillez à n'afficher ces champs que si vous envoyez effectivement ce type de contenu. 

Une fois inscrit, le client pourra accéder à son compte client, où de nombreuses options sont accessibles. Le client pourra notamment ajouter une première adresse. Il s'agira de son adresse par défaut, mais il peut y en avoir d'autres ! Si le client n'a qu'une seule adresse enregistrée, elle sera utilisée à la fois comme adresse de livraison et de facturation. Au cours du processus de commande, le client pourra toujours choisir d'utiliser une adresse différente. 

![](../.gitbook/assets/image%20%2826%29%20%281%29.png)

{% hint style="success" %}
La commande express permet aux visiteurs d'acheter des produits sans devoir forcément créer un compte. PrestaShop a toujours besoin de certaines informations essentielles pour la livraison ou le paiement, mais l'utilisateur n'aura jamais à créer de mot de passe.

Vous pouvez désactiver la commande express dans le back-office, sur la page paramètres de commande.
{% endhint %}

