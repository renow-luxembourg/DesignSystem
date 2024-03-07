Dans le cas où le label serait masquée, le libellé du champ doit être rendu visible de différentes manières : dans le texte de "placeholder" mais aussi dans l’attribut `title` du champ (pour être accessible aux technologies d’assistance). Cette pratique est à réserver exclusivement aux formulaires à champ unique.
Une alternative possible est de déplacer visuellement le label dans le champ puis de le décaler lors de la saisie. ([Exemple Material design](https://m2.material.io/components/text-fields#interactive-demo))
 
**Note** : La classe `.sr-only` est utilisée pour rendre le label visible uniquement par les lecteurs d’écran. Suivant les sources, cette classe peut avoir d’autres noms, `.visually-hidden` ou `.at` sont fréquemment utilisées (Plus d’information sur les [styles applicables à cette classe]( https://www.w3.org/WAI/WCAG21/Techniques/css/C7.html)).

**Note** : lorsque l’attribut `placeholder` est présent, il est susceptible d’être restitué à la place de l’attribut `title`. Par conséquent, lorsque ces deux attributs `title` et `placeholder` sont présents, ils doivent être identiques. 
