# Comment ajouter le briefing Sortlist à votre site

## Fonctionnement 

### 1. Copiez ce snippet HTML dans votre code source
```html
<div class="sortlist-briefing"></div>
```
### 2. Mise en place
La `<div>` avec la classe “sortlist-briefing” peut être ajoutée n’importe où sur la page, y compris en plusieurs exemplaires. Chacune contiendra un bouton. Si vous souhaitez personnaliser le design, vous pouvez viser `.sortlist-briefing` > a dans votre fichier CSS

### 3. Placer le script
Placer le script suivant:
```html
<script src="https://www.sortlist.com/api/briefing-embed?source=https%3A%2F%2Fyourwebsite.fr&text=Trouver%20des%20agences&domain=fr&expertiseId=58&country=FR"></script>
```

Le `<script>` peut être placé, une fois seulement, à la fin du `<body>` afin de ne pas bloquer le chargement de la page. Ce script chargera seulement le `<button>` et une simple fonction javascript, donc les performances de votre site ne seront pas impactées au chargement.


## Paramètres disponibles:

Comme vous pouvez le voir, dans le lien `src=` du script de l'étape 3, il y a un paramètre que **vous devez modifier** et d'autres qui aideront vos conversions.

`https://www.sortlist.com/api/briefing-embed?source=https%3A%2F%2Fyourwebsite.fr&text=Trouver%20des%20agences&domain=fr&expertiseId=58&country=FR`

| Paramètre   | Type              | Modification  | Description  | 
| :---------- | :---------------- | :--------    | :---- | 
| `source`    | URL encodée | **Obligatoire** | L'URL [encodée](https://www.convertstring.com/fr/EncodeDecode/UrlEncode) de votre site. Sera utilisé pour le tracking et peut contenir le query param d’une plateforme d’affiliation ou des utm. | 
| `text`      | Texte      | Optionelle | Le texte du bouton, défaut est `Trouver des agences` |
| `domain`    | TLD      | Optionelle | Le domaine Sortlist vers lequel vous désirez pointer. On suggère par défaut d'utiliser `fr` |
| `country`    | Iso31661      | Optionelle | Un des codes pays disponibles : (FR, BE, DE). Sera utilisé pour préremplir la question à propos de la localisation et améliorera vos conversions.  |


## Des questions?

Contactez **Olivier Danniau**, notre responsable partenariats France au [+33 (0) 7 56 93 64 56](tel:+33756936456)
