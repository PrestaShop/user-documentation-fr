# Langues

PrestaShop a été conçu pour être multilingue : il y a une langue par défaut \(celle utilisée lors de l'installation\), et de nombreuses autres sont disponibles en téléchargement.

Participez à la traduction de PrestaShop

Si PrestaShop n'est pas entièrement traduit dans votre langue, vous pouvez nous aider à la traduire en rejoignant la communauté de traducteurs sur [Crowdin](https://crowdin.com/project/prestashop-official) pour faire progresser votre langue !

La page "Langues" gère les langues que vous utiliserez dans le back office et sur votre boutique. Cette page affiche les langues déjà installées sur votre boutique, avec quelques informations : code ISO, code de la langue, format de date \(courte et complète\). Vous pouvez activer ou désactiver une langue simplement en cliquant sur l'icône dans la colonne "Activé".

Pour ajouter une langue, il suffit d'importer le pack de localisation d'un pays qui utilise cette langue \(dans la page "Localisation"\). S'il se trouve que cela ne marche pas, ou que vous avez besoin de quelque chose de plus adapté à vos besoins, vous pouvez ajouter une nouvelle langue manuellement en utilisant le formulaire qui se trouve derrière le bouton "Ajouter une langue".

Vous pouvez aussi ajouter une langue via la page "Traductions", dans la section "Ajouter/Modifier une langue". Contrairement au pack de localisation, cela importera uniquement la langue, sans autre donnée de localisation \(unités, devise, etc.\).

![](../../../../.gitbook/assets/64225447.png)

## Créer une nouvelle langue <a id="Langues-Cr&#xE9;erunenouvellelangue"></a>

Créer une nouvelle langue signifie que vous devez traduire l'intégralité des textes du front office de PrestaShop, son back office, ses modules, etc., au risque d'utiliser les chaînes anglaises par défaut. La traduction se fait avec l'outil de la page "Traductions" du menu "Localisation". Vous pouvez également créer une nouvelle langue afin mieux intégrer un pack de langue que vous auriez téléchargé depuis le site de PrestaShop.

![](../../../../.gitbook/assets/64225448.png)

Pour créer une nouvelle langue, vous devez remplir autant de champs du formulaire que possible :

* **Nom**. Le nom est public. Si vous créez la langue pour des besoins régionaux, vous devriez l'indiquer dans le nom. Par exemple, "Français \(Québec\)".
* **Code ISO**. Saisissez le bon code à deux lettres ISO 639-1. Vous trouverez plus d'information sur [http://fr.wikipedia.org/wiki/Liste\_des\_codes\_ISO\_639-1](http://fr.wikipedia.org/wiki/Liste_des_codes_ISO_639-1). Si vous importez un pack de langue, ce code doit correspondre exactement à celui du pack.
* **Code langue**. Saisissez le bon code de langue à quatre lettres, sous la forme `xx-yy`, `xx` étant le code ISO de la langue \(le même que ci-dessus\) et `yy` étant le code ISO 3166-1 alpha-2 du pays \([http://fr.wikipedia.org/wiki/ISO\_3166-1](http://fr.wikipedia.org/wiki/ISO_3166-1)\). Vous trouverez plus d'information sur Wikipédia : [http://fr.wikipedia.org/wiki/%C3%89tiquette\_d%27identification\_de\_langues\_IETF](http://fr.wikipedia.org/wiki/%C3%89tiquette_d%27identification_de_langues_IETF).
* **Format de date**. Les pays ne partagent pas toujours les mêmes représentations des dates \(voir sur Wikipédia : [http://en.wikipedia.org/wiki/Date\_format\_by\_country](http://en.wikipedia.org/wiki/Date_format_by_country) \(en anglais\)\). Ainsi, que votre boutique affiche la date 02/08/12, un client aux États-Unis comprendra "le 8 février 2012", tandis qu'un client en France comprendra "le 2 août 2012". C'est pourquoi il est important d'indiquer le format de date lié à votre langue. Les lettres utilisées doivent être celles de la fonction `date()` de PHP : [http://php.net/manual/fr/function.date.php](http://php.net/manual/fr/function.date.php).
* **Format de date \(complet\)**. La même chose que le format de date ci-dessus, mais en incluant le format des heures et minutes.
* **Drapeau**. Mettez en ligne une image du drapeau qui correspond le mieux à la langue que vous voulez ajouter. Elle devrait être au format 16\*16. Nous vous recommandons d'utiliser un des drapeaux du jeu d'image gratuit FamFamFam Flags : [http://www.famfamfam.com/lab/icons/flags/](http://www.famfamfam.com/lab/icons/flags/).
* **Image "Aucune image"**. Mettez en ligne une image qui sera affichée quand le produit n'a pas encore de photo. Cette image est simplement une image vierge avec pour seul contenu le texte "Aucune image" ou "Aucune image disponible" dans la langue créée. Cette image doit être au format 250\*250 pixels. Vous pouvez trouver des exemples d'images "Aucune image" dans le dossier `/img/l` de votre installation de PrestaShop.
* **Langue RTL**. Certaines langues s'écrivent de droite à gauche, notamment celles écrites en alphabet arabe ou hébreu \(voir [http://fr.wikipedia.org/wiki/Texte\_bidirectionnel](http://fr.wikipedia.org/wiki/Texte_bidirectionnel)\). Quand un thème PrestaShop est bien codé, il est capable de gérer les langues RTL - à partir du moment où il est clairement configuré pour.
* **État**. Vous pouvez désactiver une nouvelle langue jusqu'à ce que vous ayez tout traduit.
* **Boutique associée**. Vous pouvez ne rendre une langue disponible que pour certaines boutiques, par exemple une boutique locale.

Assurez que tout fonctionne : rendez-vous sur le front office de votre boutique, et cliquez sur les drapeaux tout en haut. De la même manière, les clients pourront choisir une autre langue en utilisant ces icônes.

Sharing your translations with the community

Vous avez peut-être traduit tout une langue directement via l'interface de PrestaShop. Vous pouvez en faire bénéficier la communauté PrestaShop en envoyant un export à [translation@prestashop.com.](mailto:translation@prestashop.com.) Nous nous chargerons de mettre en ligne votre contribution dans notre [projet de traduction](https://crowdin.com/project/prestashop-official), pour que les marchands qui parlent votre langue puissent en profiter aussi !

Pour exporter vos traductions, rendez-vous dans la page "Traductions" du menu "International", section "Exporter des traductions".

