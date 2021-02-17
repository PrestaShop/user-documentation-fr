# Informations complémentaires

## Garder une version d’essai sous la main ! <a id="Informationscompl&#xE9;mentaires-Garderuneversiond&#x2019;essaisouslamain!"></a>

Après avoir terminé la configuration de votre boutique d’après vos souhaits, mais avant son ouverture officielle au public acheteur, nous vous recommandons **vivement** d’installer une version d’essai locale sur votre ordinateur personnel \(à l’aide de [WAMP](http://en.wikipedia.org/wiki/Comparison_of_WAMPs) pour Windows, [MAMP](http://en.wikipedia.org/wiki/MAMP) pour Mac, ou [LAMP](http://en.wikipedia.org/wiki/LAMP_%28software_bundle) pour Linux, ou [XAMPP](http://www.apachefriends.org/en/xampp.html) pour n’importe laquelle de ces plateformes\), ou ailleurs sur votre serveur d’hébergement.

Cette deuxième instance servira d’environnement de préparation de la production où vous pourrez effectuer toutes les modifications de votre boutique en ligne PrestaShop sans affecter la version active. De cette façon, en cas d’erreur, votre boutique restera inchangée.

Après avoir confirmé que votre version d’essai fonctionne normalement, copiez la version d’essai sur la version active. Il est préférable de le faire après les heures de trafic élevé en désactivant correctement et temporairement votre boutique depuis le back-office de PrestaShop.

## Vérifier la bibliothèque GD <a id="Informationscompl&#xE9;mentaires-V&#xE9;rifierlabiblioth&#xE8;queGD"></a>

La [bibliothèque GD](http://www.boutell.com/gd/) permet à PrestaShop de retravailler les images que vous mettez en ligne, notamment de les redimensionner.

Sur une installation par défaut de PHP, la bibliothèque GD doit être activée. Toutefois, si ce n’est pas le cas, les instructions standard de Windows sont :

1. Dans le répertoire racine de votre dossier PHP, ouvrez le fichier `php.ini`.
2. Désactivez le commentaire de la ligne `extension=php_gd2.dll` \(à peu près au milieu du fichier, au milieu d’une longue liste d’extensions\) en supprimant le “;” au début de la ligne.
3. Redémarrez les services PHP.

Si vous n’avez pas accès au fichier `php.ini` \(ce qui est souvent le cas en hébergement partagé\), contactez votre hébergeur pour lui faire part de vos besoins.

## Activer PHP 5.6+ <a id="Informationscompl&#xE9;mentaires-ActiverPHP5.6+"></a>

Pour installer PrestaShop, PHP 5.6+ doit être activé. La compatbilité est étendue jusqu'à PHP 7.2 mais ne tentez pas d'exécuter PrestaShop à l'aide de PHP 7.3, cela ne fonctionnera pas.

N’hésitez pas à publier sur [GitHub](https://github.com/PrestaShop) \(vous aurez besoin d’un compte\) un rapport de bogue pour obtenir des conseils afin de faire fonctionner PrestaShop sur votre service d’hébergement. Nous les ajouterons à ce guide à mesure que nous les recevrons.

Voici une liste des procédures que nous connaissons...

### 1&1 IONOS <a id="Informationscompl&#xE9;mentaires-1&amp;1IONOS"></a>

Ajoutez cette ligne à votre fichier `.htaccess` :

```text
AddType x-mapp-php5 .php
```

Pour la réécriture d'URL, ajoutez ces lignes :

```text
Options +FollowSymLinks
RewriteEngine On
```

### Free.fr <a id="Informationscompl&#xE9;mentaires-Free.fr"></a>

Ajoutez cette ligne à votre fichier `.htaccess` :

```text
php 1
```

### OVH <a id="Informationscompl&#xE9;mentaires-OVH"></a>

Ajoutez cette ligne à votre fichier `.htaccess` :

```text
SetEnv PHP_VER 5
```

Pour désactiver les variables globales :

```text
SetEnv REGISTER_GLOBALS 0
```

### GoDaddy <a id="Informationscompl&#xE9;mentaires-GoDaddy"></a>

Pour voir votre version de PHP :

1. Connectez-vous à votre Account Manager.
2. Dans la section Products, cliquez sur Web Hosting.
3. À côté du compte d'hébergement que vous voulez utiliser, cliquez sur Launch.

Dans la section Server, vous pourrez voir la version de PHP.

Pour modifier la version de PHP :

1. Dans le menu Content, sélectionnez Programming Languages.
2. Sélectionnez la version de PHP que vous souhaitez utiliser, puis cliquez sur Continue.
3. Cliquez sur Update.

Les modifications peuvent mettre jusqu'à 24h à être prises en compte.

### Lunarpages \(mutualisé\) <a id="Informationscompl&#xE9;mentaires-Lunarpages(mutualis&#xE9;)"></a>

1. Connectez-vous à cPanel. Il devrait se trouver à l'adresse [http://www.\(votre\_domaine\).\(com/net/org/etc.\)/cpanel](http://www.%28votre_domaine%29.%28com/net/org/etc.%29/cpanel)
2. Saisissez vos identifiants.
3. Dans la page qui s'affiche, cliquez sur l'icône "Enable/Disable PHP 5.6+".
4. Dans la page qui s'affiche, cliquez sur "Add PHP 5.6+ To Your Account!".

Les modifications peuvent mettre jusqu'à 24h à être prises en compte.

