# Gérer les transporteurs

Vous devez enregistrer des transporteurs dans votre installation de PrestaShop – c'est-à-dire indiquer clairement qui va livrer vos produits. Il peut s'agir de vous-même ou de votre boutique \(par exemple, si vous ne vendez que des produits dématérialisés, ou si vous ne travaillez que dans votre quartier\), mais dès qu'il s'agit d'expédier un colis avec des timbres et une livraison faite par un tiers, comme votre service de postes ou FedEx, UPS et autres, alors vous devez ajouter leurs détails dans la base de données de votre boutique. Cela permettra à vos clients de choisir un transporteur au mieux, en fonction de ses zones de livraison, de ses frais et de ses dates.

La page "Transporteurs" vous présente une liste de tous vos transporteurs actuels. D'ici, vous pouvez directement changer leur état, indiquer s'ils sont inclus dans vos promotions "livraison gratuite", et modifier leur position quand ils sont affichés pour l'utilisateur.

![](../../../.gitbook/assets/52298298.png)

6 conseils pour construire une politique de livraison qui convertit et fidélise

[![](../../../.gitbook/assets/51839792.png)](https://www.youtube.com/watch?v=QhTU_eSrm7o&list=PLyZYn1MMU7-xT-L_zUyGnRBJmAuP6uc-c&index=26)

Par défaut, deux transporteurs sont disponibles :

* Votre propre boutique : ce "transporteur" représente votre boutique physique, où vos clients peuvent venir pour récupérer eux-mêmes leurs achats. Il n'a ni tranche de poids ou de prix.
* "My carrier" : il s'agit d'un exemple de transporteur, qui ne devrait pas être utilisé en production. Il n'a qu'une tranche de prix \(de 0 € à 10 000 €\) et une tranche de poids \(de 0 kg à 10 000 kg\).

Il vous revient de supprimer ces transporteurs par défaut et d'en ajouter de nouveaux pour vos clients. À tout le moins, vous devriez modifier le transporteur "My carrier" et remplacer ses données par celles d'un vrai transporteur : nom, détails et zones. Cependant, nous vous recommandons de supprimer le transporteur "My carrier", et d'utiliser un module de transporteur existant pour enregistrer votre partenaire de livraison dans PrestaShop.

## Ajouter un nouveau transporteur à l'aide d'un module transporteur recommandé <a id="G&#xE9;rerlestransporteurs-Ajouterunnouveautransporteur&#xE0;l&apos;aided&apos;unmoduletransporteurrecommand&#xE9;"></a>

L'installation de PrestaShop propose bon nombre de modules gratuits, parmi lesquels se trouve une poignée de modules transporteur que vous pouvez installer aussitôt, pour les principaux transporteurs nationaux et internationaux.

Les transporteurs proposés dépendent de la configuration initiale de votre boutique : si vous avez déclaré être basé en France, vous n'aurez pas les mêmes modules que si vous étiez basé aux États-Unis !

Dans la page "Transporteurs", vous pouvez choisir entre créer un transporteur à l'aide de l'Assistant, ou utiliser l'un de nos modules transporteur recommandés. Il est fortement recommandé d'enregistrer vos transporteurs en passant par un module de transporteur : cela accélérera largement le processus, et les réglages seront bien plus précis.

En fonction du module, vous pouvez soit cliquer sur le bouton "Installer" et laisser PrestaShop faire le plus gros du travail, soit cliquer sur le bouton de mise en panier \(via le prix du module\). Dans le second cas, vous serez envoyé sur la place de marché Addons, où vous pouvez acheter le module. Une fois celui-ci acheté, vous pouvez l'installer et le configurer.

## Créer un nouveau transporteur à l'aide de l'assistant \(Carrier Wizard\) <a id="G&#xE9;rerlestransporteurs-Cr&#xE9;erunnouveautransporteur&#xE0;l&apos;aidedel&apos;assistant(CarrierWizard)"></a>

Si vous ne trouvez pas de module pour votre transporteur, que ce soit dans les modules intégrés ou sur la marketplace Addons, vous devez alors créer votre transporteur vous-même, grâce à l'assistant que PrestaShop met à votre disposition. Cliquez sur "Créer un transporteur".

Dans cette section, nous allons créer un transporteur de A à Z. Vous pouvez créer autant de transporteurs que nécessaire.  
Si un transporteur propose plusieurs services de livraison, vous devriez créer autant de transporteurs dans PrestaShop, et les différencier par leur nom.

Nombre d'informations demandées par les formulaires de PrestaShop doivent vous être fournies par vos transporteurs une fois que vous avec un compte chez eux, ou que vous êtes en contrat direct avec eux. Vérifiez auprès d'eux afin de vous assurer que tout est configuré correctement.

Pour créer un nouveau transporteur, cliquez sur le bouton "Créer un transporteur" de la page "Transporteurs". Cela ouvrira l'Assistant de Création de Transporteur.

### Premier volet : paramètres généraux <a id="G&#xE9;rerlestransporteurs-Premiervolet:param&#xE8;tresg&#xE9;n&#xE9;raux"></a>

Vous allez commencer par décrire le transporteur, en donnant les informations dont le client aura besoin pour reconnaître et choisir le transporteur qu'il préfère.

![](../../../.gitbook/assets/52298299.png)

Voici les informations que vous devez saisir :

* **Nom du transporteur**. Le nom du transporteur est public, donc utilisez le nom officiel. Si vous avez plusieurs transporteurs PrestaShop pour les services de livraison d'un même transporteur, vous pourrez les différencier par le nom. Vous pouvez également y ajouter une description du service. Par exemple, vous pourriez utiliser "PrestaLivraison – 500 kg et plus".
* **Délai de livraison**. L'estimation du temps qu'il faut au transporteur pour livrer votre produit, écrit en français. Cette information est affichée durant la commande. Elle aidera vos clients à choisir leur transporteur en fonction du temps qu'ils sont prêts à attendre pour recevoir leur achat. Les clients acceptent souvent de payer plus cher pour recevoir un colis plus rapidement. Vous devez remplir le champ dans toutes les langues disponibles, notamment celle par défaut.
* **Vitesse**. Le champ "Délai de livraison" peut contenir n'importe quel texte, et n'est donc pas utilisé pour comparer les transporteurs entre eux. Le réglage "Vitesse" vous permet de donner une note au transporteur, de 0 \(très lent\) à 9 \(très rapide\). Cette valeur est ensuite utilisée pour comparer les transporteurs entre eux en fonction de leur rapidité, et aider les clients à choisir celui qu'ils préfèrent.
* **Logo**. Le fait d'avoir un logo aide les clients à plus rapidement différencier les transporteurs. PrestaShop redimensionnera votre image afin de tenir dans le formulaire de commande. Le logo apparaîtra sur chaque volet de l'Assistant, afin de vous rappeler quel transporteur vous êtes en train de modifier/créer.
* **URL de suivi**. Ce champ doit être rempli avec l'adresse de suivi fournie par votre transporteur \(s'il en a une\). Par exemple, le service postal français, La Poste, propose l'adresse suivante : [`http://www.colissimo.fr/portail_colissimo/suivreResultat.do?parcelnumber=@`](http://www.colissimo.fr/portail_colissimo/suivreResultat.do?parcelnumber=@). Quand le client a choisi son transporteur, il recevra l'adresse que vous avez saisie dans ce champ, avec le signe "@" remplacé par le numéro de suivi fourni par le transporteur, ce qui lui permettra de cliquer sur le lien et voir où en est sa livraison.

