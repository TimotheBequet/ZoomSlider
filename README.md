# ZoomSlider

## Utilisation :
La navigation entre les slides se fait :
- soit avec le scroll de la souris : 
    - scroll vers le bas -> slide suivante
    - scroll vers le haut, slide précédente

- soit avec les flèches directionnelles :
    - flèche droite ou bas -> slide suivante
    - flèche gauche ou haut -> slide précédente

- soit en cliquant sur les éléments du menu


## Code :
#### Analyse : 
##### HTML :
Le code HTML est découpé en 2 parties : un header, un body.
Le header contient une nav, contenant elle-même des liens vers chaque slide.
L'espacement entre les liens est géré avec Bootstrap 5.
Les slides sont des div.

##### CSS :
Tous les effets visuels 'statiques' (à l'exception de l'effet glow sur l'élément actif de la nav) sont gérés dans le CSS.
Ils peuvent être modifiés à volonté, ça n'impactera pas l'effet de transition entre les slides.

##### JavaScript :
L'effet de transition entre les slides ainsi que tous les écouteurs et gestion d'évènements sont gérés en JS.
Lorsqu'une animation de transition est lancée, on bloque l'action de changement de slide le temps que l'animation se termine (1.5 secondes).


## CodePen.io :
Lien vers la page codepen.io (ne prend pas en compte Bootstrap) : [https://codepen.io/TimotheBequet/pen/eYjgxyR](https://codepen.io/TimotheBequet/pen/eYjgxyR)