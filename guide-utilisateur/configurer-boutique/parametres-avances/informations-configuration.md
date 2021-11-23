# Informations de configuration

Cette page sert de rappel pratique de votre configuration PrestaShop : numéro de version, informations sur le serveur, version de PHP et de MySQL... Ce sont des éléments essentiels à communiquer aux développeurs de PrestaShop en cas de problème, ou tout simplement à votre webmaster ou votre hébergeur.

![](../../../.gitbook/assets/52298444.png)

Il y a une dernière section, nommée "Liste des fichiers modifiés". Juste après avoir installé PrestaShop, la seule chose que cette section affiche est "Aucune modification n'a été détectée sur vos fichiers".\
Mais après avoir installé quelques modules et thèmes, fait des modifications avancées à certaines classes d'override ou même effacé des fichiers, cette liste affichera les différences entre votre installation actuelle de PrestaShop et ce à quoi elle ressemblait au moment de son installation. Cela vous aide à voir les modifications qui ont été faites à votre installation... et donc à savoir quoi prendre en compte si vous souhaitez mettre à jour votre boutique manuellement, ou lors du déplacement de vos fichiers vers un autre serveur.

Même sur une installation récente, cette section peut indiquer "`.gitattributes`", "`.gitignore`", "[`CONTRIBUTING.md`](http://contributing.md)", "[`CONTRIBUTORS.md`](http://contributors.md)" ou "[`README.md`](http://readme.md)" comme fichiers manquants. Ce sont des fichiers propres à Git, et PrestaShop ne s'en sert pas, donc vous n'avez pas à vous en soucier.
