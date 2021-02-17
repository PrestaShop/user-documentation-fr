# Paramètres de performances

Cette page combine de nombreux outils et conseils qui peuvent vous aider à améliorer les performances de votre boutique côté serveur, pas côté commercial – bien qu'un serveur qui fonctionne bien permet d'avoir plus de clients à la fois, et donc de faire plus de ventes.

## Smarty <a id="Param&#xE8;tresdeperformances-Smarty"></a>

Smarty est le nom du langage de template utilisé par les thèmes de PrestaShop. Vous pouvez en apprendre plus sur ce langage à l'adresse [http://www.smarty.net/](http://www.smarty.net/).

![](../../../.gitbook/assets/52298447.png)

Deux options sont disponibles :

* **Compilation des templates**. Afin d'obtenir de meilleures performances, PrestaShop conserve vos pages HTML dans un système de cache.
  * **Ne jamais recompiler les fichiers de templates**. Le comportement normal : les pages HTML sont compilées et mises en cache, puis affichées telles quelles, même si le thème a été modifié entretemps.
  * **Recompiler les fichiers de templates s'ils ont été mis à jour**. PrestaShop est en mesure de savoir si un thème a été modifié.
  * **Forcer la compilation à chaque appel**. À n'activer que si vous êtes en train de créer un thème, et que vous avez besoin de voir vos modifications à chaque rechargement.
* **Cache**. Cette option vous permet de gérer tous les caches de fichiers, et pas seulement ceux liés aux thèmes. À ne désactiver que si vous êtes en train de corriger un thème ou un module PrestaShop. Autrement, vous ne devriez sans doute pas y toucher. Le bouton "Vider le cache" en haut à droite de l'écran permet de supprimer le contenu du cache en un clic au lieu de devoir le faire en passant par un logiciel FTP.
* **Synchronisation multi-serveurs**. Lorsque vous utilisez plusieurs serveurs, cette option vous aide à synchroniser leurs caches.
* **Type de mise en cache**. Par défaut, Smarty utilise un système de cache qui se base sur des fichiers. Vous pouvez choisir d'utiliser plutôt MySQL comme resource de stockage du cache Smarty.
* **Vide le cache**. En fonction de la fréquence à laquelle votre boutique évolue, vous pouvez vouloir ne jamais vider le cache, ou au contraire le vider dès que votre boutique est modifiée \(nouveau produit ou nouveau design\).

## Mode debug <a id="Param&#xE8;tresdeperformances-Modedebug"></a>

Lorsque vous êtes en mode debug, vous pouvez choisir l'impact qu'on certaines fonctionnalités sur PrestaShop, afin de mieux repérer là d'où vient une erreur :

![](../../../.gitbook/assets/52298448.png)

* **Désactiver les modules non développés par PrestaShop**. Les modules créés par PrestaShop sont longuement testés et ne devraient pas poser de problème. Si vous activez cette option, vous pourrez si l'erreur provient du propre code de PrestaShop \(coeur ou module\), ou d'un module tiers.
* **Désactiver toutes les surcharges**. De nombreuses fonctionnalités de PrestaShop peuvent être surchargées. Si vous activez cette option, tout le code de surcharge sera désactivé, et vous pourrez voir si le problème vient du code de PrestaShop, ou d'une surcharge tierce.
* Mode debug. En activant cette option, les messages d'erreurs techniques s'afficheront dans votre interface de gestion de la boutique. Ceci est utile lorsque vous faites appel à quelqu'un de technique pour vous aider, sans pour autant lui donner les accès à votre boutique. Cette personne aura besoin de comprendre ce qu'il se passe sur votre boutique, et ces messages la guideront.

## Fonctionnalités désactivables <a id="Param&#xE8;tresdeperformances-Fonctionnalit&#xE9;sd&#xE9;sactivables"></a>

Certaines fonctionnalités de PrestaShop peuvent être désactivées si vous ne les utilisez pas, car elles peuvent ralentir votre boutique.

