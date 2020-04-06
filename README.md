# G4DTG

# Contribuer

J'ai codé cette page pour découvrir comment marchait l'indexation d'un site statique en Jekyll mais ne compte pas rentrer toutes les parties pédagogiques.  
Vous pouvez participer en me soumettant par mail (kraymer+g4dtg@gmail.com) des parties en renseignant l'url youtube, le nom de l'ouverture et les thèmes abordés. 

Pour les plus techos, des merge requests peuvent être ouvertes en créant des fichiers markdown dans `youtube/`.  
Un fichier décrivant une partie ressemble à ça :

~~~
---
layout: post
title: lefrigobruiteur vs Blitzstream
date: 05/04/2020
youtube: https://youtu.be/OaIsoKFMB7E?t=2353
ouverture: italienne
themes:
- "[Attaque au centre](https://youtu.be/OaIsoKFMB7E)"
- "[Fourchette de pion](https://youtu.be/OaIsoKFMB7E?t=2479)"
- "[Prise dame sur découverte par échec](https://youtu.be/OaIsoKFMB7E?t=2551)"
---

[Full game]({{ page.youtube }})  
{{ page.themes | join: " <br> " }}
~~~

