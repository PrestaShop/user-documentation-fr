# Traductions

PrestaShop vous fournit un outil complet de traduction pour votre boutique. Il vous permet d'ajouter et de modifier les traductions de vos pages. Ainsi, vous êtes véritablement maître de votre boutique, et pouvez gérer la traduction des chaînes sans avoir à attendre que les traducteurs officiels publient leurs corrections. En effet, bien que PrestaShop 1.7 soit disponible dans de nombreuses langues, avec à la fois l'interface et la boutique traduites dans plus de 25 langues, certaines langues ne sont pas encore entièrement traduites.

Même si vous ne souhaitez pas utiliser les corrections des traducteurs, vous pourriez vouloir changer la formulation qu'ils ont utilisé \(moins formelle, moins verbeuse, etc.\), et personnaliser les différents textes disponibles. Ce faisant, vous adaptez votre site web à votre public : par exemple, une boutique de vêtements hip-hop n'utilisera pas les mêmes expressions qu'une boutique de vente de montres de luxe.

Le processus d'adaptation d'un logiciel à d'autres langues est appelé _internationalisation et localisation_, ou i18n et L10n.

La première étape est l'internationalisation, durant laquelle les développeurs choisissent le mécanisme à utiliser pour traduire leur logiciel. Toutes les chaînes du logiciel sont ensuite converties pour être exploitées par ce mécanisme. La seconde étape est la localisation, où les utilisateurs bilingues ou polyglottes traduisent les chaînes originales vers leur propre langue. La localisation peut également inclure la mise en place de données locales pour améliorer encore plus le logiciel pour les utilisateurs locaux. Vous pouvez en apprendre plus sur [Wikipédia](http://fr.wikipedia.org/wiki/Internationalisation_%28informatique%29).

