# Paramètres de log

Des problèmes surviendront tôt ou tard. La plupart du temps, vous n'en avez pas conscience car le système les gère pour vous. Mais vous pourriez vouloir les connaître, afin de corriger les plus courants, et assurer à votre boutique une meilleure stabilité.

![](../../../.gitbook/assets/52298487.png)

La page "Log" vous permet de voir l'ensemble des actions réalisées sur votre boutique, et remonte les erreurs PHP qui surviennent. Elles sont consignées dans le tableau central du sous-onglet, et sont présentées sous 4 niveaux d'importance

* **1 : À but informatif**. Indiquent que le script a rencontré quelque chose qui peut être une erreur, mais peut aussi être un événement normal dans la vie du script.
* **2 : Avertissement**. Indiquent un problème qui doit être intercepté par le script durant l'exécution du script.
* **3 : Erreur**.
* **4 : Problème majeur (erreur critique)**. Indiquent des erreurs qui ne peuvent pas être ignorées, comme des problèmes d'allocation de mémoire, par exemple.

Ces explications proviennent du manuel de PHP. Pour en apprendre plus, lisez [http://www.php.net/manual/fr/errorfunc.constants.php](http://www.php.net/manual/fr/errorfunc.constants.php).

## Alerte par e-mail <a href="parametresdelog-alertepare-mail" id="parametresdelog-alertepare-mail"></a>

Ces niveaux servent également de valeur pour la fonctionnalité d'alerte par e-mail.\
PrestaShop ajoute une dernière valeur, 5, qui indique que l'administrateur ne souhaite recevoir aucune notification en cas de problème, qu'il soit majeur ou mineur.

![](../../../.gitbook/assets/52298488.png)

Le système de gestion d'erreur vous permet également d'être notifié par e-mail des dernières erreurs. Les notifications sont envoyées sur l'adresse e-mail du propriétaire de la boutique, et vous pouvez configurer le niveau d'importance à partir duquel vous recevrez ces e-mails :

* "1" si vous voulez tout savoir, même la plus petite indication.
* "3" si vous ne voulez être tenu au courant que des erreurs (simples ou majeures).
* "4" pour ne garder que les erreurs majeures.
* "5", le réglage par défaut, n'envoie aucune notification.
