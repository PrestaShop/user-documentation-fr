# Interface de la page multiboutique

## L'interface multiboutique <a id="Interfacedelapagemultiboutique-L&apos;interfacemultiboutique"></a>

### Gérer vos boutiques <a id="Interfacedelapagemultiboutique-G&#xE9;rervosboutiques"></a>

La page "Multiboutique" comprend trois sections principales :

* **Arbre multiboutique**. Vous donne un aperçu global de vos groupes de boutiques, et de leurs boutiques, et même des adresses web rattachées à une boutique. Par défaut, il n'y a qu'une seule boutique, dans le groupe par défaut : votre boutique principale.
* **Groupe de boutique**. Liste les groupes de boutiques disponibles. Vous pouvez les modifier en cliquant sur l'icône "Modifier" à droite.
* **Options multiboutiques**. Liste les options disponibles pour les boutiques existantes.
  * **Boutique par défaut**. La boutique par défaut est celle qui vous sert de point central pour toutes les autres, partage ses détails avec d'autres boutiques \(produits, transporteurs, etc.\), et est celle qui apparaît quand vous vous connectez à l'administration.

![](../../.gitbook/assets/52625505.png)

## Un seul back office pour plusieurs boutiques Front-Office <a id="Interfacedelapagemultiboutique-UnseulbackofficepourplusieursboutiquesFront-Office"></a>

Une fois que la fonctionnalité multiboutique est activée dans votre installation de PrestaShop 1.5, de nombreux aspects de PrestaShop sont personnalisables pour chaque boutique.

Pour vous permettre de savoir à quelle boutique vos modifications vont être appliquées, PrestaShop ajoute un sélecteur en haut de chaque écran, grâce auquel vous pourrez choisir le champ d'application de vos modifications :

* application à toutes les boutiques de votre installation de PrestaShop.
* application aux boutiques du groupe sélectionné seulement.
* application à la boutique sélectionnée seulement.

![](../../.gitbook/assets/52625506.png)

Le sélecteur de boutique vous aide à savoir dans quelle boutique vous êtes en train de travailler.

Cela étant, une fois que le mode multiboutique a été activé, nombre des options du logiciel ne peuvent plus être modifiées que dans un contexte global \(toutes les boutiques\), notamment les pages international et paramètres. Ces pages présentent donc les options comme étant désactivées pour tout autre contexte. Cependant, vous pouvez choisir de modifier ces réglages dans un contexte plus local \(par groupe de boutiques ou même par boutique\) si nécessaire.

En effet, les pages de réglages apparaîtront comme d'habitude dans le contexte "Toutes les boutiques", tandis que tout autre contexte \(groupe de boutiques ou boutique seule\) affichent des options en plus :

* une option "Oui/Non" en haut de chaque section des pages de réglages.
* une case à cocher pour chaque option.

![](../../.gitbook/assets/57082010.png)

Ils ont tous la même utilité : vous permettre d'activer les options qui seraient autrement désactivées dans le contexte de boutique en cours. Vous pouvez choisir les options que vous voulez activer, ou activer toutes les options de la section en passant l'option globale à "Oui". Une fois activés, il vous revient de changer la valeur de chaque option : cliquer sur une case ou passer à "Oui" ne changent pas les réglages, ils ne font que vous autoriser à les changer dans ce contexte.

Malgré tout, certaines options ne peuvent pas être modifiées dans un contexte local : ils affichent alors "Vous ne pouvez pas changer la valeur de ce champ de configuration dans le contexte de la boutique actuelle."

Dans le tableau suivant, vous trouverez si un élément peut être personnalisé par boutique, par groupe de boutiques ou pour toutes les boutiques en même temps.