Si votre catalogue contient des produits qui font déjà usage de ces fonctionnalités, alors vous ne pourrez pas les désactiver. Vous devrez supprimer quelques informations produits afin de les désactiver.

Vous pouvez désactiver les fonctionnalités suivantes :

![](../../../.gitbook/assets/52298449.png)

* **Déclinaison de produit**. Les déclinaisons de produits vous permettent de créer toute une ligne de produits à partir d'un seul produit : variation de taille, de couleur, de capacité, etc.
* **Caractéristiques**. Les caractéristiques vous permettent de donner des détails sur le produit : poids, matériaux, pays d'origine, etc.

## Concaténation, Compression et mise en Cache \(CCC\) <a id="Param&#xE8;tresdeperformances-Concat&#xE9;nation,CompressionetmiseenCache(CCC)"></a>

CCC est un ensemble d'outils pour vous aider à minimiser la charge du serveur Web et le temps de chargement du thème.

Le nom est explicite : ces outils combinent les fichiers textuels de même type en un seul fichier plus gros, ce qui réduit le nombre de fichiers à télécharger ; il compresse ensuite le fichier à l'aide de l'algorithme Zip, ce qui donne des téléchargements plus rapides ; enfin, il met en cache les fichiers compressés, afin d'éviter au serveur de devoir relancer ce processus de concaténation et de compression à chaque fois qu'un fichier est demandé, ce qui alourdit la tâche du processus du serveur.

![](../../../.gitbook/assets/52298450.png)

* **"Smart cache" pour les feuilles de style**. Les fichiers CSS sont des fichiers textuels, et peuvent être combinés et compressés en toute sécurité.
* **"Smart cache" pour le code JavaScript**. Les fichiers JavaScript sont également des fichiers textuels, mais leur combinaison peut parfois être problématique. Assurez-vous de tout tester avant de laisser ce réglage activé.
* **Optimisation Apache**. Ce réglage changera la configuration de votre serveur Web afin de le rendre plus efficace dans le cadre des options CCC.

## Serveurs de média <a id="Param&#xE8;tresdeperformances-Serveursdem&#xE9;dia"></a>

Cette option vous permet de renvoyer une partie de votre trafic spécifique \(fichiers image et vidéo, par exemple\) vers d'autres serveurs en votre possession, par le biais d'autres domaines ou sous-domaines – le plus souvent hébergé au sein d'un CDN \(Content Delivery Network\). Par défaut, PrestaShop peut utiliser un serveur de média supplémentaire.

![](../../../.gitbook/assets/52298451.png)

Il ne suffit pas d'ajouter votre nom de domaine dans le champ pour soudainement faire des gains de performance. Pour autant, la mise en place d'un serveur média est une chose simple, et les gains sont réels et quasi-immédiats. Voici comment s'y prendre :

