# Traductions

Les traductions officielles de PrestaShop proviennent de Crowdin, une plateforme de traduction sur laquelle une communauté de traducteurs bénévoles travaille sur pas moins de 80 projets de traduction.

{% hint style="info" %}
Si vous souhaitez contribuer à la traduction de PrestaShop en votre langue, n'hésitez pas à [rejoindre la communauté sur Crowdin](https://crowdin.com/project/prestashop-official).
{% endhint %}

Sur la page** International > Traductions**, vous pouvez adapter ces traductions officielles à vos besoins. Par exemple, vous pouvez changer la formulation choisie par les traducteurs pour quelque chose de moins formel et personnaliser le texte pour mieux convenir à votre public et rendre votre boutique encore plus unique.

## Sélectionner le type de traduction à modifier

Les traductions ont été organisées en 5 catégories, selon l'endroit où les chaînes apparaissent sur le logiciel PrestaShop.

![](<../../../.gitbook/assets/image (44).png>)

{% hint style="info" %}
Une chaîne est une série de caractères. Elle peut être composée d'un seul caractère ou contenir plusieurs mots. Lorsqu'une nouvelle version mineure ou majeure de PrestaShop sort, toutes les nouvelles chaînes associées à cette version sont ajoutées sur [Crowdin ](https://crowdin.com/project/prestashop-official)pour être traduites par la communauté.
{% endhint %}

* Traductions du back-office : les chaînes visibles par vous et votre équipe depuis le back-office de la boutique.
* Traductions du front-office : les chaînes visibles par vos clients lorsqu'ils naviguent dans votre boutique.
* Traductions des modules installés : les chaînes présentes dans un module. Seuls les modules installés sont répertoriés.
* Traductions des e-mails : les chaînes utilisées dans les modèles d'e-mail par défaut.
* Autres traductions : les chaînes qui n'ont pas encore été identifiées comme provenant du front-office ou du back-office.&#x20;

Certaines catégories disposent d'une deuxième liste déroulante pour affiner votre recherche. Une fois votre sélection effectuée, choisissez la langue dans laquelle vous souhaitez modifier les traductions et cliquez sur "Modifier". Une nouvelle page s'ouvre, où vous pouvez rechercher les traductions à modifier.

## **Rechercher une chaîne en particulier**

![](<../../../.gitbook/assets/image (47).png>)

En haut à gauche de la page, il y a une barre de recherche qui vous permet de rechercher un mot ou une chaîne spécifique.&#x20;

Vous pouvez également trouver rapidement les chaînes non traduites. En haut à droite sont affichés le nombre total de chaînes de caractères dans la section et le nombre de traductions manquantes. Les catégories qui contiennent des traductions manquantes sont affichées en rouge dans le menu à gauche de la page.

## Parcourir les traductions

![](<../../../.gitbook/assets/image (53).png>)

Le menu situé à gauche de la page vous permet de parcourir toutes les chaînes d'une catégorie. Toutes les chaînes sont organisées en ce que l'on appelle des "domaines de traduction". Les domaines de traduction visent à donner plus de contexte aux traducteurs, en indiquant où la chaîne apparaît sur le logiciel PrestaShop. Pour en savoir plus sur les domaines de traduction, consultez la page dédiée sur le guide [Content style guide](traductions.md#selectionner-le-type-de-traduction-a-modifier) du projet PrestaShop.

## Modifier les traductions

Pour modifier une traduction existante ou compléter une traduction manquante, éditez ou ajoutez du texte dans le champ situé juste en dessous de la chaîne et cliquez sur l'un des boutons "Enregistrer" en haut ou en bas de la page.&#x20;

Certaines chaînes de caractères utilisent une syntaxe spéciale, avec des variables telles que `%s`, `%d`, `%product%`, etc.&#x20;

Si une chaîne contient une variable, celle-ci sera remplacée par une valeur dynamique. Par exemple, dans la chaîne "Le produit (`%product%`) n'est plus disponible", `%product%` sera remplacé par le nom du produit. Par exemple, "Le produit (T-shirt imprimé Colibri) n'est plus disponible". Vous devez donc toujours conserver les variables dans votre traduction finale.&#x20;

Si une chaîne contient une variable, vous devez vous assurer que le contenu de cette variable sera placé au bon endroit dans la phrase, et éviter la traduction littérale. Les variables numérotés (`%1$s, %2$d`, etc.) permettent aux traducteurs de réorganiser l'ordre des variables dans la chaîne. Par exemple, "This is a `%1$s` `%2$d`", avec `%1$s` pour "red" et `%2$d` pour "pen", pourrait être traduit par "C'est un `%2$s` `%1$s` = "C'est un stylo rouge" en français.

### Traduire le contenu des modules

Pour traduire un module spécifique, sélectionnez l'option "Traductions des modules installés" et le module souhaité. Une nouvelle page s'ouvre, avec toutes les chaînes de caractères du module. Selon le module sélectionné, l'interface peut être différente. Certains modules utilisent un système de traduction spécifique à la version 1.7, tandis que d'autres utilisent encore l'ancien système de la version 1.6. Au final, cela ne change rien pour vous, puisque vous pourrez traduire vos modules de la même manière.

### Traduire les templates d'e-mails

Il existe deux façons de modifier la traduction d'un courriel :&#x20;

* **Modifier la version HTML** : avec cet aperçu modifiable, ce que vous voyez est ce que vous obtenez. Cliquez sur le bouton "Modifier la version HTML". Vous pourrez modifier le texte et le design de votre message. Lorsque vous avez terminé, enregistrez.&#x20;
* **Modifier la version texte** : vous pouvez modifier la version texte de votre message directement dans le champ de texte.

{% hint style="info" %}
Veillez à conserver les variables (par exemple `{lastname}` ou `{shop_name}`) dans vos traductions. Elles seront remplacées par la bonne valeur lors de l'envoi de l'e-mail.
{% endhint %}

![](<../../../.gitbook/assets/image (52).png>)

## Réinitialiser les traductions

![](<../../../.gitbook/assets/image (56).png>)

Pour remplacer une traduction personnalisée par la traduction officielle de PrestaShop, cliquez sur le bouton "Réinitialiser" à côté de la chaîne. Si le champ est vide, cela signifie qu'aucune traduction officielle n'est disponible pour le moment. N'hésitez pas à [contribuer au projet de traduction](https://crowdin.com/project/prestashop-official) si vous souhaitez mettre votre traduction à la disposition d'autres marchands.

## Ajouter ou mettre à jour une langue&#x20;

![](<../../../.gitbook/assets/image (49).png>)

Pour ajouter ou mettre à jour une langue, sélectionnez la langue souhaitée dans la liste et cliquez sur le bouton "Ajouter ou mettre à jour la langue". Si vous avez ajouté une nouvelle langue, vous pouvez ensuite la gérer dans **Localisation > Langues**.

## Exporter des traductions

![](<../../../.gitbook/assets/image (50).png>)

Vous pouvez créer votre propre pack de langues à l'aide de cette fonctonnalité, soit pour faire une sauvegarde de vos traductions, soit pour les partager. Tout d'abord, sélectionnez la langue dans laquelle vous souhaitez exporter des traductions. Ensuite, sélectionnez le type de traductions que vous souhaitez :&#x20;

* Traductions PrestaShop
* Traductions thème
* Traductions module installé

Chaque catégorie dispose d'une deuxième liste déroulante ou de cases à cocher pour affiner votre sélection. Une fois que vous avez terminé, cliquez sur le bouton "Exporter".

## Copier les traductions d'une langue vers une autre&#x20;

![](<../../../.gitbook/assets/image (41).png>)

Vous pouvez copier le contenu d'une langue vers une autre. C'est particulièrement utile lorsque vous souhaitez remplacer la langue d'un thème par la même langue en provenance d'un autre thème.&#x20;

Sélectionnez la langue et le thème source, puis la langue et le thème de destination, et cliquez sur le bouton "Copier". Dans la plupart des cas, la langue doit rester la même dans les deux listes déroulantes.&#x20;

S'il existe déjà un dossier de langue pour cette langue dans le thème de destination, il sera écrasé par les fichiers de langue et de thème que vous copiez. Vous pouvez créer une nouvelle langue pour le thème de destination avant d'y copier la langue source.
