# Ce dont vous avez besoin

## Instructions de configuration rapides <a id="Cedontvousavezbesoin-Instructionsdeconfigurationrapides"></a>

Voici une synthèse de ce dont vous avez besoin pour commencer l’installation de PrestaShop 1.7. Vous trouverez, si nécessaire, des instructions plus détaillées dans les sections suivantes.

* Configuration requise :
  * PHP 7.1 ou version ultérieure.
    * Réglages utiles \(dans le fichier `php.ini`\) : 
      * `allow_url_fopen` réglé sur “On” \(Activé\), 
      * `register_globals` réglé sur “Off” \(Désactivé\)`,`
      * `upload_max_filesize` réglé sur “16M” \(ou plus\).
    * Extensions PHP indispensables \(dans le fichier `php.ini`\) : CURL, DOM, Fileinfo, GD, Intl, Mbstring, Zip, JSON, Iconv.
    * Outils serveur utiles : cron/crontab, Memcached.
  * MySQL 5.6 ou version ultérieure.
  * Pour un meilleur fonctionnement : 
    * Hébergeur Unix/Linux.
    * Serveur web Apache 2.2 \(ou version ultérieure\) ou serveur web Nginx.
      * Paramètres des modules Apache : 
        * `mod_rewrite` activé, 
        * `mod_security` désactivé,
        * `mod_auth_basic` désactivé.
    * Au moins 256 Mo de RAM dédiée à PHP. Plus la mémoire sera élevée, meilleures seront les performances.
* Codes d’accès à votre serveur FTP et à votre base de données MySQL.
  * Ces codes doivent vous être fournis par votre hébergeur si vous n’effectuez pas d’installation locale.
* Un éditeur de texte.
* Un client FTP.
* Un navigateur web récent \(si vous utilisez Internet Explorer : au moins IE9\).

Il vous faudra également connaître l’adresse web \(sur votre domaine\) depuis laquelle vous souhaitez vendre des produits

