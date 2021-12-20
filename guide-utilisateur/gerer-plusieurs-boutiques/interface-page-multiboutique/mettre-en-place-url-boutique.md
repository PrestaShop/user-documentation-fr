# Mettre en place l'URL d'une boutique

## Composition de l'URL d'une boutique

![](<../../../.gitbook/assets/httpswww.mystore.comwomen (6).png>)

## Avoir deux boutiques sur le même nom de domaine

Deux boutiques ne peuvent pas partager la même URL.&#x20;

Cependant, vous pouvez avoir autant de boutiques que vous le souhaitez sur le même nom de domaine en utilisant dessous-dossiers ou des sous-domaines.

### Utiliser des sous-dossiers&#x20;

![](<../../../.gitbook/assets/httpswww.mystore.comwomen (7).png>)

Si vous choisissez d'utiliser des sous-dossiers pour héberger plusieurs boutiques sur le même nom de domaine, assurez-vous de créer 2 URLs pour chaque boutique : une avec "www." et une sans.&#x20;

Sinon, les clients essayant d'accéder à votre boutique secondaire sans le "www." dans l'URL seront redirigés vers votre boutique principale.&#x20;

### Utiliser des sous-domaines

![](<../../../.gitbook/assets/httpswww.mystore.comwomen (8).png>)

{% hint style="success" %}
Vous n'avez pas besoin de créer des sous-domaines ou des sous-fichiers manuellement. PrestaShop créera automatiquement le chemin sur votre serveur.
{% endhint %}

### Utiliser un nom de domaine différent

Dans le cas où vous souhaitez utiliser un nom de domaine différent pour votre boutique supplémentaire plutôt qu'un sous-domaine ou un sous-dossier, vous devez configurer votre domaine pour qu'il pointe vers le dossier où se trouve PrestaShop. La réécriture de l'URL est alors effectuée par PrestaShop.&#x20;

Vous pouvez aussi créer un alias pour votre nom de domaine qui redirige vers l'URL absolue où se trouve votre installation de PrestaShop. La façon de réaliser cela dépend du panneau de contrôle et des options que votre société d'hébergement vous fournit : "Alias" pour Plesk, "Forward" pour CPanel, "Aliasdomain" pour ISPConfig, etc.

## Mettre en place une URL

Pour mettre en place l'URL d'une boutique:

1. Sélectionnez la boutique dans l'arbre multiboutique
2. Cliquez sur le lien "Cliquez ici pour définir une URL pour cette boutique"&#x20;
3. Remplissez le formulaire

**Options de l'URL:**&#x20;

![](<../../../.gitbook/assets/image (48).png>)

Boutique : Sélectionnez la boutique pour laquelle vous souhaitez mettre en place l'URL.

URL principale : Basculez le bouton sur "Oui" si vous souhaitez que toutes les URLs de cette boutique renvoient vers votre URL principale.

Statut : Toutes les URLs, à l'exception de l'URL principale, peuvent être désactivées.

**URL de votre boutique:**

![](<../../../.gitbook/assets/image (50).png>)

**Domain**e : Saisissez le nom de domaine de la boutique. Vous pouvez indiquer un sous-domaine si nécessaire. Assurez-vous simplement qu'il ne contient pas '`http://`', ou tout autre '`/`'. Exemple : `www.example.com` ou `kids.example.com`.&#x20;

**Domaine SSL** : Si votre domaine SSL est différent de votre domaine principal, veillez à l'indiquer dans ce champ.&#x20;

**URL physique** : Saisissez le chemin physique de votre installation sur votre serveur. Si vous avez installé votre boutique dans le répertoire racine, l'URL physique doit être `/`. Si vous avez installé votre boutique dans un sous-dossier, l'URL physique est le nom du sous-dossier.&#x20;

**URL virtuelle** : Grâce à la réécriture d'URL, vous pouvez utiliser cette option si vous souhaitez créer un magasin avec une URL qui n'existe pas sur votre serveur, sans avoir à créer un sous-dossier. Par exemple, si vous voulez que votre boutique soit disponible avec l'URL `www.example.com/my-store/shoes/`, vous devez définir `shoes/` dans ce champ, en supposant que `my-store/`est votre URL physique.&#x20;

Les URLs simplifiées doivent être activées dans **Paramètres de la boutique > Trafic et SEO.** Notez que cette option ne fonctionne que pour les boutique sous-dossiers, pas pour les boutiques sous-domaines.&#x20;

**URL finale** : Vous pouvez obtenir ici un aperçu du résultat final de l'URL de la boutique, en fonction des paramètres définis plus haut.



