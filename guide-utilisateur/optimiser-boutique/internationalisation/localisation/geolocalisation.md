# Géolocalisation

La géolocalisation est "un procédé permettant de positionner un objet (une personne, etc.) sur un plan ou une carte à l'aide de ses coordonnées géographiques" (pour en savoir plus, lisez la page Wikipédia : [http://fr.wikipedia.org/wiki/G%C3%A9olocalisation](http://fr.wikipedia.org/wiki/G%C3%A9olocalisation)). Dans notre cas, elle nous sert à découvrir la position d'un visiteur en utilisant l'adresse IP de son ordinateur et d'autres outils. L'un de ces usages est de pouvoir bloquer les visiteurs en provenance de certaines villes ou certains pays.

Comme indiqué la première fois que vous ouvrez la page "Géolocalisation", vous devez télécharger et installer un fichier afin de profiter de cet outil : [http://geolite.maxmind.com/download/geoip/database/GeoLiteCity.dat.gz](http://geolite.maxmind.com/download/geoip/database/GeoLiteCity.dat.gz). Il s'agit du fichier GeoLite City Database de MaxMind, une base de données assez précise de villes et autres emplacements. Téléchargez-le en cliquant sur le lien, puis décompressez-le dans le dossier `/tools/geoip/` de votre installation de PrestaShop. Une fois le fichier en place, activez l'option "Géolocalisation par IP", et vous êtes paré.

![](../../../../.gitbook/assets/64225455.png)

## Options <a href="geolocalisation-options" id="geolocalisation-options"></a>

Vous pouvez choisir les pays qui ont accès à votre site (par défaut, tous), et configurer les comportements de PrestaShop pour les pays restreints et ceux non reconnus (ou les "autres pays"). Vous avez le choix entre ces trois options :

* Les visiteurs ne peuvent pas voir le catalogue.
* Les visiteurs peuvent voir le catalogue mais ne peuvent pas commander. Dans les faits, cette option leur présente votre boutique en mode "Catalogue".
* Toutes les fonctionnalités sont disponibles (uniquement pour les pays restreints).\
  \


![](../../../../.gitbook/assets/64225456.png)

Vous pouvez sélectionner ou désélectionner tous les pays à la fois en cliquant sur la case en haut de la liste. Lorsque vous sélectionnez des pays qui peuvent accéder à votre boutique, faites en sorte de ne pas bloquer un pays par erreur, car vous perdriez toutes les ventes potentielles pour ses citoyens !

## Liste des adresses IP autorisées <a href="geolocalisation-listedesadressesipautorisees" id="geolocalisation-listedesadressesipautorisees"></a>

Cette section vous permet d'accepter certaines adresses IP spécifiques malgré un blocage. Cela peut se révéler utile en cas de spammeurs ou d'attaques. La liste est déjà remplie avec une liste de bonnes adresses connues. Ajoutez-en autant que nécessaire, une par ligne, et cliquez sur "Enregistrer".

![](../../../../.gitbook/assets/64225457.png)