Cliquez sur "Suivant" pour accéder au deuxième volet.

### Deuxième volet : destination d'expédition et coûts <a id="G&#xE9;rerlestransporteurs-Deuxi&#xE8;mevolet:destinationd&apos;exp&#xE9;ditionetco&#xFB;ts"></a>

![](../../../.gitbook/assets/52298299.png)

Ce panneau présente tout d'abord une poignée de réglages :

* **Ajouter le frais de manutention**. Ajoute ou enlève les frais de manutention du prix du transporteur, tels que paramétrés dans la page "Préférences" \("Frais de manutention"\).
* **Livraison gratuite**. Si cette option est activée, vous ne pourrez pas indiquer de prix de livraison. Si cette option est désactivée, vous pourrez modifier les tranches et les coûts par pays dans le formulaire plus bas.
* **Facturation**. Au moment de facturer le client pour le transport, PrestaShop peut appliquer deux comportements, que vous devez configurer en fonction de la manière dont votre transporteur gère sa facturation \(donc lisez bien leur documentation\) : 
  * **En fonction du prix total**. La facturation dépend du prix total de la commande.
  * **En fonction du poids**. La facturation dépend du poids total de la commande.
* **Taxe**. Indique sur le transporteur requiert une taxe locale afin de livrer, et le cas échéant, laquelle. La taxe doit déjà avoir été créée dans PrestaShop \(ce qui se fait dans la page "Taxes" du menu "International"\).
* **Comportement hors tranches**. Au cas où le transporteur choisi n'a pas de coût d'expédition en place pour la zone ou le poids requis, vous pouvez indiquer la manière dont PrestaShop doit réagir. Vous avez deux options :
  * **Prendre la tranche la plus grande**. PrestaShop prendra la tranche la plus chère et appliquera ses conditions.
  * **Désactiver le transporteur**. PrestaShop ne proposera pas ce transporteur, étant donné qu'il ne livrera probablement pas cette commande.

Vient ensuite la section importante : la création des tranches du transporteur. C'est une étape très importante, car PrestaShop a besoin de cette information pour présenter au client les transporteurs qui peuvent effectivement livrer sa commande. En effet, en fonction du prix total ou du poids total de la commande, certains transporteurs ne seront pas disponibles tandis que d'autres ne le seront que pour certaines valeurs. Vous devez donc remplir ces tranches très précisément, et de préférence en suivant la documentation de chaque transporteur.

