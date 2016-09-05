- Introduction
    - Qu'est ce que le CSS ?
    - Qu'est ce que l'on va voir dans cette formation ?
    - Quel éditeur utiliser ? (bracket peut être ?)
    
## Le langage

- Comment écris-t-on du CSS ?
    - L'attribute style 
    - la balise `<style>`  
    - Dans un css séparé via `link` 
    - La syntaxe : selecteur { propriété: valeur }` 
    - les status (:hover, :focus...)
- La notion de priorité (quelle règle l'emporte) aka https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity
- Prefix navigateur et notion de compatibilité (découverte de caniuse.com et autoprefixer)

## Les règles

On ne peut pas présenter toutes les règles mais le but est de donner une base de départ et de présenter quelques règles incontournables et surtout la bible : https://developer.mozilla.org/fr/docs/Web/CSS/Reference

- La police
    - font-family
    - font-weight
    - line-height
    - color
    - text-transform
    - font-style
    - letter-spacing
    - text-shadow
    - text-align
    - @font-face, https://developer.mozilla.org/fr/docs/Web/CSS/@font-face
- Display
    - inline vs block
    - inline-block
    - table
    - flex (à placer dans un chapitre pour plus tard)
- Float (ça mérite un chapitre entier XD)
- Position
    - static
    - absolute (et donc voir le relative) top left right bottom
    - fixed / sticky
- Dimensions
    - margin / padding, comment on peut mettre une valeur négative ? dafuk ?
    - width, height
    - min-width, max-height...
- Apparence
    - background
    - border
    - box-shadow
- Transform
    - translate
    - rotate
    - scale
    
## Travaux pratique 

- Intégration de la maquette : https://dribbble.com/shots/1567242-FREE-PSD-Multipurpose-Landing-Page/attachments/319370 

## Notions avancées

- Media query
- Transitions
- Animations

## "Bonnes Pratiques" <= renommer ça parceque ça fait genre j'impose la manière de faire les choses :)

- Les unités : %, px, em, rem, ch, vw / vh - vmin / vmax
- Mobile First
- SMACSS / BEM
- Les preprocesseurs: sass, less, stylus
