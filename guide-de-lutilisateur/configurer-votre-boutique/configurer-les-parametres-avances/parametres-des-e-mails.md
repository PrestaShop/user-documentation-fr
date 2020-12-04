# Paramètres des e-mails

Votre boutique envoie de nombreux message tout du long des étapes de création de compte et de passage de commande. Sur cette page, vous pourrez configurer la manière dont les messages sont envoyés.

## Liste des e-mails <a id="Param&#xE8;tresdese-mails-Listedese-mails"></a>

Une première section liste tous les e-mails qui ont été envoyés depuis votre boutique PrestaShop, avec le destinataire, le modèle utilisé, la langue de l'e-mail, son objet et l'heure de l'envoi. Cela vous permet de garder trace des communications envoyées à vos clients.

![](../../../.gitbook/assets/52298460.png)

## Adresse e-mail <a id="Param&#xE8;tresdese-mails-Adressee-mail"></a>

C'est ici que vous décidez de la manière de vos e-mails sont envoyés.

Le formulaire a trois jeux d'options :

![](../../../.gitbook/assets/52298461.png)

* **Envoyer l'e-mail à**. C'est un réglage front-end. À la fin du processus d'achat, un client peut laisser un message à destination de votre équipe. Vous pouvez choisir à qui ce message sera envoyé en utilisant la liste déroulante. Pour ajouter une adresse, rendez-vous dans "Paramètres de la boutique &gt; Contact".
* Configuration technique : la manière dont les e-mails sont techniquement envoyés. Choisissez l'une des trois options. Voir ci-après pour plus d'information.
* Configuration visuelle : la manière dont les e-mails sont visuellement envoyés. Choisissez l'une des trois options. Voir ci-après pour plus d'information.
* **Loguer les e-mails envoyés**. Désactivez cette option si vous ne souhaitez plus garder trace des emails envoyés par votre boutique \(via la liste d'emails de la première section\).

### Configuration technique <a id="Param&#xE8;tresdese-mails-Configurationtechnique"></a>

La suite de cette section vous permet de configurer PrestaShop pour envoyer des e-mails aux clients. Cependant, nous vous conseillons fortement de vérifier auprès de votre hébergeur les réglages à utiliser.

Les options sont les suivantes :

* **Ne jamais envoyer d'e-mails**. Gardez ce réglage lorsque vous faites des tests. Une fois votre boutique rendue publique, vous ne devriez jamais utiliser ce réglage.
* **Utiliser la fonction mail\(\) de PHP**. Cette option est recommandée par défaut. Si elle ne marchait pas, utilisez l'option SMTP ci-dessous.
* **Utiliser mes propres paramètres SMTP**. Dans ce cas, une nouvelle section apparaît, avec de nouveaux champs. Les informations de ces champs devraient vous être fournies par votre hébergeur : nom du domaine de mail, serveur SMTP, etc. Faites en sorte de retranscrire exactement ce que votre hébergeur vous envoie.

Les informations de configuration SMTP doivent être fournies par l'une de ces entités :

* Votre administrateur système,
* Votre hébergeur Web,
* Votre fournisseur d'accès Internet,
* Votre fournisseur d'e-mails.

![](../../../.gitbook/assets/52298462.png)

Votre hébergeur peut vous indiquer si le nom d'utilisateur est obligatoire, ainsi que le mot de passe et le type de cryptage à utiliser.

Par exemple, dans le cas de GMail \(le service de mail proposé par Google\), saisissez les informations suivantes :

* Serveur SMTP : [smtp.gmail.com](http://smtp.gmail.com)
* Utilisateur : [nom.utilisateur@gmail.com](mailto:nom.utilisateur@gmail.com) \(exemple\)
* Mot de passe : RT22UE87 \(exemple\)
* Cryptage : SSL
* Port : 465

### Configuration visuelle <a id="Param&#xE8;tresdese-mails-Configurationvisuelle"></a>

Il y a deux formats disponibles pour les e-mails : HTML, qui est très joli mais peut ne marcher partout ; et texte, qui est n'est pas folichon mais fonctionne partout.

Vous pouvez choisir l'un des deux, ou les deux. Nous vous recommandons de choisir les deux.

## Essai de votre configuration mail <a id="Param&#xE8;tresdese-mails-Essaidevotreconfigurationmail"></a>

Une fois que vous avez configuré vos envois d'e-mails avec l'une ou l'autre des méthodes proposées, saisissez vos adresses e-mail dans le champ intitulé "Envoyer un mail test à", puis cliquez sur le bouton "Envoyer un mail test".  
Vérifiez maintenant la boite de réception de l'adresse fournie, afin de vérifier que vous avez bien reçu le mail de test. Si vous ne l'avez pas reçu, veuillez modifier votre configuration en conséquence.

![](../../../.gitbook/assets/52298463.png)

