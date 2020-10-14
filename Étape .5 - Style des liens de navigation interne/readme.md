## Étape 5 - Style des liens de navigation interne

**But de l'étape :** Changer le style de la section contenant les liens de navigation pour que tout soit aligné et suive le thème du CV.

Dans le fichier `style.css` :

- Écrire des règles pour l'élément `<nav>` qui lui donnent une hauteur de `70` pixels et changent son affichage (`display`) en conteneur flexible (valeur `flex`).
- Écrire des règles pour la classe `secondary-block` qui changent sa couleur de texte en blanc et change sa couleur de fond avec la valeur `rgb(4, 117, 186)`.
- Écrire une règle pour les éléments `<a>` qui change leur couleur en blanc.
- Écrire les règles suivantes pour l'élément `<h2>` enfant de `<nav>` :
  - Des marges extérieures (`margin`) à `0`.
  - Des marges intérieures (`padding`) avec :
    - `20` pixels en haut.
    - `0` à droite.
    - `20` pixels en bas.
    - `15` pixels à gauche.
- Écrire les règles suivantes pour l'élément `<ul>` enfant de `<nav>` :
  - Un affichage (`display`) en mode `flex`.
  - Des marges extérieures à `0`.
  - Des marges intérieures à `24` pixels.
  - Supprimer les puces de la liste avec la propriété `list-style`.
- Écrire une règle pour les éléments `<li>` enfants de `<nav>` qui change leur marge extérieure gauche à `15` pixels.