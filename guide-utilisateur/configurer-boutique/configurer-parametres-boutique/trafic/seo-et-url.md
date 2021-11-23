# SEO et URL

Les outils sur cette page vous permettent d'améliorer la présence de votre site PrestaShop sur les moteurs de recherche, et donc d'atteindre plus de clients potentiels.

SEO signifie "Search Engine Optimization" (soit "Optimisation pour les Moteurs de Recherche"). Il s'agit d'un ensemble de techniques et de meilleures pratiques créées dans le but d'améliorer le référencement d'un site web sur les moteurs de recherche. Vous pouvez en apprendre plus en lisant la page [Wikipédia](http://fr.wikipedia.org/wiki/Optimisation\_pour\_les\_moteurs\_de\_recherche). URL signifie "Uniform Resource Locator" (soit "Localisateur Uniforme de Ressource"). Il s'agit de l'adresse en ligne d'une page web. Vous pouvez en apprendre plus en lisant la page [Wikipédia](http://fr.wikipedia.org/wiki/Uniform\_Resource\_Locator).

Par défaut, les adresses les plus profondes de PrestaShop (c'est-à-dire les pages spécifiques plutôt que le nom de domaine) ne donnent d'information ni à l'acheteur, ni aux moteurs de recherche : une adresse comme [www.myprestashop.com/product.php?id\_product=27](http://www.myprestashop.com/product.php?id\_product=27) n'aide pas le visiteur à savoir quel produit se trouve sur cette page. Les URL simplifiées (ou "Friendly URLs") permettent d'améliorer cela, en permettant d'écrire par exemple [www.myprestashop.com/2-music-players/27-ipod-nano-green](http://www.myprestashop.com/2-music-players/27-ipod-nano-green).

Comme vous pouvez le voir dans le second exemple, les catégories comme les produits peuvent disposer d'une URL simplifiée : dans l'exemple ci-dessus, `id_category=2` `2-music-players`, et `id_product=27` devient `27-ipod-nano-green`. Par défaut, le numéro d'identifiant ne peut pas être enlevé. En revanche, les mots peuvent aussi bien être générés par le nom de la catégorie et/ou du produit qu'écrits à la main. Tout se passe directement dans la page de configuration du produit ou de la catégorie (dans le menu "Catalogue") : l'adresse simplifiée peut se trouver directement dans la page principale de configuration d'une catégorie et dans l'onglet "SEO" de la page de configuration d'un produit.

Il y a d'autres pages individuelles que PrestaShop installe et qui pourront certainement bénéficier d'adresses simplifiées : les pages CMS, les pages de compte de l'utilisateur, les pages ayant un contenu généré automatiquement. La page "SEO & URL" vous donne la liste de ces pages, et vous permet de modifier leurs URL simplifiées ainsi que leurs balises méta (titre, description, mot-clé).

![](../../../../.gitbook/assets/64225651.png)

Les URL simplifiées ne fonctionnent qu'avec un serveur configuré pour reconnaître la réécriture d'URL (par le biais de la fonctionnalité `mod_rewrite` du serveur Apache, par exemple). Assurez-vous que le vôtre est bien configuré (si besoin, demandez à votre hébergeur !) car si ce n'est pas le cas et que vous activez les adresses simplifiées, votre boutique peut devenir totalement inaccessible à vos clients.

### Exemple : réglages SEO de la page d'accueil <a href="seoeturl-exemple-reglagesseodelapagedaccueil" id="seoeturl-exemple-reglagesseodelapagedaccueil"></a>

Pour changer les balises méta de la page d'accueil, vous devez simplement ouvrir la page "SEO & URL" et cliquer sur la page "index" pour modifier librement les informations importantes sur le SEO.

![](../../../../.gitbook/assets/52298417.png)

Quelques conseils :

* Le nom par défaut de la page d'accueil est celui de la boutique, et donc le champ titre de l'index est vide. Si vous mettez dans du contenu dans le champ, il remplacera le titre complet de la page d'accueil. Le nom de la boutique est configuré pour sa part lors de l'installation de PrestaShop, et peut être modifié dans l'onglet "Coordonnées" de la section Paramètres de la boutique > Contact de votre back office.
* Utilisez une description courte : un court paragraphe de texte suffit.
* Pour ajouter un mot-clé, cliquez dans le champ et validez en appuyant sur la touche "Envoi". Vous pouvez enlever des mots-clés en cliquant sur la croix rouge.
* Vous n'avez pas à ajouter d'URL réécrite s'il y en a déjà une.

Notez que si votre boutique a déjà été indexée par Google ou n'importe quel autre moteur de recherche, l'apparition de vos modifications dans les résultats de recherche peut prendre du temps... soyez patient !

## Ajouter une nouvelle URL simplifiée <a href="seoeturl-ajouterunenouvelleurlsimplifiee" id="seoeturl-ajouterunenouvelleurlsimplifiee"></a>

Les URL simplifiées sont à définir dans les pages de configuration de chaque produit, catégorie ou encore page CMS. La présente page de création ne sert que pour certaines pages automatiques, vous n'aurez la plupart du temps pas à vous en soucier.

Faites en sorte de remplir les champs pour toutes les langues disponibles sur votre boutique : c'est non seulement extrêmement utile pour vos utilisateurs internationaux mais certains moteurs de recherche peuvent également faire bon usage de telles informations locales.

![](../../../../.gitbook/assets/52298418.png)

Cliquez sur le bouton "Créer" pour atteindre le formulaire de création. Il contient une poignée de champs :

* **Page**. La liste déroulante vous donne toutes les pages pouvant bénéficier d'une URL simplifiée.
* **Titre de la page**. Le titre de cette page, qui apparaîtra dans les résultats des moteurs de recherche.
* **Méta description**. Une présentation de la page en quelques mots, afin d'attirer le regard du visiteur. Elle apparaîtra dans les moteurs de recherche.
* **Méta mots-clés**. Vous pouvez définir des mots-clés afin de référencer votre site sur les moteurs de recherche. Vous pouvez en donner plusieurs : saisissez les mots, appuyez sur la touche "Entrée" de votre clavier et vous verrez vos mots-clés encapsulés dans un bloc, avec une petite croix rouge pour les effacer.
* **URL réécrite**. C'est ici que vous configurez vos adresses simplifiées. Faites court et descriptif, n'utilisez que des lettres et des chiffres, et remplacez les espaces (" ") par des tirets ("-").

## Configuration des URL <a href="seoeturl-configurationdesurl" id="seoeturl-configurationdesurl"></a>

Les principales options des URL simplifiées sont :

*   **URL simplifiée**. Modifiez cette option _si vous savez que votre serveur peut utiliser la réécriture d'URL_ ! Si ce n'est pas le cas, laissez l'option sur "Non".

    Il se peut que s'affiche la notification "_Le mode de réécriture d'URL (mod\_rewrite) n'est pas activé sur votre serveur, ou il est impossible de vérifier la configuration. Pour utiliser les URL réécrites, vous devez activer ce mode._" Dans ce cas, PrestaShop ne peut pas détecter votre configuration serveur, mais cela ne veut pas dire que la fonctionnalité ne peut pas fonctionner. Vous devez la tester vous-mêmes.
* **URL accentuées.** PrestaShop peut générer des adresses web avec des caractères spéciaux, pour les produits ayant un nom avec des caractères non ASCII (accents, etc.). Vous pouvez désactiver cette option ici.
*   **Rediriger vers l'URL canonique**. Une page PrestaShop donnée peut avoir plusieurs adresses web, la plupart du temps suite à la prise en compte de paramètres. Par exemple, [`http://example.com/product.php?id=5&option1`](http://example.com/product.php?id=5\&option1) et [`http://example.com/product.php?id=5&option2`](http://example.com/product.php?id=5\&option2) pointent vers le même produit, avec une simple différence. Étant donné qu'il est préférable qu'un produit n'aie qu'une adresse web et non plusieurs dupliquées entre elles, vous devriez activer l'option des adresses canoniques.\
    \
    __

    Les adresses canoniques sont une manière d'éliminer les contenus dupliqués que vous avez créés – ce qui peut faire considérablement chuter votre référencement, étant donné que le contenu est alors considéré comme étant du spam. Pour éviter que les moteurs de recherche vous voient comme un spammeur, PrestaShop utilise la balise `rel="canonical"` qui indique quelle est la page originale d'un contenu. Bien qu'il soit vivement recommandé d'activer cette option, elle dépend également de votre thème et de son implantation de la balise `rel="canonical"` dans l'en-tête HTML. Si besoin, demandez plus d'information au concepteur du thème.

    \
    _Nouveauté depuis la 1.7.6 !_ Par défaut, c'est l'adresse canonique d'un produit qui est appelée et, dans le cas d'un produit avec déclinaison, l'adresse canonique pointe vers la déclinaison par défaut.\
    \
    Il y a trois options :

    * _Aucune redirection._ Vous risquez d'avoir des adresses dupliquées.
    * _301 Déplacé Définitivement._ Renvoie le code HTTP 301, en pointant vers l'adresse principale et en notifiant les moteurs de recherche que c'est là la seule adresse à prendre en compte. C'est l'option qu'on vous recommande lorsque vous avez terminé vos changements.
    * _302 Déplacé Temporairement._ Renvoie le code HTTP 302, en pointant vers l'adresse principale et en notifiant les moteurs de recherche que l'adresse principale peut changer plus tard.
* **Désactiver l'option Apache MultiViews**. Apache est le serveur web le plus populaire, et c'est selon toute probabilité celui qui est utilisé pour votre hébergement (même si vous devriez vérifier vous-même). L'option Multiviews active un système de négociation de contenu, grâce auquel le serveur Web tente d'envoyer au visiteur la page qui correspond le mieux à sa langue, ce quelle que soit l'adresse Web de la page. Malheureusement, cette option peut être incompatible avec les URL simplifiées. Si c'est le cas, désactivez simplement les Multiviews avec cette option.
* **Désactiver le module apache "mod\_security"**. `mod_security` est un module du serveur Apache qui sert de pare-feu, protégeant ainsi vos serveurs des intrusions. Il peut cependant bloquer certaines fonctionnalités importantes, et même produire des erreurs en fonction de la configuration. Dans ces cas, désactivez le module ici.\
  \


![](../../../../.gitbook/assets/64225652.png)

## URL de la boutique <a href="seoeturl-urldelaboutique" id="seoeturl-urldelaboutique"></a>

Dans cette section, vous pouvez voir et modifier certains de vos réglages serveur par défaut :

* **Domaine**. Le domaine principal de votre boutique.
* **Domaine SSL**. Le domaine sécurisé (`https://`) de votre boutique.
* **Chemin**. Le dossier où vous avez installé PrestaShop. Si c'est à la racine de votre domaine, utilisez "`/`".

La plupart du temps, nous vous conseillons de ne pas toucher ces champs sans savoir exactement ce que vous faites. En effet, parfois une seule modification peut rendre votre boutique inaccessible.

![](../../../../.gitbook/assets/64225653.png)

## Format des URL <a href="seoeturl-formatdesurl" id="seoeturl-formatdesurl"></a>

_N'est affiché que si les URL simplifiées sont activées._

Vous pouvez changer la manière dont les URL simplifiées sont générées, en modifiant la "route" vers la ressource de votre boutique. Par exemple, la route par défaut pour afficher un produit est `{category:/}{id}-{rewrite}{-:ean13}.html`, ce qui donne `/summer-dresses/7-printed-chiffon-dress.html`. Vous pouvez changer cette route pour utiliser `{manufacturer:/}{id}-{rewrite:/}` afin d'obtenir `/fashion-manufacturer//7-printed-chiffon-dress/`

Huit champs sont disponibles par défaut et chacun est accompagné d'une liste de mots-clés. Certains mots-clés sont obligatoires, ils sont indiqués par une "\*".

![](../../../../.gitbook/assets/64225654.png)

Une fois tous ces champs mis à jour, n'oubliez pas d'enregistrer vos modifications !

## Options SEO <a href="seoeturl-optionsseo" id="seoeturl-optionsseo"></a>

_Nouveauté depuis la 1.7.5.1 !_ PrestaShop vous permet désormais d'activer ou non l'affichage des attributs d'un produit dans la balise titre de ce produit.

![](../../../../.gitbook/assets/64225656.png)

## Génération du fichier robots.txt <a href="seoeturl-generationdufichierrobots.txt" id="seoeturl-generationdufichierrobots.txt"></a>

Un fichier `robots.txt` vous permet de bloquer des robots et autres logiciels automatiques qui parcourent le web afin d'y trouver plus de pages à ajouter au serveur de leur société. Vous voudrez sûrement donner les pleins accès à certains robots, comme ceux de Google ou de Yahoo!, tandis que d'autres devront trouver porte fermée, comme les robots de spam, les voleurs de contenus, les collecteurs d'adresses e-mails, etc. Notez que les robots les plus malicieux ne respectent pas les directives de ce fichier, qui ne sont pas imposées.

L'outil de génération de `robots.txt` de PrestaShop créée simplement un fichier avec des directives d'exclusion pour les fichiers et dossiers qui ne sont pas censés être publics et donc pas censés être indexés. Ces directives s'appliquent à tous les robots, bons et mauvais : le fichier généré utilise la chaîne "User-agent: \*"

En cliquant sur le bouton "Générer le fichier robots.txt", vous remplacez tout fichier `robots.txt` par le nouveau. Ainsi, si vous souhaitez ajouter vos propres règles, faites-le après que PrestaShop a généré le fichier.

![](../../../../.gitbook/assets/64225655.png)

Vidéo - Améliorez le référencement de votre boutique en ligne

[![](../../../../.gitbook/assets/64225669.jpg)](https://www.youtube.com/watch?v=mt0GtxNJVBM)
