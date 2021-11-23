# Sauvegarde BDD

La sauvegarde de BDD (base de données) consiste à enregistrer le contenu de votre base de données au sein de fichiers que vous mettez en lieu sûr. L'objectif consiste à être en mesure de revenir en arrière au cas où la base de données ne fonctionnerait plus.

Il vous faut régulièrement effectuer des sauvegardes du contenu de votre boutique, de sorte que si un problème survenait, vous pourriez retomber sur vos pieds rapidement et efficacement. La base de données contient la plupart des informations de votre boutique, qui sont essentielles au bon fonctionnement de PrestaShop – y compris les produits, catégories et autres données que vous avez ajoutées depuis l'installation, à l'exception de vos images (qui elles sont stockées sur votre serveur, avec les fichiers de votre thème).

Plus vous faites de sauvegardes régulièrement, plus vous êtes en sécurité. Au minimum, faites en une au moins une fois par semaine.

Pour créer une sauvegarde de votre base de données, vous disposez de plusieurs solutions. Vous pouvez utiliser des outils tels que phpMyAdmin (à réserver aux utilisateurs chevronnés) ou l'outil intégré à PrestaShop, disponible dans la "Sauvegarde BDD" du menu "Paramètres avancés".

La page s'ouvre avec deux textes proéminents. Vous devriez les lire tous les deux du début à la fin afin de vous faire une meilleure idée de ce que fait cette page.

* La section "Avertissement" vous donne une série de rappels concernant les sauvegardes, que vous devriez lire à chaque fois que vous en faites une. Cette section se termine par un bouton "J'ai lu l'avertissement - Créer une sauvegarde", sur lequel vous devez cliquer pour créer une sauvegarde. Une fois celle-ci créée, elle apparaît dans la liste sous l'avertissement.
* La section "Comment restaurer" vous donne des conseils sur la manière de remettre vos données dans PrestaShop en cas de défaillance. Mémorisez-les bien, ou au moins conservez cette information en lieu sûr au cas où la base de données devenait inaccessible, rendant impossible la connexion à l'administration de PrestaShop – et donc à la page de gestion des sauvegardes. Au cas où, vous les trouverez également ci-dessous.

Comment restaurer une sauvegarde en 10 étapes simples

1. Mettez sur "Non" l'option "Activer la boutique" dans la page "Maintenance" du menu "Préférences".
2. Téléchargez le fichier de sauvegarde depuis la liste ci-dessous ou sur votre serveur FTP (dans le dossier "admin/backups").
3. Vérifiez l'intégrité de votre sauvegarde : présence d'erreurs, fichier incomplet... vérifiez toutes vos données.
4. Demandez à votre hébergeur un accès à l'outil "phpMyAdmin".
5. Connectez-vous à "phpMyAdmin" et sélectionnez votre base de données actuelle.
6. Si vous n'avez pas activé l'option "Supprimer les tables existantes durant l'import", vous devez supprimer toutes les tables présentes dans votre base de données actuelle.
7. En haut de l'écran, cliquez sur l'onglet "Importer".
8. Cliquez sur le bouton "Parcourir..." et sélectionnez le fichier de sauvegarde depuis votre disque dur.
9. Vérifiez la taille maximale autorisée (ex. : Max 16 Mo)\
   Si le poids de votre fichier de sauvegarde est trop important, contactez votre hébergeur.
10. Cliquez sur le bouton "Exécuter" et patientez durant l'import de votre fichier. Cela peut prendre plusieurs minutes.

Le tableau en-dessous liste toutes les sauvegardes déjà effectuées, en indiquant leur date de création, leur âge, leur nom de fichier et leur taille.\
Deux actions se trouvent à droite de chaque ligne :

* **Détails**. Vous permet de télécharger la sauvegarde.
* **Supprimer**. Vous permet d'effacer la sauvegarde. Attention, c'est une action définitive.

![](../../../../.gitbook/assets/52298483.png)

Après chaque sauvegarde, vous devriez télécharger le fichier généré en cliquant sur l'icône "Plus d'infos", ou simplement en utilisant le lien du texte de notification en haut. Mettez votre fichier de sauvegarde dans un lieu sûr, car vous pourriez en avoir besoin à n'importe quel moment. De plus, vous pouvez trouver ces fichiers directement sur votre serveur, dans le dossier `/admin/backup/`.

Votre base de données est enregistrée au format SQL dans un fichier `.sql`, puis compressé à l'aide de l’algorithme BZip2 (une variante du format populaire Zip. Pour en apprendre plus, lisez [http://en.wikipedia.org/wiki/Bzip2](http://en.wikipedia.org/wiki/Bzip2)) dans un fichier `.bz2`. Cela vous donne une archive avec l'extension `.sql.bz2`.

## Options de sauvegarde <a href="sauvegardebdd-optionsdesauvegarde" id="sauvegardebdd-optionsdesauvegarde"></a>

En bas de l'écran, deux options sont disponibles :

* **Ignorer les tables de statistiques**. PrestaShop enregistre les statistiques de votre site dans une poignée de tables de la base de données, et ces tables peuvent prendre beaucoup d'espace très rapidement. Il peut évidemment être utile de garder vos statistiques en lieu sûr, mais cela donne des fichiers souvent très lourds à télécharger, alors que vous n'êtes sans doute intéressé que par une sauvegarde de vos produits, catégories, clients, commandes, etc.\
  Par défaut, PrestaShop sauvegarde toutes les tables, mais si vous manquez d'espace disque sur votre serveur web, passez cette option sur "Oui".
* **Supprimer les tables existantes durant l'import**. Quand vous importez un fichier de sauvegarde, le système peut soit réécrire par-dessus les tables existantes, ou effacer d'abord les tables en place afin de les remplacer par celles de la sauvegarde. Le premier cas peut donner des doublons, ce qui explique pourquoi cette option est activée par défaut.

![](../../../../.gitbook/assets/52298484.png)
