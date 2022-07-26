# Projet-3-OhmyFood


Ohmyfood! est une entreprise de commande de repas en ligne.  
Notre concept permet aux utilisateurs de composer leur propre menu et réduire leur temps d’attente dans les restaurants car leur menu est préparé à l’avance.  
Plus de perte de temps à consulter la carte !

![Ohmyfood! Paris ](.readme/OhmyFood_accueil.png)

## Compatibilité


La cible étant les personnes connectées et pressées, le site sera développé en utilisant
l’approche mobile-first. Pour cette raison, seules des maquettes mobiles seront réalisées.
Sur tablette et desktop, le site devra s’adapter, mais ces supports n’étant pas prioritaires, leur mise en page est libre.

- [x] - L’ensemble du site devra être responsive sur mobile, tablette et desktop.
- [x] - Les pages devront passer la validation W3C en HTML et CSS sans erreur.
- [x] - Le site doit être parfaitement compatible avec les dernières versions desktop de Chrome et Firefox.

## Technologies  

 - Le développement devra se faire en CSS, sans JavaScript.
  
 - Aucun framework ne devra être utilisé, en revanche. l’utilisation de SASS serait un plus.
  
 - Aucun code CSS ne devra être appliqué via un attribut style dans une balise HTML.


 

 - Tout le code doit être versionné sur GitHub et le site devra être accessible sur Github Pages une fois terminé.


## Effets graphiques et animations


Boutons :
- [x] - Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir.
L’ombre portée devra également être plus visible.

- [x] - À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un
bouton "J’aime" en forme de coeur

Page d’accueil :
- [x] - un “loading spinner” doit apparaître pendant 1 à
3 secondes quand on arrive sur la page d'accueil, et couvrir l'intégralité de l'écran, **Le design de ce loader n’est pas défini,tant qu’elle est cohérente avec la charte graphique du site.*

Pages de menu :

- [x] - À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps.

- [x] - Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus.  
Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de la droite vers la gauche.  
Pour cette première version, l’effet peut apparaître au survol sur desktop au lieu du clic.  
Si l’intitulé du plat est trop long, il devra être rogné avec
des points de suspension.

Clonez le projet Ohmyfood!
```terminal
git clone "https://github.com/Anthony-landry/Projet-3-OhmyFood.git"
```
Installez les dépendances
```terminal
npm install
```

Sur votre IDE (vscode etc)

Lancer le Watch via Sass 
```terminal
npm run sass 
```
Lancer préfix*
```terminal
npm run préfix 
```

**prefix : postcss / autoprefixer /cssnano*

PostCSS :  est un outil qui va permettre de transformer le CSS à travers différents plugins.

autoprefixer : ajoute automatiquement des préfixes dans votre CSS -webkit- et -moz-.

cssnano : minimise votre CSS et optimise le code pour avoir le moins de code livré en production.