C'est ici que l'Assistant de Création de Transporteur prend tout son sens. Avec cette interface, vous pourrez construire les tranches de prix ou de poids \(en fonction de votre sélection dans l'option "Choix de la tranche" ci-dessus\), une tranche après l'autre, en appliquant vos prix pour chaque zone à chaque tranche.

Les zones doivent avoir été définies auparavant. Pour cela, rendez-vous dans la page "Zones géographiques" du menu "International".

La création de chaque tranche ne nécessite que quelques étapes :

1. **Mettre en place les limites inférieures et supérieures de la tranche que vous êtes en train de créer**. En fonction de votre choix de type de tranche, celle-ci affichera "Sera appliquée lorsque le poids est" ou "Sera appliquée lorsque le prix est" pour la limite inférieure, et "Sera appliquée lorsque le poids est" ou "Sera appliquée lorsque le prix est" pour la limite supérieure.

   Notez que la limite inférieure est incluse \(&gt;=\), tandis que la limite supérieure est exclue \(&lt;\). Cela signifie que la limite supérieure d'une tranche doit avoir la même valeur que la limite inférieure de la tranche suivante, car les deux ne se superposent pas.

2. **Indiquez les prix**. Dès que les limites inférieures et supérieures sont en place, PrestaShop rend le champ "Toutes" disponible. Il s'agit d'un champ spécial : toute valeur que vous y saisirez sera répliquée dans tous les champs des zones géographiques disponibles, sans action de votre part. Vous pouvez ensuite modifier la valeur de chaque zone individuellement. Cochez la case de chaque zone dans laquelle le transporteur livre pour cette tranche. Si le transporteur ne livre pas dans cette zone géographique pour la tranche actuelle, assurez-vous bien que la case est décochée.
3. **Créez la tranche**. Pour créer une nouvelle tranche, cliquez sur le bouton "Ajouter une nouvelle tranche". PrestaShop ajoutera une nouvelle colonne de champs pour les zones. À nouveau, mettez en place les limites inférieures et supérieures de cette tranche, puis indiquez les prix par zone.

Les unités de poids et de prix sont ceux définis par défaut dans votre installation de PrestaShop, et ceux que vos produits utilisent. Vous pouvez modifier ces unités dans la page "Localisation" du menu "International".

Cliquez sur "Suivant" pour accéder au troisième volet.

### Troisième volet : taille, poids et groupes associés <a id="G&#xE9;rerlestransporteurs-Troisi&#xE8;mevolet:taille,poidsetgroupesassoci&#xE9;s"></a>

![](../../../.gitbook/assets/52298301.png)

Ce volet présente deux jeux d'options :

* **Hauteur/Largeur/Profondeur/Poids maximum du paquet**. Vous pouvez indiquer le poids et la taille minimal et maximal d'un transporteur, des informations essentielles pour choisir correctement. La valeur à utiliser pour les unités par défaut de poids et de dimension, tels que configurées dans la page "Localisation" du menu "International".
* **Groupe d'accès**. Il se peut que vous ne vouliez donner accès à ce transporteur qu'aux membres d'un groupe précis. Cette option vous en donne la possibilité.

Cliquez sur "Suivant" pour accéder au quatrième et dernier volet.

### Quatrième volet : récapitulatif <a id="G&#xE9;rerlestransporteurs-Quatri&#xE8;mevolet:r&#xE9;capitulatif"></a>

Ce dernier volet vous donne une vue d'ensemble de vos réglages pour ce transporteur.

Si certains réglages ne sont pas bons, vous pouvez revenir aux volets précédents en cliquant soit sur le bouton "Précédent", soit directement sur l'onglet du panneau.  
Si vous souhaitez enregistrer ce transporteur comme brouillon pour le moment afin d'y revenir plus tard, désactivez-le à l'aide de l'option "Activé" en bas du volet final.  
Dans tous les cas, cliquez sur le bouton "Terminer" pour enregistrer votre travail, et créer le transporteur.

Lorsque vous utilisez PrestaShop en mode multiboutique, un autre volet apparaît, et l'ordre des volets se retrouve changé :

1. Paramètres généraux
2. **Multiboutique**
3. Destination d'expédition et coûts
4. Taille, poids et groupes associés
5. Récapitulatif

Tous les volets restent identiques à leurs descriptions ci-dessus. Le nouveau volet, "Multiboutique", vous permet de limiter ce transporteur à une sélection de vos boutiques.

Le nouvel assistant ne permet pas à l'heure actuelle de créer des tarifs de transporteur par boutique : les tarifs mis en place s'appliquent à toutes les boutiques.  
Pour avoir des frais de port différents en fonction de la boutique, il vous faut créer des transporteurs différents : une version d'un transporteur \(et de ses tarifs\) par boutique. Utilisez ensuite l'onglet "Multiboutique" pour assigner ce transport à une boutique ou à un groupe de boutiques.

