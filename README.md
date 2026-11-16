# Menu des Délicieuses Bouchées

Étape 2 du projet GoMyCode : une page HTML de menu de restaurant avec un tableau, des images et des balises sémantiques. Le contenu répétitif du tableau a été généré avec l'aide d'une IA, puis vérifié et corrigé.

## Contenu du dépôt

- `menu.html` : la page du menu (version corrigée)
- `images/` : les images des plats
- `screenshots/` : les captures d'écran de l'étape IA et du débogage

## Ce que j'ai fait

- J'ai construit moi-même la structure de la page (`<header>`, `<main>`, `<section>`, `<footer>`) et le tableau (`<table>`, `<thead>` et les colonnes Image, Nom du plat, Description, Prix).
- J'ai utilisé une IA pour générer les lignes du menu : 3 sections (Entrées, Plats principaux, Desserts) avec 3 plats chacune.
- J'ai relu le code généré, je l'ai débogué et amélioré.
- Au moins 2 plats ont une vraie image avec un attribut `alt` descriptif.

## Étape IA

### Prompt utilisé

![Prompt envoyé à l'IA](screenshots/prompt-ia.png)

### Réponse de l'IA

![Réponse de l'IA](screenshots/reponse-ia.png)

## Étape de débogage

### Code corrigé

![Code corrigé](screenshots/code-corrige.png)

### Explication des changements

J'ai découpé le tableau en trois `<tbody>` avec des `<th scope="colgroup">` pour que chaque section (Entrées, Plats principaux, Desserts) soit bien structurée et lisible par les lecteurs d'écran. J'ai remplacé l'attribut `width` des images par du CSS pour un affichage uniforme, et j'ai ajouté un `<caption>` et des `scope` sur les en-têtes pour améliorer l'accessibilité. Les attributs `alt` générés par l'IA étaient déjà descriptifs, je les ai donc conservés.

## Auteur

Theghis, étudiant GoMyCode
