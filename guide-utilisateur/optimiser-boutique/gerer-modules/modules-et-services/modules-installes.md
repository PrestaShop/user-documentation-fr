# Modules installés

Vous pouvez installer, configurer et mettre à jour chacun de vos modules installés. Ce chapitre explique comment gérer vos modules depuis l'onglet "Modules installés".

![](../../../../.gitbook/assets/51185201.png)

## La liste des modules <a href="#modulesinstalles-lalistedesmodules" id="modulesinstalles-lalistedesmodules"></a>

Cette liste vous permet de trouver rapidement le module que vous souhaitez configurer ou pour lequel vous souhaitez modifier des paramètres.

Elle est divisée en 3 sections :

* **Modules installés**. Il s'agit des modules que vous avez ajoutés à votre boutique, en les achetant sur PrestaShop Addons ou en les chargeant directement.
* **Modules intégrés**. Ces modules PrestaShop sont préinstallés lorsque vous créez votre boutique. Ils couvrent les bases de l'e-commerce et sont gratuits.
* **Modules de thème**. Chaque thème installé comprend son propre jeu de modules. Vous y trouverez tous les modules liés à votre thème actif.

Si vous souhaitez trouver un module rapidement, vous pouvez rechercher un module spécifique ou filtrer les modules pour trouver celui de votre choix.

![](../../../../.gitbook/assets/51185200.png)

* **Champ de recherche**. Permet de rechercher un module à partir de son nom, de son auteur ou de mots-clés.
* **Sélecteurs de tri**. La liste est automatiquement actualisée lorsque vous faites une sélection et affiche des modules en fonction de tous les paramètres en cours.
  * **Catégories**. Sur la gauche, vous trouverez une liste des catégories existantes, et le nombre de modules concernés entre parenthèse. Cliquez sur la catégorie pour afficher les modules qui y sont rattachés.
  * **Afficher tous les modules.** Permet faire la distinction entre modules activés et modules désactivés. Seuls les modules activés peuvent être configurés, voilà pourquoi ce sélecteur est important.
  * **Dernière utilisation.** Si vous utilisez souvent le même module, cette option vous permettra de trouver facilement les derniers modules sur lesquels vous avez travaillé.
  * **Nom**. Trie les modules par ordre alphabétique, de A à Z.

Les modules peuvent avoir l'un des 4 états suivants :

* Non-installé.
* Installé mais désactivé.
* Installé et activé.
* Installer et activé, mais avec des avertissements.

Différence entre désactivation et désinstallation

Si vous ne souhaitez plus utiliser un module, vous pouvez au choix le désactiver ou le désinstaller. Le résultat de ces deux actions est a priori le même : le module n'est pas actif, ses options n'apparaissent plus dans votre back-office, et les éléments qu'il a pu ajouter au front-end disparaissent.

La différence se tient dans ce que la désactivation du module conserve la configuration de celui-ci, afin de pouvoir tout récupérer lors d'une éventuelle réactivation, tandis que la désinstallation supprime les données de configuration.

De fait, vous ne devriez ne désinstaller un module que si vous ne vous souciez plus de ses données ou si vous êtes certain que vous n'en aurez plus besoin. Dans le cas où vous ne voudriez même pas du module sur votre boutique, vous pouvez même cliquer sur le lien "Supprimer".

\
Effectuer des actions sur les modules <a href="#modulesinstalles-effectuerdesactionssurlesmodules" id="modulesinstalles-effectuerdesactionssurlesmodules"></a>
--------------------------------------------------------------------------------------------------------------------------------------------------------------

Voici les actions disponibles, en fonction de l'état du module :

* Modules désinstallés :
  * **Installer.** Cette action déclenchera l'installation du module sur votre boutique PrestaShop. Le module sera automatiquement activé. Il se peut qu'il ajoute de nouvelles options à votre back-office.\
    \

* Modules installés :
  * **Mettre à jour**. Votre boutique PrestaShop se met régulièrement en contact avec le serveur d'Addons pour vérifier si des mises à jour disponibles pour vos modules. Si une mise à jour est trouvée pour l'un de vos modules, le nom de son bouton devient "Mettre à jour". Il vous suffit de cliquer dessus pour que PrestaShop télécharge et mette à jour le module.
  * **Activer**. Pour les modules qui n'ont jamais été désactivés, ajoutez de nouvelles options à votre back-office.
    * **Activer sur mobile**. Cette option permet d'activer l'affichage du module en front office pour les appareils mobiles (smartphones, etc.).
  * **Configurer**. Certains modules disposent d'une page de configuration. Dans ce cas, ils affichent un lien "Configurer" pour accéder à une nouvelle interface, d'où vous pourrez ajuster leurs réglages.
  * **Désactiver**. Lors de son installation, un module est activé par défaut. Vous pouvez le désactiver, ce qui enlèvera ses options de votre back-office mais conservera ses réglages en vue d'une possible réactivation.
    * **Désactiver sur mobile**. Cette action désactivera la vue front-office du module pour les appareils mobiles (smartphones, etc.).
  * **Réinitialiser**. Cette action remet les réglages par défaut de ce module.
  * **Désinstaller**. Cette action désactive le module. Pour également supprimer tous ses fichiers et ses données, sélectionnez l'option "Supprimer le dossier du module après la désinstallation."

Ces actions peuvent être effectuées individuellement sur chaque module ou en masse, grâce au menu  "Actions groupées" à droite.

### Désinstallation d'un module <a href="#modulesinstalles-desinstallationdunmodule" id="modulesinstalles-desinstallationdunmodule"></a>

**Ne supprimez pas les modules en les plaçant directement dans la corbeille à l'aide de votre client FTP !** Laissez PrestaShop s'en charger.

Quand vous souhaitez arrêter d'utiliser un module temporairement tout en conservant sa configuration, vous pouvez simplement le désactiver. Il vous suffit de cliquer sur le lien "Désactiver". Les actions deviendront "Activer" et "Supprimer" mais le bouton "Désinstaller" reste visible.

Si vous n'avez pas besoin de conserver les paramètres de configuration du module, cliquez sur le bouton "Désinstaller". Le dossier du module restera dans le dossier /modules, mais le module n'aura plus d'impact sur votre boutique.&#x20;

Si vous souhaitez supprimer définitivement le module de votre serveur, cliquez sur le lien "Supprimer" : PrestaShop supprimer alors le dossier et l'ensemble des fichiers du module.

Assurez-vous que la désactivation ou la suppression du module n'endommage pas le thème.