Consultez la page officielle dédiée à la configuration requise : [http://www.prestashop.com/fr/system-requirements](http://www.prestashop.com/en/system-requirements).

Une fois votre configuration prête, vous pouvez utiliser le guide d’installation : [http://doc.prestashop.com/pages/viewpage.action?pageId=51185382](ce-dont-vous-avez-besoin.md).

## Instructions de configuration détaillées

PrestaShop est une application web. Pour fonctionner, elle doit être installée sur un serveur web et a besoin d’un nom de domaine que vos visiteurs utiliseront pour accéder à votre boutique.

### Enregistrer un nom de domaine <a id="Cedontvousavezbesoin-Enregistrerunnomdedomaine"></a>

Avant de télécharger ou d’installer quoi que ce soit, vous devez offrir un toit à votre boutique en ligne PrestaShop. Il est constitué de deux éléments : un nom de domaine et un serveur web. Le nom de domaine est l’identifiant en ligne de votre site web, par exemple : [exemple.com](http://example.com/) ou [maboutiqueenligne.net](http://myonlineshop.net/). Il s’agit de la partie publique de votre serveur web et donc de votre boutique.

Vous devez acheter un nom de domaine pour votre boutique. Il se peut que vous en obteniez un en même temps que vous prenez un hébergement web : de nombreux hébergeurs offrent un nom de domaine gratuit à la création de chaque nouveau compte. Un nom de domaine peut être gratuit pendant un an ou pour toute la durée de votre contrat d’hébergement, ce qui permet de bénéficier facilement et directement d’une offre complète \(hébergement + nom de domaine\).

Les noms de domaine fournis par certains hébergeurs peuvent poser problème : si vous n’êtes pas satisfait du service, vous voudrez peut-être migrer votre boutique chez un meilleur hébergeur, ce qui nécessite de déplacer vos fichiers, vos données et votre nom de domaine vers ce dernier.

Les fichiers et les données sont faciles à déplacer, mais en fonction de l’hébergeur, vous pourriez avoir du mal à récupérer votre nom de domaine. Dans la mesure où l’hébergeur a acheté le nom de domaine pour vous, techniquement, le domaine lui appartient. L’hébergeur peut donc vous interdire de le transférer vers un autre hébergeur ou vous autoriser à le faire moyennant des frais. Comme le nom de domaine est votre marque et votre adresse sur Internet, vous devez vous plier aux règles de l’hébergeur.

C’est la raison pour laquelle il est souvent recommandé de générer votre nom de domaine auprès d’un bureau d’enregistrement indépendant \(voir : [https://fr.wikipedia.org/wiki/Bureau\_d%27enregistrement](http://en.wikipedia.org/wiki/Domain_name_registrar)\). Techniquement, vous ne pouvez jamais acheter un nom de domaine ; vous pouvez seulement le louer, la plupart du temps moyennant des frais annuels. Cela vous donne le droit d’utiliser ce nom de domaine, mais dès que vous cessez de payer, le nom de domaine ne vous appartient plus et peut être récupéré par n’importe qui.

En plus de payer l’enregistrement du nom de domaine, vous devrez payer l’hébergement sur Internet. Toutefois, vous restez libre de passer chez un meilleur hébergeur à tout moment sans surcoût : vous n’aurez qu’à modifier les adresses DNS du nom de domaine. La modification sera appliquée dans le monde entier dans un délai de 24 heures.

  
Si vous préférez obtenir votre nom de domaine auprès d’un bureau d’enregistrement indépendant, en voici quelques-uns auxquels vous pouvez faire confiance :

* Gandi : [http://en.gandi.net/](http://en.gandi.net/)
* Namecheap : [http://www.namecheap.com/](http://www.namecheap.com/)
* GoDaddy : [https://www.godaddy.com/](https://www.godaddy.com/)
* 1&1 IONOS : [https://www.ionos.fr/](https://www.ionos.fr/)

Il en existe beaucoup d’autres. Renseignez-vous auprès de vos amis !

### Trouver un hébergeur

Maintenant que vous avez un nom de domaine, il faut qu’il soit relié à PrestaShop. Cela signifie que les fichiers de PrestaShop doivent être hébergés sur un serveur web. Vous pouvez avoir votre propre serveur web, mais il est plus probable que votre boutique soit hébergée par un service d’hébergement Internet \(voir : [http://en.wikipedia.org/wiki/Internet\_hosting\_service](http://en.wikipedia.org/wiki/Internet_hosting_service)\) qui vous fournit un domicile en ligne moyennant un abonnement mensuel ou annuel.

Avant de lancer une boutique en ligne, vous devrez d’abord choisir un fournisseur d’hébergement. Presque tous les hébergeurs peuvent prendre en charge la solution PrestaShop de manière efficace. Toutefois, seuls quelques fournisseurs d’hébergement proposent des serveurs optimisés pour PrestaShop \(avec une fonction d’installation en 1 clic et une version à jour\). Voici notre[ liste de partenaires d’hébergement](https://www.prestashop.com/en/ecommerce-hosting).

Lorsque vous choisissez votre hébergeur, rappelez-vous une condition essentielle : l’hébergeur doit prendre en charge PHP 7.1 \(ou une version plus récente\), le langage de programmation dans lequel PrestaShop est écrit, et MySQL 5 \(ou une version plus récente\), le système de bases de données où PrestaShop stocke toutes ses données. Il y a d’autres exigences. Reportez-vous à la section “Exigences techniques” ci-après.

### Pré-requis techniques

PrestaShop est une application qui fonctionne sur un serveur web. Elle est rédigée dans le langage de programmation PHP. Elle stocke ses données sur un serveur MySQL.

PHP est un langage de programmation open source, principalement utilisé pour les applications web. Créé en 1995, il est depuis devenu le langage de programmation le plus utilisé par les développeurs web. Il utilise une syntaxe de type C qui permet aux développeurs de l’apprendre facilement.

MySQL est un système de gestion de bases de données open source. Également créé en 1995, il est désormais le système de bases de données le plus utilisé par les développeurs web. Il est basé sur le langage SQL, le langage de base de données le plus répandu.

  
Quel que soit le service d’hébergement que vous choisissez, les composants suivants doivent être installés sur votre serveur web :

* **Système** : Unix, Linux ou Windows. Unix est fortement recommandé.
* **Serveur web** : Serveur web Apache 2.2 ou version ultérieure.
* **PHP 7.1 ou version ultérieure**. 
* **MySQL 5.6 ou version ultérieure**.
* Au moins 256 Mo de RAM sur votre serveur.

PrestaShop peut également fonctionner avec un serveur web IIS 6.0 Microsoft ou une version ultérieure, et un serveur Nginx 1.0 ou une version ultérieure.

Vous trouverez plus d’informations pour les administrateurs système dans le [guide de l’administrateur système](ce-dont-vous-avez-besoin.md). Veillez à le lire !

### Outils <a id="Cedontvousavezbesoin-Outils"></a>

Vous aurez besoin de deux outils : un éditeur de texte, pour éditer les fichiers texte, et un client FTP, pour transférer les fichiers de votre machine vers votre serveur et vice versa.

#### Éditeur de texte <a id="Cedontvousavezbesoin-&#xC9;diteurdetexte"></a>

Voici quelques éditeurs de texte bien connus :

* Windows et OS X :
  * Sublime Text : [http://www.sublimetext.com/](http://www.sublimetext.com/)
  * Atom : [https://atom.io/](https://atom.io/)
* Unix/Linux :
  * Vim : [http://www.vim.org/](http://www.vim.org/)
  * Emacs : [http://www.gnu.org/software/emacs/](http://www.gnu.org/software/emacs/)

N'utilisez JAMAIS un logiciel de traitement de texte lorsque vous voulez modifier les fichiers de PrestaShop, comme Microsoft Word ou [OpenOffice.org](http://openoffice.org/) Write.

Client FTP

FTP est l’abréviation de “File Transfer Protocol”, un protocole standard utilisé pour transférer des fichiers depuis un ordinateur vers un hébergeur.

Dans ce guide, nous allons utiliser FileZilla, un client FTP gratuit et efficace pour Windows, Mac OS X et Linux. Téléchargez-le sur [http://filezilla-project.org/](http://filezilla-project.org/) et lancez l’installeur. Remarque : ne téléchargez pas FileZilla Server, mais uniquement FileZilla Client !

Une fois FileZilla installé, vous devrez le configurer avec les paramètres de connexion de votre serveur web, normalement fournis par votre hébergeur. Si vous n’avez pas reçu ces paramètres, demandez-les à votre hébergeur ou consultez votre dossier spam pour vérifier qu’ils ne s’y trouvent pas.

Les principaux paramètres nécessaires sont les suivants :

* **Un nom d’hôte** ou **une adresse IP** : emplacement du serveur FTP de votre espace d’hébergement.
* **Un nom d’utilisateur** : votre identifiant de compte d’hébergement unique.
* **Un mot de passe** : mesure de sécurité obligatoire.

Ouvrez FileZilla et le Gestionnaire de site. Vous pouvez le faire de trois manières différentes :

* Appuyez sur Ctrl-S.
* Cliquez sur l’icône “Ouvrir le Gestionnaire de site” située dans l’angle supérieur gauche.
* Ouvrez le menu “Fichier” et sélectionnez l’option “Gestionnaire de site...”.

Une fenêtre s’ouvre.

Pour ajouter votre espace d’hébergement au Gestionnaire de site :

1. Cliquez sur le bouton “Nouveau site”. Une nouvelle entrée est créée dans la liste des sites. Donnez-lui un nom facilement identifiable.
2. Sur le côté droit, dans l’onglet “Général”, saisissez les paramètres fournis par votre hébergeur : nom d’hôte, nom d’utilisateur et mot de passe. Vous n’avez normalement pas à modifier les autres paramètres par défaut, à moins que votre hébergeur ne vous le demande.
3. Une fois tous les champs correctement renseignés, cliquez sur le bouton “Connexion”. Cette opération permettra d’enregistrer votre site dans la liste et de vous connecter à votre compte pour que vous puissiez vérifier que tout fonctionne correctement.

Si FileZilla ne vous convient pas, voici quelques autres clients FTP connus :

* Windows :
  * CoreFTP : [http://www.coreftp.com/](http://www.coreftp.com/)
  * WinSCP : [http://winscp.net/](http://winscp.net/)
  * SmartFTP : [http://www.smartftp.com/](http://www.smartftp.com/)
* Mac OS X :
  * Cyberduck : [http://cyberduck.ch/](http://cyberduck.ch/)
  * Transmit : [http://www.panic.com/transmit/](http://www.panic.com/transmit/)
  * Fetch : [http://fetchsoftworks.com/fetch/](http://fetchsoftworks.com/fetch/)
* Unix/Linux :
  * gFTP : [http://gftp.seul.org/](http://gftp.seul.org/)
  * kasablanca : [http://kasablanca.berlios.de/](http://kasablanca.berlios.de/)
  * NcFTP : [http://www.ncftp.com/ncftp/](http://www.ncftp.com/ncftp/)

## Se préparer

Dans un premier temps, vous devez décider de l’endroit où héberger PrestaShop. Quatre possibilités s’offrent à vous par rapport à votre nom de domaine :

* Au niveau de la racine du domaine : [http://www.exemple.com/](http://www.example.com/)
* Dans un dossier : [http://www.exemple.com/boutique/](http://www.example.com/shop/)
* Dans un sous-domaine : [http://boutique.exemple.com/](http://store.example.com/)
* Dans le dossier d’un sous-domaine : [http://vêtements.exemple.com/boutique/](http://clothes.example.com/boutique/)

Grâce à la fonctionnalité multiboutique, vous pouvez avoir autant de boutiques que vous le souhaitez avec une seule installation de PrestaShop 1.7, chacune avec son propre nom de domaine si nécessaire. Tenez-en compte lorsque vous décidez de votre organisation.

  
 Quel que soit votre plan, la boutique par défaut résidera toujours à l’endroit où se trouve PrestaShop.

