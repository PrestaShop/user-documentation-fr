# Thème et logo

Tout est dit dans le titre : cette page vous permet de gérer vos thèmes, et c'est ici que vous pouvez mettre à jour vos différents logos.

* [Adaptation du thème Right-To-Left \(RTL\)](theme-et-logo.md#adaptation-du-theme-right-to-left-rtl)
* [Votre thème actuel](theme-et-logo.md#votre-theme-actuel)
  * [Configurer la disposition des pages](theme-et-logo.md#configurer-la-disposition-des-pages)
  * [Sélectionner le thème pour la boutique &lt;nom de la boutique&gt;](theme-et-logo.md#selectionner-le-theme-pour-la-boutique-less-than-nom-de-la-boutique-greater-than)
  * [Importer un thème](theme-et-logo.md#importer-un-theme)
  * [Exporter un thème](theme-et-logo.md#exporter-un-theme)
  * [En direct de PrestaShop Addons !](theme-et-logo.md#en-direct-de-prestashop-addons)
* [Configuration page d'accueil ](theme-et-logo.md#configuration-page-daccueil)
* [Personnalisation avancée : le thème parent / enfant](theme-et-logo.md#personnalisation-avancee-le-theme-parent-enfant)
  * [Créer un thème enfant](theme-et-logo.md#creer-un-theme-enfant)

## Adaptation du thème Right-To-Left \(RTL\)

_Nouveauté depuis PrestaShop 1.7.3 !_ PrestaShop supporte désormais les langues qui se lisent de droite à gauche. Cela signifie que le back office comme les thèmes sont compatibles en Right-To-Left \(RTL\). En outre, un outil accessible depuis cette page permet aux marchands le désirant de générer une feuille de style au format RTL. En d'autres termes, si vous voulez adapter votre front office en RTL, c'est ici que ça se passe ! Ce sera particulièrement utile si vous souhaitez adresser vos produits sur les marchés arabes, israélien ou encore iranien. 

![](../../../.gitbook/assets/64225411.png)

Logos

Modifier le logo de votre boutique est souvent l'une des première étape de la personnalisation de votre boutique. Grâce aux différentes options disponibles, vous pouvez non seulement modifier le logo principal de votre boutique \(visible sur la page d'accueil\), mais également les logos présents ailleurs sur votre boutique :

* * **Logo de l'en-tête**. Le logo qui apparaîtra sur toutes les pages de votre boutique.
  * **Logos pour les factures et les e-mails**. Les logos qui apparaîtront respectivement sur les e-mails de notification, et les factures de votre boutique.
  * **Favicon**. La favicône de votre boutique, affichée à la gauche des onglets de votre navigateur web.   ![](../../../.gitbook/assets/64225406.png)  

Le thème par défaut utilise un logo "Classic". Il est très fortement recommandé de changer toutes les instances de ce logo et de les remplacer par le vôtre !

En mode multiboutique, vous pouvez appliquer ces modifications à toutes les boutiques ou à un groupe de boutiques d'un coup, à l'aide du sélecteur multistore.

## Votre thème actuel

La troisième section de cette page vous sert de rappel du thème que vous utilisez actuellement, avec ses informations :

* Nom du thème ;
* Version du thème ;
* Nom de l'auteur du thème ;
* Miniature du thème.  

![](../../../.gitbook/assets/64225407.png)

### Configurer la disposition des pages

Selon les options offertes par votre thème, vous avez la possibilité de personnalisé la mise en page de ses différents types de pages. Choisissez combien de colonnes afficher, de quelle taille et autres détails liés à la structure de votre thème. En cliquant sur "Choisir la mise en page", vous arrivez sur une nouvelle page qui liste les différents types de pages de votre thème \(page produit, page catégorie, panier, etc.\). Pour chaque type de page, vous pouvez choisir la mise en page par défaut.

Pour le thème par défaut de PrestaShop, "Classic", voici les options possibles :

* Pleine largeur - Aucune colonne, idéal pour les pages exemptes de toute distraction, comme les page produits
* 3 colonnes - Une colonne centrale et deux colonnes latérales
* 2 colonnes, petite colonne à gauche - Deux colonnes, dont une plus petite à gauche.
* 2 colonnes, petite colonne à droit - Deux colonnes, dont une plus petite à droite.

Cliquez sur "Enregistrer" pour que vos choix soient pris en compte.

### Sélectionner le thème pour la boutique &lt;nom de la boutique&gt;

C'est dans cette section que vous allez choisir le thème actuel de votre boutique, dès lors que vous avez au moins deux thèmes disponibles. L'interface vous présente une liste de miniatures des thèmes actuellement disponibles sur votre installation PrestaShop, et il vous revient de choisir le thème que vous souhaitez utiliser.

Cette section affiche simplement les miniatures des thèmes disponibles, avec leurs noms. Placez le curseur de votre souris sur la miniature pour afficher un menu avec deux options :

* **Utiliser ce thème**. Cela remplacer votre thème actuel par ce thème.
* **Supprimer ce thème**. Cela supprimera les fichiers de ce thème de votre serveur web.  

En mode multiboutique, vous ne pouvez pas appliquer un thème à toutes les boutiques ou à un groupe de boutiques ; vous devez sélectionner une boutique dans le sélecteur multiboutique, puis choisir un thème.

### Importer un thème

Vous pouvez ajouter un thème et l'installer \(avec ses modules attachés\) grâce au bouton "Ajouter un thème", qui ouvre un nouvel écran. Cet écran vous présente trois méthodes pour installer un nouveau thème. Un dernier bouton vous amène au formulaire de création de thème, présenté ci-dessus.

![](../../../.gitbook/assets/64225408.png)

Quelle que soit la méthode, le processus reste le même : indiquer l'emplacement de l'archive Zip du thème, puis cliquer sur "Enregistrer". Seule la source du fichier Zip diffère :

* **Importer depuis l'ordinateur** : utilisez l'explorateur de fichiers pour trouver l'archive.
* **Importer depuis le web** : indiquez directement l'adresse web de l'archive.
* **Importer depuis le serveur FTP** : à l'aide d'un client FTP, mettez l'archive en ligne dans le dossier suivant : `/themes/`.

Cliquez de nouveau sur "Suivant" pour valider votre choix: le thème est maintenant installé. Puis cliquez sur "Suivant" une dernière fois. Une dernière page de confirmation vous présente toutes les modifications appliquées à votre site PrestaShop. Cliquez sur "Terminer" pour mettre fin au processus.

### Exporter un thème

Cette section n'est disponible que si vous avez au moins un thème installé sur votre site PrestaShop. Elle vous donne une méthode pour exporter votre module dans un format correct \(en particulier, avec un fichier de configuration qui fonctionne\).

Il peut se révéler très utile d'exporter un thème, que ce soit pour le sauvegarder par sécurité, pour créer une archive à donner à un ami, ou pour vendre le thème sur la [marketplace Addons](http://addons.prestashop.com/fr). L'exportateur ne fait pas que générer une archive Zip complète de votre thème, il ajoute également de nombreuses informations dans des fichiers XML, qui se révèleront très utiles lors de la mise à disposition sur Addons, et lors de l'import dans une boutique PrestaShop.

Choisissez un thème et cliquez sur le bouton "Exporter ce thème". Un formulaire de configuration apparaît, avec lequel vous pouvez configurer les paramètres du thème : auteur, nom du thème, version de compatibilité, modules liés \(s'il en a\), etc. Une fois tous les paramètres en place, cliquez sur le bouton "Enregistrer". Vous obtiendrez rapidement un fichier à télécharger à l'aide de votre navigateur. Enregistrez-le sur votre disque dur, puis donnez un nom compréhensible à ce fichier au lieu de la suite de caractère. Partant de là, vous pouvez facilement partager ce thème, et s'il s'agit de votre propre création, vous pouvez également le mettre en vente sur la [marketplace Addons](http://addons.prestashop.com/fr).

### En direct de PrestaShop Addons !

Si vous êtes à la recherche d'un nouveau thème, PrestaShop Addons est ce qu'il vous faut ! Grâce à cette section, vous pouvez consulter les thèmes les plus populaires pour trouver de l'inspiration. Si vous voulez voir davantage de thèmes, cliquez sur "Découvrir tous les thèmes" pour être redirigé vers l'ensemble des thèmes présentés sur Addons, la marketplace officielle de PrestaShop.

Vous pouvez cliquer sur chaque image pour aller sur la page individuelle de chaque thème et obtenir plus d'information. Vous pouvez aussi utiliser la bar de recherche en bas de page pour trouver un thème selon une thématique qui correspond à votre site et votre marque.

## Configuration page d'accueil 

_Nouveauté depuis PrestaShop 1.7.4 !_ On est très fiers de vous la présenter : la cartographie de la page d'accueil ! Chaque partie du front office est contrôlée par un module spécifique. En d'autres termes, une simple modification à effectuer sur une partie de la page d'accueil renvoie obligatoirement à la section "Modules" du back office, sur laquelle il faut ensuite sélectionner le bon module pour, enfin, accéder à sa page de configuration... pas très intuitif, n'est-ce pas ? Désormais, grâce à la double visualisation de cette cartographie du front office, la personnalisation du thème est plus rapide, et les marchands sont plus heureux !

![](../../../.gitbook/assets/56688755.png)

Sur la partie gauche, vous trouverez une illustration simplifiée de la page d'accueil, réalisée pour vous permettre de repérer la partie à modifier en un coup d'oeil. Sur la partie gauche, vous obtiendrez en miroir la sélection de modules à configurer.

Le front office est divisé en sept catégories différentes : menu, glissière, produits en page d'accueil, bloc de texte, bannière, newsletter & réseaux sociaux et footer. Chacune de celles-ci se déploie pour afficher les fonctionnalités du coeur et les modules natifs que contient la zone sélectionnée. Ces fonctionnalités peuvent être installées, configurées ou désactivées. En cliquant sur le bouton "Configurer", notez que c'est la page de configuration de la fonctionnalité qui s'ouvre.

## Personnalisation avancée : le thème parent / enfant

Cette fonctionnalité a été introduite avec la version 1.7 de PrestaShop. Elle est utile si vous souhaitez modifier légèrement un thème \(ajouter un bloc par exemple\), tout en continuant de bénéficier de ses mises à jours. En effet, si vous modifiez un thème directement depuis son dossier, si vous veniez à mettre à jour ce thème, il se peut que vos modifications soient incompatibles avec la mise à jour, et que vous puissiez en bénéficier.

![](../../../.gitbook/assets/56688756.png)

Grâce à un thème enfant, vous pouvez ainsi personnaliser votre thème tout en profitant de ses dernières nouveautés. 

L'utilisation d'un thème enfant est un peu technique. Vous avoir plus de détails sur l'utilisation d'un thème enfant, consultez la documentation technique : [https://devdocs.prestashop.com/1.7/themes/reference/template-inheritance/parent-child-feature](https://devdocs.prestashop.com/1.7/themes/reference/template-inheritance/parent-child-feature/)

### Créer un thème enfant

Assurez-vous que le thème que voulez utiliser comme parent se trouve bien dans le dossier `/themes.` Ensuite vous devez créer un nouveau dossier avec un thème minimal, contentant uniquement les fichiers suivants, que vous pouvez copier du thème parent :

![](../../../.gitbook/assets/64225592.png)

Une fois que vous avez ces fichier, dans le fichier du thème enfant `theme.yml`,vous devez préciser quel thème doit être considéré comme le thème parent. Dans l'exemple ci-dessous, nous avons choisi le thème PrestaShop par défaut, Classic. La valeur doit être le nom technique du thème \(c'est à dire, le nom de son dossier\). Ajouter ainsi les informations suivantes au fichier `theme.yml` :

![](../../../.gitbook/assets/64225412.png)

Vous pouvez maintenant utiliser ce thème et le modifier à souhait.

Votre thème est-il si bien que d'autres marchants pourraient vous l'acheter ? Vous pouvez le vendre sur [Addons](http://addons.prestashop.com/fr), la place de marché officielle des thèmes et modules PrestaShop.