<table>
  <thead>
    <tr>
      <th style="text-align:left">&#xC9;l&#xE9;ment</th>
      <th style="text-align:left">Par boutique</th>
      <th style="text-align:left">Par groupe de boutique</th>
      <th style="text-align:left">Toutes les boutiques</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">Employ&#xE9;s</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
    </tr>
    <tr>
      <td style="text-align:left">Groupes de clients</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
    </tr>
    <tr>
      <td style="text-align:left">Produits</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
    </tr>
    <tr>
      <td style="text-align:left">&#x2014; Prix</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
    </tr>
    <tr>
      <td style="text-align:left">&#x2014; D&#xE9;clinaisons et prix</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
    </tr>
    <tr>
      <td style="text-align:left">&#x2014; Langues</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
    </tr>
    <tr>
      <td style="text-align:left">&#x2014; Images multiples (<b>sauf l&apos;image principale</b>)</td>
      <td
      style="text-align:left">X</td>
        <td style="text-align:left">X</td>
        <td style="text-align:left">X</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <p>&#x2014; Quantit&#xE9;s disponibles &#xE0; la vente, &#xE0; condition
          que :</p>
        <ul>
          <li>L&apos;option de partage des quantit&#xE9;s disponibles &#xE0; la vente
            ait &#xE9;t&#xE9; coch&#xE9;e pour le groupe,</li>
          <li>Le groupe ne partage pas ses quantit&#xE9;s avec une boutique en dehors
            du groupe.</li>
        </ul>
      </td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">&#x2014; Toutes les autres informations (description, tags, URL simplifi&#xE9;es,
        etc.)</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
    </tr>
    <tr>
      <td style="text-align:left">Valeurs et Attributs, Caract&#xE9;ristiques</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
    </tr>
    <tr>
      <td style="text-align:left">R&#xE9;ductions : r&#xE8;gles de promotions panier</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">R&#xE9;ductions : r&#xE8;gles de promotions catalogue</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">R&#xE8;gles de taxes</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
    </tr>
    <tr>
      <td style="text-align:left">Cat&#xE9;gories (<b>sauf l&apos;image principale</b>)</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
    </tr>
    <tr>
      <td style="text-align:left">Transporteurs</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
    </tr>
    <tr>
      <td style="text-align:left">Entrep&#xF4;ts</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
    </tr>
    <tr>
      <td style="text-align:left">Stock avanc&#xE9;</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Fournisseurs</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
    </tr>
    <tr>
      <td style="text-align:left">Marques</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
    </tr>
    <tr>
      <td style="text-align:left">Pages CMS</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
    </tr>
    <tr>
      <td style="text-align:left">Contacts</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
    </tr>
    <tr>
      <td style="text-align:left">Pays
        <br />Le statut d&apos;un pays (activ&#xE9; ou d&#xE9;sactiv&#xE9;) est commun
        &#xE0; toutes les boutiques auxquelles il est associ&#xE9;.</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
    </tr>
    <tr>
      <td style="text-align:left">Devises</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
    </tr>
    <tr>
      <td style="text-align:left">Langues</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
    </tr>
    <tr>
      <td style="text-align:left">Modules</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
    </tr>
    <tr>
      <td style="text-align:left">&#x2014; Points d&apos;accroche et exceptions</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
    </tr>
    <tr>
      <td style="text-align:left">&#x2014; Activation / D&#xE9;sactivation</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
    </tr>
    <tr>
      <td style="text-align:left">&#x2014; Configuration (par exemple nom d&apos;utilisateur et mot de passe
        pour PayPal)</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Modules de paiement</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
    </tr>
    <tr>
      <td style="text-align:left">&#x2014; Restrictions par pays</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">&#x2014; Restrictions par devise</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">&#x2014; Restrictions par groupe d&apos;utilisateur</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">URLs personnalis&#xE9;es</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Sc&#xE8;nes</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
    </tr>
    <tr>
      <td style="text-align:left">Comptes service web</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
      <td style="text-align:left">X</td>
    </tr>
    <tr>
      <td style="text-align:left">Carrousel d&apos;image (slider) pour votre page d&apos;accueil</td>
      <td
      style="text-align:left">X</td>
        <td style="text-align:left"></td>
        <td style="text-align:left"></td>
    </tr>
  </tbody>
</table>

Notes

**Catégories** : un produit apparaît en front office dans une catégorie donnée d'une boutique si et seulement si il a été associé à cette catégorie dans le contexte de la boutique. En d'autres termes : si les boutiques A et B ont en commun la catégorie C, on peut associer un produit P dans le contexte de la boutique A à la catégorie C, et ce produit P ne sera pas visible dans la boutique B à la catégorie C.

**Transporteurs** : vous pouvez gérer les associations de transporteurs par boutique, par groupe, ou sur l'ensemble des boutiques, mais pas personnaliser un transporteur par boutique. Il faut dupliquer le transporteur si vous souhaitez utiliser un même transporteur avec des tranches de prix différentes sur deux boutiques.

**Entrepôts** : bien que la gestion avancée du stock ne puisse être utilisée qu'avec une boutique à la fois, les entrepôts peuvent être gérés par groupe de boutiques, et vous pouvez simplement gérer les entrepôts pour manipuler le stock de manière avancé.

Pour chaque boutique, vous pouvez définir des prix spécifiques pour les produits, partager tout ou partie du catalogue, changer les images des produits, etc.

Vous pouvez choisir de partager les comptes clients pour permettre à vos clients de s'identifier sur l'ensemble de vos boutiques avec les mêmes identifiants, et même de se connecter à toutes vos boutiques de manière transparente.

Avec la gestion avancée des stocks, vous pouvez gérer plus finement les associations entre les entrepôts et les boutiques.