1. Ouvrez un compte chez un hébergeur spécialisé dans les contenus distribués. Les sociétés les plus connues dans ce domaine sont Akamai \([http://www.akamai.com/](http://www.akamai.com/)\), Amazon \(avec ses services AWS, dont CloudFront : [http://aws.amazon.com/fr/](http://aws.amazon.com/fr/)\) ou encore CloudFlare \([http://www.cloudflare.com/plans](http://www.cloudflare.com/plans)\). Vous pouvez également vous renseigner auprès de votre hébergeur, qui dispose peut-être d'une offre CDN.
2. Copiez vos fichiers média vers le serveur de cet hébergeur. Cela signifie que le serveur distant doit contenir une copie exacte des dossiers suivants de votre installation de PrestaShop : `/img`, `/themes` et `/modules`. Notez que vous devrez faire en sorte que ces dossiers soient toujours synchronisés : même si vous ajoutez de nouveaux produits ou des modifications de votre thème, le serveur CDN doit avoir les dernières versions de tous les fichiers.
3. Une fois le serveur CDN en place, ajoutez son adresse \(fournie par votre hébergeur CDN\) dans le premier champ "Serveur de média n°1". Si cet hébergeur vous propose d'autres serveurs, ajoutez-les.

Dans le cas où vous souhaitez que vos fichiers soient visuellement toujours chargés depuis votre nom de domaine plutôt que depuis un domaine inconnu, suivi le processus suivant :

1. Créez un sous-domaine au domaine de votre boutique, par exemple [`http://cdn1.maboutique.com`](http://cdn1.maboutique.com/) \(la méthode de création dépend de votre hébergeur, renseignez-vous auprès de lui\).
2. À la racine de chaque sous-domaine, ajoutez un fichier `.htaccess` qui contiendra simplement la ligne suivante :

   ```text
   Redirect Permanent / http://adresse-cdn.com
   ```

  
   L'adresse [`http://adresse-cdn.com`](http://adresse-cdn.com/) est à remplacer par celle de votre serveur CDN. Vous créez ainsi un renvoi automatiquement de votre sous-domaine vers votre serveur CDN

3. Une fois le sous-domaine en place, ajoutez-le dans le premier champ "Serveur de média n°1". Si cet hébergeur vous propose d'autres serveurs, créez autant de sous-domaines à votre domaine principal.

Même si vous n'avez pas de serveur CDN, vous pouvez utiliser la fonctionnalité des serveur de média pour que le navigateur de vos clients téléchargent plus de fichiers en même temps, accélérant ainsi le chargement de la page :

1. Configurez votre serveur pour qu'il dispose de sous-domaines virtuels, tel que [`images1.example.com`](http://images1.example.com/), [`images2.example.com`](http://images2.example.com/), et [`images3.example.com`](http://images3.example.com/), tous pointant vers la dossier principal de PrestaShop.
2. Dans votre page Performance, configurez chaque champ "Serveur de médias" avec ces sous-domaines virtuels.

Une fois ceci en place, PrestaShop chargera vos images depuis n'importe quel de ces sous-domaines. Dans les faits, les images seront toujours chargées depuis le même dossier \(le dossier principal\), mais le navigateur ouvrira des connexions supplémentaires vers votre serveur web, accélérant ainsi le chargement de la page.

##  Cache <a id="Param&#xE8;tresdeperformances-Cache"></a>

Le cache de votre serveur stocke des versions statiques de vos pages dynamiques, afin d'envoyer celles-ci à vos clients, et donc de réduire la charge serveur et le temps de compilation.

Dans la plupart des cas, vous devriez d'abord vérifier auprès de votre hébergeur s'il accepte ce réglage, car il nécessite une certaine configuration serveur.

Cette section vous permet d'activer le cache, et de choisir la méthode de cache :

![](../../../.gitbook/assets/52298452.png)

* **Memcached**. Un système distribué de cache. Très efficace, surtout si vous utilisez plusieurs serveurs, mais vous devrez d'abord vous assurer que votre serveur/hébergeur peut l'utiliser. Le plus souvent, si votre configuration PHP comprend l'extension PECL Memcached, tout est bon \(vous pouvez télécharger cette extension ici : [http://pecl.php.net/package/memcache](http://pecl.php.net/package/memcache)\). Vous pouvez ajouter des serveurs en cliquant sur le lien "Ajouter un serveur".
* **APC**. Une alternative gratuite et ouverte à PHP Cache, robuste mais ne fonctionnant qu'avec un serveur – ce qui est souvent le cas lorsque vous lancez votre boutique en ligne. Ici encore, vérifiez la disponibilité de l'extension PECL APC sur votre serveur : [http://pecl.php.net/package/APC](http://pecl.php.net/package/APC).
* **Xcache**. Xcache est un nouveau système de cache, spécifique au serveur Lighttpd – de fait, il ne fonctionnera pas avec le serveur Apache, l'un des plus populaires. Pour en apprendre plus, lisez [http://xcache.lighttpd.net/](http://xcache.lighttpd.net/).

