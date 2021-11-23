# Factures

Chaque fois qu'une commande est validée dans votre boutique, une facture est envoyée au client. Vous pouvez télécharger toutes les factures d'une même commande depuis la page de cette commande. La page "Factures" du menu "Commandes" vous permet de télécharger certaines factures passées au format PDF, d'un seul coup (toutes dans un seul fichier PDF).

![](../../../.gitbook/assets/52298158.png)

Vous pouvez générer un fichier PDF contenant plusieurs factures en fonction de deux critères :

* **Par date**. Très utile quand vous avez besoin d'imprimer toutes les factures d'un mois donné ou d'un trimestre donné. Sélectionnez les dates de début et de fin, et cliquez sur "Générer un fichier PDF par date" dans la barre supérieure.
* **Par état de commande**. Nécessaire dans le cas où vous avez besoin d'imprimer précisément les commandes qui ont été annulées, remboursées ou en rupture de stock. Pour vous aider, PrestaShop vous indique le nombre de factures liées à chaque état, entre parenthèse.

Dans les deux cas, les factures sont générées au sein d'un même fichier PDF, chacune sur sa propre page. Vous ne pouvez pas obtenir un fichier PDF par facture à l'aide de cette page.

Vous pouvez personnaliser l'apparence de la facture : les modèles de fichiers PDF sont situés dans le dossier `/pdf`. Ces fichiers `.tpl` sont en fait des fichiers HTML contenant des balises Smarty pour les données dynamiques. Vous pouvez modifier l'apparence de la facture en modifiant le fichier `invoice.tpl`.

Si vos clients vous demandent leurs factures, vous pouvez les rediriger vers la page "Historique de vos commandes" de leur espace client, où ils trouveront les factures rattachées à leurs commandes.

## Options des factures <a href="factures-optionsdesfactures" id="factures-optionsdesfactures"></a>

Vous pouvez choisir si les factures doivent être ou non imprimées dès que la commande est passée, de même que le préfixe de la facture et numéro facture que vous souhaitez voir apparaître dans la version imprimée de la section. Cette fonctionnalité peut vous aider à gérer votre compte.

![](../../../.gitbook/assets/52298159.png)

* **Activer les factures**. Si vous désactivez cette option, votre client ne recevra plus sa facture lors de son achat. Il vous reviendra de la lui envoyer, si le client en demande une.
* **Afficher le détail des taxes**. Affiche le montant des taxes sur la facture ventilée par taux de taxe lorsque plusieurs taxes sont combinées.
* **Afficher l'image du produit**. Ajoute une miniature de l'image principale de chaque produit à côté du nom de celui-ci dans la facture.&#x20;
* **Préfixe de facture**. Par défaut, PrestaShop utilise des préfixes adaptés à chaque langue pour ses factures : "IN" en anglais ("_invoice_"), "FA" en français, "CU" en espagnol (pour "_cuenta_"), etc. Vous pouvez préférer utiliser des préfixes par langue : "EN", "FR", "SP", etc. Bien sûr, vous pouvez également choisir d'avoir un préfixe pour tous les cas, ou pas de préfixe du tout.
* **Ajouter l'année courante au numéro de facture.** En plus du numéro de facture et de son préfixe, vous pouvez ajouter l'année en cours à la référence de facture.
* **Réinitialiser le numéro de facture au début de chaque année.** Au début de chaque année, le numéro de facture est réinitialisé pour commencer à 0.
* **Position de l'année.** Choisissez où afficher l'année, avant ou après le numéro de facture.
* **Numéro de facture**. Si votre société a déjà eu des commandes et factures avant que vous ne vous lanciez avec PrestaShop, vous pouvez utiliser cette option pour commencer la numération de vos bons de livraison à un certain nombre.
* **Texte libre**. Vous pouvez ajouter du texte personnalisé dans vos factures (par exemple, des mentions légales spécifiques), qui s'affichera en dessous du récapitulatif des modes de paiement.
* **Texte de pied de page**. Vous pouvez ajouter du texte personnalisé en bas de toutes vos factures. Le texte apparaîtra sous le nom de votre boutique dans la facture.
* **Modèle de facture**. En fonction de vos thèmes, vous pourriez avoir plus d'un style de facture. Testez-les avec une fausse commande, afin de choisir celui que vous préférez. Si vous savez écrire du HTML, vous pouvez ajouter vos propres modèles de facture ou modifier ceux déjà en place : ils se trouvent dans le dossier `/pdf` de votre installation de PrestaShop.
* **Utiliser le cache disque pour les factures PDF**. Vous pouvez choisir de stocker les factures générées sur le disque du serveur de PrestaShop plutôt que sur son cache. Cela permet de préserver de la mémoire, mais cela ralenti la génération de fichiers PDF. De fait, utilisez cette option en toute connaissance de cause.

N'oubliez pas d'enregistrer vos modifications.

Quand les clients souhaitent obtenir leurs factures, vous pouvez les rediriger vers leurs comptes utilisateurs, dans leur historique des commandes, qui garde toutes les factures qui leur sont liés.
