# Grille d'évaluation pour le TP3
## Structure, sémantique, accessibilité, API des formulaires HTML5
- [X] __Regrouper les éléments de formulaire de même nature__ (0.85/1 point)
    - Utiliser des `<fieldsets>`
    - Faire des groupes d’`<option>`s dans une liste déroulante
- [X] __Étiqueter__ (0.8/1 point)
    - Étiqueter les groupes d’éléments de formulaire
    - Nommer chaque groupe avec une `<legend>`
    - Étiqueter un groupe d’`<option>`s d’une liste déroulante
    - Étiqueter avec un `<label>` les champs de formulaire
- [X] __Tester l'accessibilité__ (0.8/1 point)
    - Rendre (garder) le formulaire navigable au clavier
    - Baliser avec précision les éléments de formulaire
    - Bien choisir le type du `<input>`
    - Code sémantique et valide pour l’ensemble du document
- [X] __Ajouter des containtes de saisie__ (0.9/1 point)
    - Identifier par un attribut approprié les champs obligatoires du formulaire
    - Ajouter des contraintes de saisie sur les champs de formulaire

## Styles CSS
- [X] __Aligner les éléments de formulaire__ (.8/1 point)
    - Contrôler les espacements
- [X] __Intégrer tous les contenus__  (1 point)
    - Selon les guides visuels (ou mieux !)
- [X] __Styler l’interactivité__  (.75/1 point)
    - État focus, état checked des éléments de formulaires
    - États des hyperliens (link, visited, hover, active)
    - Styler les messages d’erreur
    - Utiliser des sprites CSS
- [X] __Styler les boutons radio__  (.75/1 point)
    - en les gardant accessibles au clavier

## Méthodes de travail favorisant la collaboration
- [X] __Organiser et documenter la feuille de styles__  (0.85/1 point)
- [X] __Utiliser le contrôle des versions GIT__  (1 point)
    - Un minimum de 3 commits est attendu pour les étapes html, css, contrôle qualité finale



## Note et commentaires
<span style='color:red'> 8.5 / 10</span>

Bon travail autant en HTML qu'en CSS, les contraintes de saisie sont bien implémentées mais certaines pourraient être améliorées comme pour la saisie de la date, il devrait y avoir des attributs `min` et `max` entre autres pour empêcher d'obtenir des valeurs négatives en appuyant sur la flèche vers le bas.
- [Plusieurs erreurs HTML](images/erreurs-html.pdf)  
Principalement en raison d'un mauvais emboîtement de balises. Pour améliorer cet aspect du travail il serait essentiel d'utiliser le validateur du w3c pour détecter et corriger ce type d'erreurs. On peut aussi porter plus d'attention à l'arborescence HTML en utilisant davantage les petites poignées pour ouvrir et fermer les blocs de code.
- Les regroupements d'`<option>` dans le `<select>` avec des balises `<optgroup>` ne sont pas réussis. La balise de fermeture  `</optgroup>` doit être placé après les `<option>` de ce groupe.
- Une classe "sanspuces" est utilisée sur la liste des boutons radio mais le style `list-type:none` ne lui était pas appliqué.
- Il manque des styles d'interactivité sur les boutons radio. Voir les commentaire dans le code.


## Barème
| Barème | sur 1 |
|--------|-------|
| A+     | 1     |
| A      | 0.95  |
| B+     | 0.9   |
| B      | 0.85  |
| C+     | 0.8   |
| C      | 0.75  |
| D      | 0.65  |
