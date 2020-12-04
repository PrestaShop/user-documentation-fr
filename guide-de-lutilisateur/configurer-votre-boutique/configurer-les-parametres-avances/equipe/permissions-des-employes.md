# Permissions des employés

Les permissions sont un aspect central des profils de PrestaShop. Elles permettent de voir précisément ce qu'un compte d'employé peut ou ne peut pas faire sur votre boutique.

La page d'administration "Autorisations" est faite d'onglets :

* Sur la gauche de l'écran, autant d'onglets que de profils disponibles.
* Sur le reste de l'écran, PrestaShop affiche les permissions du profil cliqué. Cet onglet contient deux tableaux, côte à côte.

Quand vous cliquez sur n'importe quel profil \(autre que SuperAdmin\), les deux tableaux apparaissent pour vous donner accès à leurs critères :

* À gauche, les permissions liées aux menus : vous pouvez décider ce que le profil peut faire sur un menu/page. Dans les faits, vous pouvez empêcher un profil de modifier le contenu d'une page, ou même lui cacher complètement un menu.
* À droite, les permissions liées aux modules : bien que vous puissiez autoriser certains profils à voir les modules disponibles, vous pourriez préférer que seuls les employés de confiance aient accès à la configuration de certains modules.

![](../../../../.gitbook/assets/52298480.png)

Pour chacun de ces critères des menus, vous avez 5 options :

* **Voir**. Autorise l'employé à consulter des informations.
* **Ajouter**. Autorise l'employé à ajouter de nouvelles informations
* **Modifier**. Autorise l'employé à modifier des informations.
* **Supprimer**. Autorise l'employé à supprimer des informations.
* **Tout**. Autorise les 4 critères ci-dessus.

De leurs côtés, les critères des modules ont 3 options :

* **Voir**. Autorise l'employé à consulter la configuration d'un module.
* **Configurer**. Autorise l'employé à configurer un module.
* **Désinstaller**. Autorise l'employé à désinstaller un module.

Les permissions du SuperAdmin ne peuvent pas être changées : le profil dispose simplement de tous les droits pour tous les critères.

## Régler les permissions d'un nouveau profil <a id="Permissionsdesemploy&#xE9;s-R&#xE9;glerlespermissionsd&apos;unnouveauprofil"></a>

Pour cet exemple, nous allons créer un nouveau profil, "Préparateur de commandes". Commencez par créer le profil dans la page "Profils", en remplissant le champ "Nom". Dès que le profil est enregistré, il apparaît dans la liste des profils.

Il vous faut ensuite assigner des permissions à ce nouveau profil. Rendez-vous sur la page "Permissions", et cliquez sur l'onglet du nouveau profil : la liste de critères apparaît. Par défaut, un nouveau profil n'a accès à aucune page du back-office.

Il y a deux manières de remplir les critères, en fonction des limites ou libertés que vous voulez donner au profil :

* Cliquez sur les cases des permissions une à une jusqu'à ce que tous les droits soient en place.
* Cochez toutes les cases d'un coup, puis enlevez les droits un à un jusqu'à ce qu'il ne reste que les droits nécessaires.

Il y a deux manières de cocher plusieurs cases d'un coup :

* Par colonne : en haut de chaque colonne, une case à cocher permet de cocher toutes les cases de la colonne d'un coup. Décocher la case signifie décocher les cases cochées dans la colonne.
* Par rangée : si vous cliquez sur la case "Tout" d'une rangée, toutes les cases de cette ligne sont cochées. Décocher la case signifie décocher les cases cochées dans la rangée.

Vous pouvez ensuite cocher les rangées sélectionnées plutôt que de passer du temps à les cocher une à une.

Pour éviter les erreurs lors de la configuration des permissions, PrestaShop enregistre automatiquement les réglages à chaque modification. Cela signifie que vous n'avez pas à cliquer sur un bouton "Enregistrer". Une fois que vous avez assigné ses droits à un profil, vous pouvez revenir à la page d'administration "Employés" et assigner ce profil aux employés qui en sont la cible.

