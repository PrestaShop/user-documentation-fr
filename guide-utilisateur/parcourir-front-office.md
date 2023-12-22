# Parcourir le front-office

![](<../.gitbook/assets/recent updates (1).png>)

:arrow\_right:[Contribuer](https://prestashop.gitbook.io/howtocontribute/)

Le front-office est la partie visible de votre site. Cela correspond à ce que les clients voient en parcourant votre boutique et tout le long du processus d’achat.&#x20;

En tant que marchand, il est indispensable que vous connaissiez parfaitement le front-office de votre boutique car c'est ce qui va vous permettre de vous mettre à la place de vos visiteurs : de vivre ce à quoi vos clients font face quand ils naviguent sur votre site, comment se déroule leur expérience d’achat, quels peuvent être leurs points de blocage, etc.&#x20;

Même si vous pensez connaître votre front-office par cœur, n’oubliez pas d’y retourner de temps en temps comme si vous étiez un utilisateur qui visite le site pour la première fois. Parcourez votre boutique, achetez un produit, contactez le service client… mettez vous dans la peau de vos clients ! Vous pourriez faire des découvertes et noter quelques points à améliorer.&#x20;

Notez que cette page de la documentation sera basée uniquement sur le thème, les paramètres et les modules par défaut. En effet, l'activation d'autres modules ou l'utilisation d'un autre thème pourrait changer radicalement l'expérience d'achat.&#x20;

{% hint style="success" %}
Si vous souhaitez changer de thème, choisissez en un parmi le large choix de thèmes disponibles sur [PrestaShop Addons](https://addons.prestashop.com/fr/3-themes-prestashop).&#x20;
{% endhint %}

## Le thème par défaut&#x20;

![](<../.gitbook/assets/image (24).png>)

PrestaShop est livré avec un thème par défaut qui utilise un design simple et épuré, en gris et blanc. Ce minimalisme permet de s'adapter à presque tous les secteurs d'activité. Il a été conçu pour être facile à parcourir, ergonomique, conforme aux bonnes pratiques web et adapté à toutes les tailles d'écran, à tous les appareils.&#x20;

Si vous avez installé PrestaShop avec ses données de démonstration, vous verrez des produits vestimentaires et des accessoires de maison.&#x20;

## Parcourir la boutique

### L'en-tête

L'en-tête est une fine barre de contenu en haut de la page, accessible depuis toutes les pages du front-office.&#x20;

L'en-tête est divisé en deux parties.&#x20;

La partie supérieure de l'en-tête contient :

![Partie supérieure de l'en-tête ](<../.gitbook/assets/image (18).png>)

* **Un lien vers la page de contact**&#x20;
* **Un sélecteur de langues :** si plus d'une langue est disponible sur la boutique, le client peut choisir en quelle langue il souhaite naviguer.
* **Un sélecteur de devises :** si plus d'une devise est disponible sur la boutique, le client peut choisir en quelle devise il souhaite voir s'afficher les prix des produits. Cela peut s'avérer très pratique au moment de comparer les prix avec d'autres boutiques à l'international.&#x20;
* **Un lien vers la page d'authentification :** une fois connecté, le client a accès à son compte et un lien "Déconnexion" apparaît à côté de son nom.&#x20;
* **Un lien vers le panier du client :** en un coup d'oeil, le client peut savoir combien d'articles il y a dans son panier. Il peut également cliquer sur le bouton "Panier" pour accéder au contenu du panier et finaliser sa commande.&#x20;

La partie inférieure de l'en-tête, plus large, contient :

![Partie inférieure de l'en-tête](<../.gitbook/assets/image (19).png>)

* **Le logo de la boutique :** en cliquant sur ce logo, le client sera automatiquement redirigé vers la page d'accueil de la boutique. N'oubliez pas de changer le logo par défaut en ajoutant le vôtre depuis la page Design > Theme & Logo du back-office !&#x20;
* **Le menu :** par défaut, les catégories "Vêtements", "Accessoires" et "Art" sont affichées, et des sous-catégories apparaîssent au survol de la souris. Pour personnaliser le menu avec vos propres catégories, vous devez configurer le module "Menu principal".&#x20;
* **La barre de recherche :** indispensable pour faciliter la recherche sur votre boutique, elle permet aux clients de trouver rapidement les articles de leur choix grâce à des mots-clés.

{% hint style="info" %}
L'option de recherche approximative ("fuzzy search") prend désormais en compte les éventuelles fautes de frappe des entrées recherchées par vos visiteurs !&#x20;
{% endhint %}

### La section centrale&#x20;

La page d'accueil par défaut donne au client un large aperçu de la boutique et de ses possibilités. Que souhaitez-vous mettre en avant à vos clients ?

En haut de la page, il y a un carrousel d'images : trois images défilent. Vous pouvez configurer ce carrousel à l'aide du module du même nom pour mettre en avant vos nouvelles collections, des promotions à ne pas louper, etc.

![](https://media.giphy.com/media/2oUFsps8xUl4H2TK80/giphy.gif)

En dessous du carrousel sont affichés les produits populaires de votre boutique.&#x20;

Vous pouvez également personnaliser une bannière ou encore ajouter un bloc de texte. N'hésitez pas à consulter la documentation dédiée pour apprendre à [configurer les pages de votre boutique. ](optimiser-boutique/personnaliser-apparence-boutique/theme-et-logo.md#configuration-des-pages)

### Le pied de page

Le pied de page est divisé en deux parties.

![](<../.gitbook/assets/image (22).png>)

:arrow\_right:La partie supérieure du pied de page contient un **bloc d'inscription à la newsletter** de votre boutique, permettant aux clients de recevoir des offres spéciales. Ce formulaire d'abonnement est géré par le module "Inscription à la newsletter".&#x20;

![Bloc d'inscription à la newsletter ](<../.gitbook/assets/image (21).png>)

{% hint style="info" %}
Veuillez noter que l'envoi de la newsletter est de votre ressort. Grâce au module "Newsletter", vous pourrez générer un fichier .csv contenant tous les clients enregistrés et leurs e-mails. Vous pourrez ensuite importer ce fichier dans n'importe quel système d'e-mailing.&#x20;
{% endhint %}

:arrow\_right:La partie inférieure du pied de page contient 4 blocs donnant accès à des pages très utiles pour vos clients :

{% tabs %}
{% tab title="PRODUITS" %}
**Le bloc "Produits" permet d'accéder rapidement aux pages suivantes :**

* Promotions
* Nouveaux produits&#x20;
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
**Le bloc "Votre compte" redirige vers les pages principales du compte client (ou la page d'authentification, si le client n'est pas connecté) :** &#x20;

* Informations personnelles&#x20;
* Retours produits
* Commandes
* Avoirs&#x20;
* Adresses
{% endtab %}

{% tab title="INFORMATIONS" %}
**Le bloc "Informations" contient toutes les informations relatives à votre boutique :**

* Le nom de la boutique
* L'adresse&#x20;
* Le numéro de téléphone
* L'e-mail&#x20;
{% endtab %}
{% endtabs %}

### Les pages catégories

#### La colonne de gauche

![En rouge le bloc "Catégorie", en bleu le bloc "Filtrer par"](<../.gitbook/assets/image (32).png>)

**Le bloc "Catégorie"**

Une catégorie est une façon hiérarchique de trier les produits : elle peut contenir un nombre illimité de sous-catégories, ce qui permet de passer facilement de listes générales à des produits plus spécifiques en suivant un chemin logique.

Une boutique PrestaShop peut avoir autant de catégories et de sous-catégories que nécessaire, avec un nombre infini de produits dans un niveau de catégorie donné.&#x20;

Sur les pages catégories, dans la colonne de gauche, les clients peuvent voir dans quelle catégorie ou sous-catégorie ils se trouvent.&#x20;

A noter : Toutes les catégories sont en fait des sous-catégories de la catégorie racine, "Accueil". Vous pouvez configurer les catégories depuis votre back-office, sur la page Catalogue > Catégories.

{% content-ref url="vendre/gerer-catalogue/gerer-categories.md" %}
[gerer-categories.md](vendre/gerer-catalogue/gerer-categories.md)
{% endcontent-ref %}

**Le bloc "Filter par"**

Filtrer leur recherche permet aux clients de trouver le produit qu'ils recherchent plus rapidement. Sur la colonne de gauche d'une page de catégorie, il est possible de préciser sa recherche en la filtrant par attributs, caractéristiques ou encore fourchette de prix. Ce bloc peut être configuré via le module "Navigation à Facette".&#x20;

#### **L'en-tête de catégorie**

![](<../.gitbook/assets/image (33).png>)

Les catégories peuvent comporter une image d'en-tête avec une description. Vous pouvez configurer cet en-tête depuis votre back-office sur la page Catalogue > Catégories.

### L**es l**istes de produits&#x20;

Les listes de produits sont identiques sur PrestaShop, quelle que soit la nature de la page concernée (nouveaux produits, meilleures ventes, pages catégories, etc.). Les produits sont organisés sous forme de grille, avec :

* Une image miniature
* Les bandeaux de promotion ou d'état, en haut à gauche de l'image
* Le nom du produit
* Le prix du produit&#x20;

![](<../.gitbook/assets/image (37).png>)

Cette présentation sous forme de liste permet au client de voir en un coup d'œil les principales informations sur les produits, accélérant alors le processus de décision.&#x20;

Au survol de la souris, le client peut cliquer sur la loupe pour accéder à un aperçu rapide du produit. Il aura alors accès, en plus des informations précédemment énoncées, à la description du produit, et pourra ajouter le produit à son panier après avoir sélectionné les attributs (s'il y en a) et saisi la quantité souhaitée.&#x20;

![](<../.gitbook/assets/image (27) (1).png>)

**Le tri des produits**

Les produits peuvent être triés selon le prix (croissant ou décroissant), le nom (de A à Z ou de Z à A) ou par pertinence.&#x20;

### La page produit

![](<../.gitbook/assets/image (34).png>)

La page produit met en avant les informations saisies depuis la page Catalogue > Produits de votre back-office. Selon le thème utilisé, une page de produit peut être très complète, avec des informations détaillées, ou simplement présenter les informations essentielles.&#x20;

Le thème par défaut permet d'afficher une ou plusieurs images du produit. À côté des images, apparaissent d'autres informations relatives au produit : le nom du produit, le prix et les éventuelles réductions, ainsi qu'un court récapitulatif.

Juste en dessous de ces informations produit, les clients peuvent choisir parmi les déclinaisons disponibles (s'il y en a) et sélectionner la quantité souhaitée.&#x20;

En dessous du bouton d'ajout au panier, des éléments de réassurance permettent d'informer vos clients des différentes politiques de paiement, de livraison, de retours, etc. Pour modifier ces informations, vous devez configurer le module "Réassurance".

Enfin, en bas à droite de la page, un bloc affiche deux onglets :

**Description :** ici apparaît une description complète du produit, telle qu'elle a été saisie dans la fiche produit du back-office.

**Détails du produit :** cet onglet n'apparaît que si des caractéristiques ont été associées au produit depuis le back-office, par exemple la marque ou la composition.

Pour plus d'informations sur la configuration de la page produit, n'hésitez pas à visiter la[ page de documentation dédiée](vendre/gerer-catalogue/gerer-produits.md).

### **Le panier**

Depuis l'en-tête, le client peut savoir combien d'articles sont dans son panier. En cliquant sur le bouton "Panier", le client accède au contenu du panier et peut finaliser sa commande.

![Page "Panier"](<../.gitbook/assets/image (35).png>)

Un résumé du contenu du panier s'affiche. Après avoir vérifié que le contenu de sa commande est bien correct, le client peut cliquer sur le bouton "Commander". Il est alors redirigé vers le tunnel de commande.

## Acheter un produit

Une fois le panier rempli de tous les articles souhaités et le processus de commande enclenché, le client devra valider une suite d'étapes jusqu'à la validation de sa commande.

PrestaShop fait le nécessaire pour que le processus d'achat soit **rapide et efficace**. Ce dernier se déroule en 5 étapes :

1. **Informations personnelles** : si le client n'est pas connecté, il peut choisir de commander en tant qu'invité, de se créer un compte ou de se connecter. \

2. **Adresses** : si aucune adresse n'a été préalablement enregistrée, le client doit remplir le formulaire de création d'adresse. Sinon, il peut directement sélectionner l'adresse à laquelle il souhaite se faire livrer. Dans le cas où l'adresse de livraison et l'adresse de facturation seraient différentes, le client peut décocher la case "Utiliser la même adresse pour la facturation" et, au choix, sélectionner une adresse parmi celles déjà saisies, ou bien en saisir une nouvelle.\

3. **Mode de livraison** : c'est ici que le client doit choisir parmi les options de livraison et d'emballage.&#x20;
   * En fonction de ce que la boutique propose, le client peut choisir un paquet en matière recyclée et/ou un emballage cadeau pour sa commande.&#x20;
   * Le client peut profiter de cette étape s'il souhaite partager un message à propos de sa commande.\

4.  **Paiement** : le client peut choisir plusieurs options de paiement en fonction de ce que le vendeur a mis en place. Le client clique sur la méthode choisie et, selon celle-ci, il est soit envoyé vers le gestionnaire du fournisseur tiers, ou bien vers une page de PrestaShop où il peut saisir les détails nécessaires.

    PrestaShop facilite l'ajout de méthodes de paiement comme PayPal, Hipay ou d'autres fournisseurs tiers. Rendez-vous dans la page "Modules" du back-office pour découvrir tous les modules de paiement disponibles nativement, et découvrez-en de nombreux autres sur la [marketplace Addons](http://addons.prestashop.com/).


5. **Validation et résumé** : une fois que le client a tout validé et accepté les conditions générales de vente, sa commande est confirmée et il peut accéder au résumé de sa commande. En fonction de la méthode de paiement choisie, certaines informations finales peuvent être envoyées au client, avec une notification de la confirmation par e-mail et un lien vers la page de support. Le client doit cliquer sur "Je confirme ma commande" afin de la voir validée.

## Créer un compte client

{% hint style="success" %}
PrestaShop permet aux visiteurs de votre boutique de se créer une compte **simplement** et **rapidement** !&#x20;
{% endhint %}

En cliquant sur "Connexion" dans l'en-tête, le visiteur est redirigé vers une page d'authentification. S'il n'a pas de compte, il peut s'en créer un depuis cette même page. Le formulaire de création de compte se compose de deux parties :

* **Informations personnelles** : le client indique ses informations personnelles (nom, prénom, e-mail, mot de passe et date de naissance). Cette fonctionnalité est gérée par le module "Customer Sign In Link".&#x20;
* **Abonnements :** le client peut choisir de s'abonner à votre newsletter et de recevoir ou non vos offres partenaires. Veillez à n'afficher ces champs que si vous envoyez effectivement ce type de contenu.&#x20;

Une fois inscrit, le client accéde à son compte client où de nombreuses options sont accessibles. Le client peut notamment ajouter une première adresse - son adresse par défaut mais il peut en avoir d'autres ! Si le client n'a qu'une seule adresse enregistrée, elle sera utilisée à la fois comme adresse de livraison et de facturation. Au cours du processus de commande, le client peut toujours choisir d'utiliser une adresse différente.&#x20;

![](<../.gitbook/assets/image (26) (1).png>)

{% hint style="success" %}
La commande express (option accessible dans les paramètres de commande du back-office) permet aux visiteurs d'acheter des produits sans avoir à créer de compte. Les informations essentielles à la livraison ou au paiement restent requises mais le client n'aura jamais à créer de mot de passe.
{% endhint %}
