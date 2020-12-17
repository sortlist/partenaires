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

* `source` (type: URL, obligatoire, encodé comme URL, défaut: undefined-third-party)
<br>
_Sera utilisé pour le tracking et peut contenir le query param d’une plateforme d’affiliation ou des utm._
* `text` (type: text, obligatoire, encodé comme URL, défaut: Find agencies)
<br>
_Sera utilisé comme texte sur le bouton._
* `domain ` ((type: TLD, obligatoire, défaut: com))
<br>
_Un des domaines disponibles sur Sortlist (com, fr, be, de, nl, it, etc.). Sera utilisé comme domaine pour l’iframe et définira donc la langue du briefing._
* `country ` (type: Iso31661, hautement recommandé, défaut: rien)
<br>
_Un des codes pays disponibles : (FR, BE, DE).
Sera utilisé pour préremplir la question à propos de la localisation et améliorera vos conversions._

## Des questions?

Contactez **Olivier Danniau**, notre responsable partenariats France au [+33 (0) 7 56 93 64 56](tel:+33756936456)
