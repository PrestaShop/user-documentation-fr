# Devises

PrestaShop accepte un grand nombre de devises. Au départ, seule une devise est enregistrée dans votre boutique : celle du pays par défaut. Cependant, vous pouvez ajouter et configurer de nouvelles devises pour mieux répondre aux besoins de vos clients. En effet, ces derniers apprécieront de pouvoir faire des achats dans leur propre monnaie !

![](https://lh3.googleusercontent.com/nLZWL0\_hD36yhS1WHhn8TzaPYtLgm0cP6KpKdV4T\_666exvpKbEXu57jUzrC9BFUutRftIIvYLVE2cWEk2thaAhX7DvmZadAMTL8r06snansKt0ytC9fKA57ec7B3qf-WMZAAHbL)

## **Modifier la devise par défaut**

Tous les taux de change des devises ajoutées (officielles ou alternatives) sont calculés à partir d’une unité de la devise par défaut de votre boutique. C’est pourquoi la devise par défaut de votre boutique doit être celle avec laquelle vous vous sentez le plus à l’aise.&#x20;

Pour modifier la devise par défaut de votre boutique :

1. Allez dans International > Localisation
2. Dans la section “Paramètres”, trouvez le champ “Devise par défaut”
3. Sélectionnez la devise que vous souhaitez définir comme devise par défaut dans la liste

![](https://lh4.googleusercontent.com/chY2hJCmLZpvPO9ov7uu0YjBBs3hXsFg8xaAAwKOeFk7ghjEnfsABgmM9MbRDhYW4saubCjhFzDrhgkIvuQffmCefNb3YIfwrfqlRhYLHw3Bkf57YM7KmOuwrY1ew4WFlIkWYlqo)

Si la devise que vous souhaitez définir comme devise par défaut n’est pas disponible dans la liste, vous devez l’ajouter : soit en important le pack de localisation d’un pays utilisant cette devise, soit en complétant le formulaire “Ajouter une nouvelle devise” (Voir “[Ajouter une nouvelle devise](https://prestashop.gitbook.io/documentation-en-francais-pour-prestashop-1-7/guide-de-lutilisateur/optimiser-votre-boutique/gerer-la-localisation-et-linternationalisation/localisation/devises#ajouter-une-nouvelle-devise)”).&#x20;

## **Ajouter une nouvelle devise**

Il y a deux façons d’ajouter une nouvelle devise :

### **1. Importer le pack de localisation d’un pays utilisant cette devise**

Cela peut être fait depuis la page “Localisation” du menu “International”.&#x20;

![](https://lh4.googleusercontent.com/2AD9IZhZLFTOutUrmeLvhNID82TBaDkEBHJAn1B66TpBf3\_22DW8r9UvukeqQm8ebFKoF0llt1ht26Ck48\_pAC-XsxHTRVu56lsS0TL9Qt2EgTRVq4MqYh4rTGNZrqH1IDDuE-Zu)

Par exemple, pour ajouter le Dinar Algérien, importez le pack de localisation de l’Algérie.

Lorsque vous que vous importez un pack de localisation, la devise est activée par défaut. Une fois le pack importé, vous pouvez gérer le statut de la devise dans la section “Devises” de la page “Localisation”.

### **2. Ajouter la devise manuellement**

Cliquez sur le bouton “Ajouter une nouvelle devise”. Sélectionnez la devise que vous souhaitez ajouter dans la liste. Les champs seront complétés automatiquement.\
\
Lorsque vous ajouter une devise manuellement, cette dernière est désactivée par défaut. Pour l’activer sur votre boutique, n’oubliez pas de modifier l'état et d’enregistrer.

## **Créer une devise alternative**

Vous pourriez avoir besoin d’ajouter une devise qui n’est incluse dans aucun des packs de localisation et qui n’est pas non plus disponible dans la liste de devises. Vous pouvez utiliser cette fonctionnalité pour ajouter n’importe quelle cyptomonaie, monnaie locale, etc. qui répond aux besoins de vos clients.&#x20;

1. Cliquez sur le bouton “Ajouter une nouvelle devise”&#x20;
2. Cochez la case “Créer une devise alternative”
3. Complétez les champs suivants :

![](https://lh6.googleusercontent.com/YsBSIKAepm2BxMC0g-yudl-7QDDMFWnkW6YF95\_U3rR2O5IGJDJuNC4byWmbcs4KzG0MqI-Ti2jnBX6QBLJN-r8qOUKrQuHgtU2uL5q5GraNXcof4RdDdlXh\_H-dKhaMhOPHqooH)

* **Nom de la devise.** Entrez le nom de la devise.
* **Code ISO.** Entrer le code ISO 4217. Voir [Wikipedia ](https://fr.wikipedia.org/wiki/ISO\_4217#Liste\_tri%C3%A9e\_par\_nom\_d%E2%80%99unit%C3%A9\_mon%C3%A9taire)pour plus d’informations. Vous trouverez aussi les codes ISO non officiels ou ceux de devises alternatives comme le Bitcoin.
* **Taux de change.** Ce taux est défini en fonction de la devise par défaut de votre boutique. Par exemple, si votre devise par défaut est l’euro et votre devise choisie est le dollar, tapez “1.20” (1€ = $1.20).&#x20;
* **Décimales.** Nombre de chiffres après la virgule pour les prix sur votre boutique.&#x20;
* **État.** Vous pouvez désactiver une devise à n’importe quel moment, à la fois sur la page d’édition et depuis la liste des devises sur la page “Devises”. Lorsque vous créez une nouvelle devise en utilisant le formulaire de création, cette dernière est désactivée par défaut.&#x20;

## **Modifier le symbole et le format**&#x20;

Vous pouvez modifier le format et le symbole de chaque devise en fonction des langues installées sur votre boutique (qu’elles soient activées ou non).

Lorsque vous modifiez une devise, en bas de la page, choisissez la langue pour laquelle vous souhaitez modifier le format ou le symbole de devise et cliquez sur “Modifier le symbole/format”.

Entrez le symbole de la devise et choissisez un format :

* Juste devant le montant, ex : □999.99
* Devant, avec un espace entre le symbole et le montant, ex :\
  □ 999.99
* Juste après le montant, ex : 999.99□
* Après, avec un espace entre le symbole et le montant, ex : 999.99 □

Le carré blanc sera remplacé par le symbole une fois le champ “Symbole” complété. Veuillez noter que cette fonctionnalité n’est disponible qu’au moment de l’édition d’une monnaie, et pas lors de sa création.

## **Mettre à jour les taux de change**

Un taux de change, ou taux de conversion, est le taux auquel une devise sera échangée contre une autre. Par exemple, un taux de conversion EUR/USD de 1,22 signifie que 1 euro est égal à 1,22 dollars.&#x20;

Ainsi, si un produit vaut 15 euros, il coûtera 18,30 dollars (15\*1,22=18,3).

Au contraire, si un produit vaut 15 dollars, il coûtera 12,30 euros (15/1,22=12,3).

{% hint style="info" %}
Les taux de change sur PrestaShop sont fournis par l’[ECB](https://www.ecb.europa.eu/home/html/index.fr.html) et sont mis à jour chaque jour. Cependant, ils peuvent être légèrement différents des taux en temps réel puisque ces derniers peuvent fluctuer considérablement en peu de temps.
{% endhint %}

N’oubliez pas de mettre les taux de change à jour régulièrement :

![](https://lh3.googleusercontent.com/yfopr7QyiWfKOxC8QK3RyPsQh1f6YXUwYfbomCl29SoqHbkrF22tBDTaOLJ4I8iJg1nHxKl3\_AowbrxYySeyiMR4\_5pusS\_9A1EZY0t5tKgSOYIRiZX6TqRMq5wJF\_CYYmJZjCDw)

Pour mettre à jour les taux de change :

1. Allez à la section “Taux de change” de la page “Devises”&#x20;
2. Cliquez sur le bouton “Mettre à jour”

{% hint style="warning" %}
Les taux de change des devises alternatives ne seront pas mis à jour. Vous devrez le faire manuellement. Par exemple, si vous avez ajouté le Bitcoin et souhaitez mettre le taux de change à jour, cliquez sur le symbole “Modifier” à côté du Bitcoin sur la liste des devises et entrez le taux de change à jour dans le champ correspondant. Si vous ajoutez des monnaies très volatiles, il est fortement recommandé d’utiliser un module qui peut mettre à jour les taux de change automatiquement.&#x20;
{% endhint %}

Une simple recherche sur internet est généralement suffisante pour trouver le taux de change d’une monnaie. Vous pouvez utiliser des convertisseurs en ligne, comme XE.com :

&#x20;[https://www.xe.com/currencyconverter/convert/?Amount=1\&From=XBT\&To=USD](https://www.xe.com/currencyconverter/convert/?Amount=1\&From=XBT\&To=USD)

Pour les cryptomonnaies, vous pouvez visiter le site web suivant : [https://coinmarketcap.com/](https://coinmarketcap.com/)
