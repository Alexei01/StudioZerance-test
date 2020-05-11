# StudioZerance-test


Installation de l'application :
----------

Il suffit de télécharger le fichier .zip puis d'extraire le dossier contenant le projet. 
Il ne reste plus qu'à ouvrir le fichier 'index.html' avec un navigateur. 

Difficultés rencontrées :
----------

Le site est réparti en cinq sections. Le header, la bannière, le portfolio, le slider et le text infinite.
Le slider m'a posé problème, c'était la première fois que je devais en faire, j'ai rencontré plusieurs problèmes notamment pour bien "remplacer" l'image suivante avec celle qui la précède lors du défilement. ( Soit les deux images apparaissaient l'une sur l'autre, soit il n'y avait pas d'image). Je suis parti voir sur le web si d'autres personnes ont eu le même soucis. J'ai finalement changé toute la façon de procéder.

J'ai eu aussi quelques problèmes avec le header pour le rendre responsive, j'ai simplement choisi de ne pas l'afficher lorsque l'écran est trop petit. Le menu était soit trop petit et illisible, ou alors il prenait trop de place et le logo disparaissait ce qui déformait tout le site. 

Problèmes : 
----------

Voici les problèmes dont j'ai du mal à résoudre :

- Le soulignement du 'Shopify' sur la section bannière comme sur la maquette, j'ignore encore comment réussir à changer l'apparence du soulignement. 
J'ai pensé à remplacer le style de l'underline avec une classe, qu'on peut réutiliser sur plusieurs balises <div>. Le problème c'est que est difficilement retraçable, du moins j'ignore comment le faire.
  
- L'affichage du début du second slide, sur le premier slide. J'ai déja eu pas mal de soucis pour faire cette section "slider". Je suis parti du principe que je devais juste changer d'image à afficher sur la page lors du défilement, ainsi afficher deux images en "même temps" m'a beaucoup posé problème.
J'ai essayé d'opter de mettre les deux images dans une seule div, la deuxième étant rognée. J'ai eu beaucoup trop d'incohérences au niveau affichage donc j'ai vite abandonné cette voie. 

- La bandeau "text infinite" n'est pas fluide sur certains navigateurs. En effet j'ai utilisé une balise <marquee> qui est obsolète d'après ce que j'ai pu comprendre, ce qui le rend pas fluide pour tous. 
A mon avis, l'utilisation du CSS devrait être plus appropriée, notamment avec l'aide de @keyframes. J'ai fais pas mal d'essais, mais cela reste sans succès. Soit le texte ne défile pas, soit il n'apparaît tout simplement plus.
Je reste persuadé que pour cette partie, avec un peu plus d'entraînement et de connaissances en CSS, je pourrais y parvenir.
  
Temps par section : 
-------------

Voici le temps que j'ai consacré pour chaque section :
* Section header : 10 minutes
* Section bannière : 5 minutes
* Section portfolio : 30 minutes
* Section slider : 3 heures
* Section text infinite : 1 heure

* Rendre le site responsive + compléter les détails : 3 heures
 


