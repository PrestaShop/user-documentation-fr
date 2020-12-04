# Devises

PrestaShop accepte un grand nombre de devises. Il n'y en a qu'une par défaut : celle de votre pays. Cependant, vous devez ajouter et configurer autant de nouvelles devises que vos clients en requièrent. En effet, les clients apprécient de pouvoir afficher les prix de votre boutique dans la monnaie de leur pays.

![](../../../../.gitbook/assets/64225450.png)

Les deux sections en bas de la page "Devises" sont très simples mais essentielles, car elles sont en rapport avec les taux de change de vos devises \(ou "taux de conversion"\). Pour citer Wikipedia, "Le taux de change d'une devise \(une monnaie\) est le cours \(autrement dit le prix\) de cette devise par rapport à une autre." Ce taux est également considéré comme la valeur de la monnaie d'un pays en fonction d'une autre monnaie. Les taux changent tous les jours, parfois de manière drastique en fonction de l'actualité, et votre boutique devrait toujours utiliser les dernières valeurs.

Pour changer la devise par défaut, vous devez vous rendre dans la page "Localisation" du menu "Localisation", et utiliser l'option "Devise par défaut" de la section "Configuration". Si la devise que vous souhaitez utiliser n'est pas disponible dans cette option, vous devez l'importer depuis un pays qui l'utilise, à l'aide de la section "Import de pack de localisation" de la page "Localisation".

## Mettre à jour les taux de change <a id="Devises-Mettre&#xE0;jourlestauxdechange"></a>

Vous pouvez mettre à jour les taux de change en cliquant en haut à droit sur "Mettre à jour", dans l'encart "Mettre à jour les taux de change". Le fichier de mise à jour sera téléchargé depuis les serveurs de [PrestaShop.com](http://prestashop.com/) par le biais du service web de PrestaShop.

![](../../../../.gitbook/assets/64225451.png)

Notez que les taux sont fournis à titre indicatif : l'équipe de PrestaShop s'efforce de fournir des taux exacts dans ces fichiers, mais ils peuvent varier légèrement des véritables taux, ne serait-ce que parce que ces taux varient grandement dans un très court laps de temps.

## Ajouter une nouvelle devise <a id="Devises-Ajouterunenouvelledevise"></a>

La manière la plus simple d'ajouter la devise d'un pays consiste à importer son pack de localisation. Cela se fait via la page "Localisation", du menu "International". Une fois la devise importée, vous devez vous rendre sur la page "Devises" pour l'activer. Vous pourriez avoir besoin d'une devise qui n'est présente dans aucun pack de localisation. Dans ce cas, vous pouvez utiliser le formulaire de création. Cliquez sur "Ajouter une nouvelle devise", et une nouvelle page s'ouvre. Vous devez y renseigner quelques champs.

![](../../../../.gitbook/assets/64225452.png)

* **Nom de la devise**. Le nom de la devise, de préférence en anglais pour que le plus grand nombre possible de clients puissent la lire.
* **Taux de change**. Ce taux est défini en fonction de la devise par défaut de la boutique. Par exemple, si la devise par défaut est l'Euro et que la devise créée est le dollar, saisissez "1.31", étant donné que 1€ vaut $1.31 \(à l'heure de publication de ce chapitre\). Utilisez ce convertisseur pour vous aider : [http://www.xe.com/fr/](http://www.xe.com/fr/).
* **Boutique associée**. Vous pouvez ne rendre une devise disponible que pour certaines boutiques, par exemple une boutique locale.
* **État**. N'importe quelle devise peut être désactivée quand vous le voulez, à la fois depuis sa propre page d'édition, et depuis le tableau des devises de la page "Devises". Lorsque vous créez une nouvelle devise, elle est désactivée par défaut. Pour l'activer, cliquer sur le bouton du bloc "État" : le message "Cette devise est activée" s'affiche alors.