L'équipe de PrestaShop a choisi de concevoir son propre outil intégré au logiciel, afin que quiconque disposant d'une installation de PrestaShop puisse personnaliser sa boutique en fonction de ses besoins. La traduction communautaire se faire à l'aide de Crowdin, situé à l'adresse [https://crowdin.net/project/prestashop-official](https://crowdin.net/project/prestashop-official). Rejoignez Crowdin et aidez-nous de sorte à ce que PrestaShop soit disponible dans votre langue!

Video - 5 questions à se poser avant de traduire sa boutique en ligne

 [![](../../../.gitbook/assets/52298021.png)](https://www.youtube.com/watch?v=Iw4lAuuA_pU)

## Modifier une traduction <a id="Traductions-Modifierunetraduction"></a>

L'outil le plus important de la page "Traductions" se trouve dans la section "Modifier les traductions". C'est ici que vous choisissez la traduction à modifier ou ajouter, afin de potentiellement en réécrire toutes les phrases si besoin était.

![](../../../.gitbook/assets/64225468.png)

Sélectionnez la partie de la traduction actuelle que vous voulez modifier :

* **Traductions du back office**. Le texte que vous voyez dans les pages d'administration de votre boutique
* **Traductions du thème**. Le texte que vos clients voient en parcourant votre boutique.
* **Traductions des modules installés**. Les chaînes utilisées par les modules installés. Notez que les modules présents mais pas installés n'apparaîtront pas dans l'outil.
* **Traductions des modèles d'e-mails**. Les chaînes utilisées par les e-mails envoyés par PrestaShop.
* **Autres traductions**. Cette catégorie est provisoire. Elle contient toutes les chaînes qui n'ont pas encore été identifiées comme provenant de l'une des catégories ci-dessus.

Si vous êtes à la recherche d'une chaîne précise, que ce soit dans la section "Back office" ou "Theme", mais que vous ne la trouvez pas, il se pourrait qu'elle soit dans la catégorie "Autres traductions".

Certaines catégories ont une seconde liste déroulante, qui donne les thèmes disponibles. Les thèmes PrestaShop ont leurs propres chaînes, mais peuvent aussi avoir leurs propres modules et modèle d'e-mail. Cette liste déroulante vous permet donc de choisir le thème avec lequel vous souhaitez travailler. Une fois votre sélection faite, choisissez la langue pour laquelle vous souhaitez modifier la traduction. Une nouvelle page s'ouvre alors, organisée en plusieurs sections. 

## Rechercher une expression <a id="Traductions-Rechercheruneexpression"></a>

En haut de la page, une barre de recherche vous permet de rechercher un mot, une chaîne ou une phrase que vous souhaiteriez modifier ou traduire. Sur la droite, vous verrez le nombre total d'expressions, ainsi que le nombre de celles qui ne sont pas encore traduites dans la catégorie \(back office, thème, etc.\).

![](../../../.gitbook/assets/64225469.png)

Renseignez l'expression recherchée et cliquez sur "Rechercher" pour lancer la recherche. Les expressions qui correspondent à votre recherche s'afficheront en dessous. Vous pouvez les modifier, ou les traduire si elles sont vides, puis cliquer sur "Enregistrer" pour sauvegarder vos modifications. En cliquant sur "Réinitialiser", vous remplacerez ce que vous avez pu rentrer par la traduction officielle de PrestaShop : cela restaurera la traduction initiale s'il y en avait une, ou supprimera la vôtre si vous en aviez ajouté une.

Référez-vous à l'arborescence qui s'affiche à gauche pour retrouver les résultats correspondant à votre recherche :

![](../../../.gitbook/assets/64225470.png)

## Parcourir les traductions <a id="Traductions-Parcourirlestraductions"></a>

La colonne de gauche est là pour vous aider à naviguer parmi les différentes expressions disponibles dans la catégorie que vous voulez modifier ou traduire. Cette navigation se base sur le concept de domaines de traduction : chaque chaîne ou expression dans PrestaShop se voit assigner un domaine de traduction. Ce domaine permet de donner un contexte pour la traduction, et permet de savoir où cette chaîne est affichée dans PrestaShop, et à quoi elle correspond \(texte d'aide, verbe d'action, etc.\).

Pour le back office et le thème, vous verrez deux domaines principaux, le second étant les modules. En effet, les modules ont du contenu qui s'affiche à la fois dans l'interface, et dans la boutique, aussi ces expressions sont disponibles quand vous cherchez à traduire votre back-office ou votre thème. À côté de chaque domaine, le nombre d'expressions manquantes pour ce domaine est affiché. Cela vous aide à savoir où aller si vous souhaitez compléter la traduction de PrestaShop. Pour voir les expressions contenus dans un domaine, cliquez sur le nom du domaine : les expressions s'afficheront sur la droite.

Domaines de traductions

Si de prime abord les domaines peuvent vous sembler confus, vous comprendrez rapidement comme ils fonctionnent et vous saurez rapidement y trouver votre chemin.

Chaque catégorie \(back office ou thème\) est elle-même divisée en sous-catégories fonctionnelles, qui correspondent à des sections et pages du back office \(ou du thème\).

Par exemple, pour le back office, les domaines suivants correspondent aux pages du même nom \(an anglais\) dans l'interface :

* _AdminCatalog, AdminModules, AdminDesign, AdminShipping, AdminPayment, AdminInternational, AdminShopParam_ et _AdminAdvParameters._
* _AdminOrdersCustomers_ rassemble les expressions des menus “Commandes”, “Clients” and “Service client”.

Chacun de ces domaines est encore divisé en trois sous-domaines, _Feature, Notification_ et _Help_, qui ont les significations suivantes :

* _Feature_ : tout ce qui est propre à une fonctionnalité de l'interface. Si vous êtes dans la catégorie "Shipping", le domaine Admin.Shipping.Feature regroupera toutes les expressions dans le menu "Livraison", et qui sont propre à ces pages en particulier.
* _Notification_ : tous les messages d'information, de succès, les notifications ou les erreurs spécifiques au domaine concerné.
* _Help_ : tous les messages d'aide et d'accompagnement pour ce domaine précis.

Et a contrario, certains domaines sont génériques et leurs chaînes sont transverses à toutes les pages du back office :

* _AdminNavigation_ pour toutes les chaînes du menu, footer, et header du back-office.
* _AdminActions_ rassemble tous les boutons ou liens sous forme de verbes d'actions que vous trouverez dans l'interface et qui sont génériques \("Annuler", "Enregistrer", "Supprimer", etc.\)
  * _AdminNotifications_ contient tous les avertissements, messages d'erreurs ou de succès qui sont standards et applicables à toutes les pages du back-office \(par exemple "Mise à jour réussie"\).
* _AdminGlobal_ englobe toutes les chaînes qui ne sont pas comprises dans les autres domaines, qui apparaissent dans plusieurs pages différentes du back-office et dans de nombreuses occurrences \("État", "Paramètres", "Activé", "Ventes", etc.\). 

La même logique va s'appliquer pour les domaines du thème :

* _ShopTheme_ et ses sous-niveaux \(Catalog, CustomerAccount, Checkout, Actions\) sont les chaînes du thème par défaut et de ses différentes sections fonctionnelles
* _ShopForms_ regroupe les libellés des différentes formulaires présents dans le thème
* _ShopNotification_ concerne tous les messages et notifications s'affichant sur votre boutique, que ce soit des erreurs ou succès.

## Modifier une traduction  <a id="Traductions-Modifierunetraduction.1"></a>

Quand vous ouvrez un domaine pour en voir les chaînes, vous pouvez modifier les traductions existantes, ou compléter celles qui seraient manquantes. Cliquer "Enregistrer" sauvegardera vos modifications. Cliquer "Réinitialiser" remplacera ce que vous avez pu rentrer par la traduction officielle de PrestaShop : cela restaurera la traduction initiale s'il y en avait une, ou supprimera la vôtre si vous en aviez ajouté une.

Certaines chaînes ont une syntaxe particulière, qui contient des variables comme `%s`, `%d`, `%1$s`, `%2$d`, etc.

Quand vous trouvez une chaîne avec une telle variable, cela signifie que PrestaShop la remplacera avec une valeur dynamique avant d'afficher la chaîne traduite. Par exemple, dans la chaîne "Your order on %s is complete.", `%s` sera remplacé par le nom de la boutique. C'est pourquoi vous devez conserver cette variable dans votre traduction finale. Par exemple, en français il faudra la traduire en "Votre commande sur %s a bien été enregistrée."

Techniquement, les variables permettent d'afficher la chaîne dans son ensemble, d'éviter de la disperser en plein de champs différents.

Dans le cas d'une chaîne avec variable, vous devriez vous assurer que le contenu de cette variable se trouvera dans le bon flot de la phrase, et éviter les traductions littérales.

Les variables numérotées \(`%1$s`, `%2$d`, etc.\) permettent aux traducteurs de réordonner les variables au sein de la chaîne tout en maintenant les informations de chacune. Ainsi, le traducteur français pourra au choix traduire "Order \#%1$d from %2$s" en "Commande n°%1$s du %2$s" ou "Le %2$s, commande n°%1$s".

![](../../../.gitbook/assets/64225471.png)

### Traduction des modules <a id="Traductions-Traductiondesmodules"></a>

Quand vous souhaitez traduire ou modifier le contenu d'un module précis, choisissez "Traduction des modules installés", puis sélectionnez le module qui vous intéresse. Une nouvelle page va s'ouvrir avec tout le contenu de ce module.

En fonction de la version pour laquelle ce module a été conçu \(1.7 ou 1.6\), l'interface de traduction peut être différente. En effet, certains modules utilisent le système de traduction propre à la 1.7, tel que décrit dans cette page, alors que d'autres utilisent toujours le système de la version 1.6. Leur page de traduction aura une présentation différente. Au final, les fonctionnalités sont les mêmes, et vous pourrez traduire ou modifier votre module de la même façon.

  
**Traduction des modèles d'e-mails**

La traduction des e-mails se fait un peu différemment des autres types de contenu.

Les chaînes sont rassemblées en groupes, mais ce ne sont plus de simples champs texte. Chaque e-mail dispose de deux modèles : un au format HTML, avec une mise en page et de la couleur, et un au format texte brut. Tandis que la version texte brut peut être modifiée directement dans le champ textuel, la version HTML ne peut être modifiée qu'en cliquant sur le bouton "Modifier ce modèle d'e-mail" situé en bas de la prévisualisation. Ce clic remplace la prévisualisation par un champ Wysiwyg \(_what you see is what you get_\), avec un éditeur complet \(basé sur [TinyMCE](http://www.tinymce.com/)\). En plus de modifier le texte, vous pouvez retoucher la mise en page comme bon vous semble. Vous pouvez par exemple changer les couleurs afin de s'adapter au style de votre boutique.

Notez que les modèles d'e-mails contiennent des variables, tels que `{lastname}` or `{shop_name}`, que PrestaShop remplace par la valeur réelle lors de l'envoi de l'e-mail. Assurez-vous de les conserver dans la traduction.

![](../../../.gitbook/assets/52298361.png)

## Ajouter / mettre à jour une langue <a id="Traductions-Ajouter/mettre&#xE0;jourunelangue"></a>

Les traductions de PrestaShop sont disponibles en packs, qui combinent toutes les catégories de traduction en un fichier zip. Certains packs de langue sont disponibles gratuitement depuis les serveurs de PrestaShop. PrestaShop s'occupe de télécharger le pack de langue, le décompresser et créer les sous-dossiers nécessaires dans le dossier `/translation` de votre installation.

![](../../../.gitbook/assets/64225472.png)

Vous pouvez également mettre à jour les langues installées, depuis les serveurs de PrestaShop.

## Exporter des traductions <a id="Traductions-Exporterdestraductions"></a>

Vous pouvez créer votre pack de langue en utilisant cet outil, soit dans le but de faire une sauvegarde de vos personnalisations, ou afin de partager vos traductions avec une autre installation de PrestaShop – l'une des vôtres ou d'un autre utilisateur.

![](../../../.gitbook/assets/64225473%20%281%29.png)

Sélectionnez simplement la langue et le thème de la traduction que vous souhaitez exporter, et cliquez sur le bouton "Exporter". Notez que le pack contiendra le thème qui est censé fonctionner avec la traduction.

## Copier <a id="Traductions-Copier"></a>

Vous pouvez copier le contenu d'une langue vers une autre. C'est particulièrement utile quand vous souhaitez remplacer la langue d'un thème par celle d'un autre thème.

![](../../../.gitbook/assets/64225473%20%281%29.png)

Choisissez la langue et le thème sources, puis la langue et le thème de destination, enfin cliquez sur le bouton "Copier". Dans la plupart des cas, la langue devrait être la même dans les deux listes déroulantes.

S'il y a déjà un dossier pour cette langue dans le thème de destination, il sera remplacé par les fichiers de la langue et du thème source. Vous préférerez peut-être créer d'abord une nouvelle langue pour le thème de destination, puis y copier la langue source.

