# Dépôt commun pour le module Java avancé

## Ressources

Exemples de code:
- [Un exemple de projet simple libGDX + gradle](https://github.com/cdlm/daleks-gdx)
- [Des projets d'étudiants de Prague en Pharo](https://github.com/Ducasse/2017-FITCTULectureProjects)

Algorithmes, techniques de code:
- [Red Blob Games](https://www.redblobgames.com): un blog avec plein d'algos utiles pour les jeux (pathfinding, visibilité, coordonnées hexagonales…)
- [Buiding a Better Jump](https://www.youtube.com/watch?v=hG9SzQxaCm8): présentation de 25min sur les équations de mouvement pour les platformers
- Double Dispatch [wikipedia](https://en.wikipedia.org/wiki/Double_dispatch#Example_in_Ruby), [article original](https://klevas.mif.vu.lt/~plukas/resources/MultiDispatch/ingalls.pdf): une technique pour sélectionner un comportement selon le produit croisé de deux types. L'exemple en Ruby montre la version sans (un switch/case sur les types…) et la solution plus flexible. L'exemple en C++ sur wikipedia parle justement de collisions mais est écrit en utilisant la surcharge, ce qui n'aide pas à comprendre le principe de base.
- [State pattern](https://sourcemaking.com/design_patterns/state): probablement utile pour les éléments de jeu qui ont plusieurs modes qui s'enchaînent à l'exécution (e.g. gérer une activité temporaire comme un saut, qui influence animation/contrôle du personnage, sans polluer la classe personnage avec le code de toutes les activités possibles et imaginables)

Ressources graphiques etc:
- [Open Game Art](https://opengameart.org)
- [Liberated Pixel Cup](https://lpc.opengameart.org)
