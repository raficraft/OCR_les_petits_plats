# Dynamisez une page web avec des animations CSS

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/f6047a13e411417090f25f5a60526957)](https://app.codacy.com/gh/raficraft/OCR_oh_my_food_p3?utm_source=github.com&utm_medium=referral&utm_content=raficraft/OCR_oh_my_food_p3&utm_campaign=Badge_Grade_Settings)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/eec9594d7ac54a16bd248cfae0047b70)](https://www.codacy.com/gh/raficraft/OCR_les_petits_plats/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=raficraft/OCR_les_petits_plats&amp;utm_campaign=Badge_Grade)

Intégration maquette HTML/CSS 
Dynamiser la page avec des animations CSS
Troisième projet du parcours développeur web d'OpenClassRooms.

## Objectif

Intégration et animation d'une maquette fournie au format PNG d'un site de commande de repas en ligne

![Lien](https://user.oc-static.com/upload/2020/08/24/15982605908418_Maquettes%20Ohmyfood.jpg).

## Éléments fourni par OpenClassRooms

-   Maquette au format Smartphone, largeur 375px.De la page index et de chaque restaurants
-   Vidéo d'exemple des animùations à réaliser
-   Logo aux fomats PNG et SVG

## Technologies

-   Le développement devra se faire en CSS, sans JavaScript.
-   Aucun framework ne devra être utilisé, en revanche l’utilisation de SASS serait un plus.
-   Aucun code CSS ne devra être appliqué via un attribut style dans une balise HTML.
-   Le code doit être versionné avec git et doit avoir un repo distant sur Github ou Gitlab
-   le site doit être hébergé sur GitPages.
-   Le site devra être compatible avec les dernières versions de Chrome et Firefox.

## Identité graphique

*Polices*
- Logo et titres : [Shrikland](https://fonts.google.com/specimen/Shrikhand?preview.text_type=custom)
- Texte[Roboto](https://fonts.google.com/specimen/Roboto?preview.text_type=custom&query=roboto)

*Couleurs*
-   Primaire : #9356DC(violet)
-   Secondaire: #FF79DA(rose)
-   Tertiare : #99E2D0(vert pastel)

## Compatibilité

La cible étant les personnes connectées et pressées, le site sera développé en utilisant
l’approche mobile-first. Pour cette raison, seules des maquettes mobiles seront réalisées.
Sur tablette et desktop, le site devra s’adapter, mais ces supports n’étant pas prioritaires,
leur mise en page est libre.
-   L’ensemble du site devra être responsive sur mobile, tablette et desktop.
-   Les pages devront passer la validation W3C en HTML et CSS sans erreur.
-   Le site doit être parfaitement compatible avec les dernières versions desktop de
Chrome et Firefox.

## Effets graphiques et animations

**Boutons**
-   Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir.
L’ombre portée devra également être plus visible.
-   À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un
bouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il devra se
remplir progressivement. Pour cette première version, l’effet peut être apparaître au
survol sur desktop au lieu du clic.

**Pages d'acceuil**

-   Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Sur
cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à
3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et
utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini,
toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte
graphique du site.

**Pages de menu**

-   À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger
décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe
“Entrée”, “Plat” et “Dessert”. Un exemple de l’effet attendu est fourni.

-   Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus.
Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de
la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol
sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec
des points de suspension. Un exemple de l’effet attendu est fourni.

## Notes sur le projet

-   Le site à été réalisé en utilisant VS code.
-   Le style du site à été réalisé en utilisant le préprocesseur SASS
-   Les styles, on été "découpé" en morceaux afin de faciliter le travail sur les différentes parties du site, puis recompilé par SASS. Voir le répertoire sass/libs/first
-   Des repères, comme ceux présent dans Photoshop m'on permis d'aligner correctement les éléments comme sur la maquette (Voir de le CSS body::after et body::before). Je pense d'ailleurs améliorer le concept avec JS afin d'obtenir un véritable outil de développement pour les dévelopeurs front-end.
-   Projet vraiment intéressant qui m'as permit de pratiquer les animations avec CSS et de comprendre à quelle moment utilisé les transitions ou les keyframes

## Liens d'ébergements

-   Projet Reservia réalisé par Raphaël Parodi et hébergé sur ![GitPages](https://raficraft.github.io/OCR_oh_my_food_p3/)




