l'interface utilisateur: faire des maquettes (figma)

l´univers: effets visuels et sonores


# Scénario

Cette section présente le scénario de l’interactivité du projet.


<!-- Pour chaque étape/scène : une image avec du texte descriptif et une explication de la transition -->

<!--
Éléments du scénarimage
Séquence visuelle
Chaque scène ou séquence du scénarimage doit être clairement illustrée, montrant les éléments visuels qui seront projetés ou affichés. Cette séquence visuelle peut inclure des captures d'écran, des croquis ou des rendus 3D, en fonction des besoins du projet.

Points d'interaction
Le scénarimage dans un cadre interactif inclut les moments où l'utilisateur interagit avec l'installation. Ces points d’interaction doivent être représentés graphiquement pour indiquer comment et quand l’utilisateur influencera la progression du récit ou des effets visuels et sonores.

Évolution du récit
Comme pour le scénario narratif, le scénarimage doit montrer la progression de l’histoire ou de l’expérience au fil des interactions. Il permet de visualiser comment l’installation évolue en fonction des actions de l'utilisateur, avec des embranchements possibles selon ses choix.

Retour visuel et sensoriel
Le scénarimage doit inclure des annotations ou des visuels montrant les réponses visuelles, sonores ou tactiles à chaque interaction. Cela peut inclure des changements d’éclairage, des transitions vidéo, ou des effets sonores qui réagissent aux actions de l’utilisateur.
-->


## Scène #1 : Accueil et présentation de la date virtuelle 

![](https://placehold.co/600x400?text=Sc%C3%A9narimage)

**Ce que l’interacteur voit :**
- Le titre du jeu « L.a.r.p. »
- Le personnage de la date virtuelle (NPC) sur l’écran principal
- Un bouton « Play » permettant de démarrer l’expérience
- Les instructions expliquant le déroulement du jeu
- Les deux stations interactives (VR et jeu tactile)

**Ce que l’interacteur entend :**
- Une musique d’ambiance
- La voix du personnage (NARRATEUR FICTIF) qui accueille les joueurs et explique leur mission
- Des effets sonores lors des interactions avec les boutons

### Tableau des automatisations
| Déclenchement | Effet visuel | Effet sonore | Effet interactif |
| --- | --- | --- | --- |
| Démarrage de l’installation | Apparition du titre, du NPC et du bouton « Play » | Musique d’ambiance | Le bouton « Play » devient accessible |
|  Le bouton « Play » devient accessible   |  Animation du NPC et affichage des instructions   |  Voix du NPC  |  Les joueurs découvrent leur mission  |
|  Fin de la présentation   |  Apparition de la première question et du chronomètre   |  Son de début de partie  |  Activation des stations interactives et passage à la scène 2  |


### Tableau des actions
| Verbe d’action | Condition / contexte | Effet visuel | Effet sonore | Effet interactif |
| --- | --- | --- | --- | --- | 
| Entrer | Les joueurs entrent dans la salle | Aucun | Aucun | Accès à l’installation |
| Observer |  Les joueurs regardent l’écran principal   |  Aucun   |  Aucun  |  Découverte de l’interface   |
| Appuyer |  Un joueur appuie sur le bouton « Play »   |  Disparition du bouton et animation du NPC   |  Son de confirmation   |  Démarrage de l’expérience    |



## Scène #2 : Recherche d’indices et questionnaire

![](https://placehold.co/600x400?text=Sc%C3%A9narimage)

**Ce que l’interacteur voit :**
- Le personnage de la date virtuelle sur l’écran principal
- Les questions et les différents choix de réponses
- Un chronomètre indiquant le temps restant
- Un environnement 3D contenant des objets et des indices dans la réalité virtuelle
- Un mini-jeu et des énigmes sur l’écran tactile
- Les indices révélés après certaines interactions

**Ce que l’interacteur entend :**
- La voix du NPC qui pose les questions
- Une musique d’ambiance pendant la recherche
- Des effets sonores lors de la manipulation des objets
- Des sons de confirmation lors de la découverte d’un indice ou de la résolution d’une énigme
- Un son indiquant que le temps est presque écoulé


### Tableau des automatisations
| Déclenchement | Effet visuel | Effet sonore | Effet interactif |
| -- | -- | -- | -- |
|  Début de la scène   |  Affichage du chronomètre de deux minutes   |  Son de début de partie   |  Activation du questionnaire et des stations  |
|  Chaque seconde écoulée   |  Mise à jour du chronomètre   |  Aucun  |  Réduction du temps disponible  |
|  Énigme résolue   |  Apparition d’un indice   |  Son de réussite  |  Obtention d’une information sur le NPC   |
|  Réponse enregistrée  |  Apparition de la prochaine question   |  Voix du NPC et son de transition   |  Activation des nouveaux choix de réponses   |
|  Il reste 10 secondes  | Le chronomètre devient rouge  |  Son d’avertissement  |  Aucun  |
|  Fin du chronomètre  |  Disparition des questions   |  Son de fin de partie   |  Désactivation des interactions et passage à la scène 3   |

### Tableau des actions
| Verbe d’action | Condition / contexte | Effet visuel | Effet sonore | Effet interactif |
| --- | --- | --- | --- | --- |
| Enfiler | Un joueur enfile le casque VR | Aucun | Aucun | Accès à l’expérience VR |
| Regarder | Le joueur tourne la tête dans l’environnement VR | Changement du point de vue | Aucun | Observation de l’environnement |
| Se déplacer | Le joueur utilise les manettes VR | Déplacement dans l’environnement 3D | Son de déplacement | Exploration de l’environnement |
| Saisir | Le joueur sélectionne un objet interactif en VR | L’objet se déplace | Son de manipulation | Possibilité d’examiner l’objet |
| Examiner | Le joueur examine un objet contenant un indice | Apparition d’une information | Son de découverte | Obtention d’un indice |
| Appuyer | Le deuxième joueur touche un élément du mini-jeu tactile | Animation de l’élément | Son d’interaction | Sélection d’un élément |
| Glisser | Le joueur déplace un élément sur l’écran tactile | Déplacement de l’élément | Son de manipulation | Progression dans l’énigme |
| Communiquer | Les joueurs partagent leurs découvertes | Aucun | Voix des joueurs | Collaboration entre les joueurs |
| Appuyer | Un joueur sélectionne une réponse sur l’écran principal | Mise en évidence de la réponse | Son de confirmation | Enregistrement de la réponse et mise à jour du score de compatibilité |



## Scène #3 : Résultat de compatibilité

![](https://placehold.co/600x400?text=Sc%C3%A9narimage)

**Ce que l’interacteur voit :**
- Le personnage de la date virtuelle sur l’écran principal
- Une animation révélant le pourcentage de compatibilité
- Le résultat final des joueurs
- Une réaction du NPC qui varie selon le résultat obtenu
- Un bouton « Rejouer »

**Ce que l’interacteur entend :**
- Une musique de fin
- Un effet sonore lors de l’apparition du résultat
- La voix du NPC qui réagit au pourcentage de compatibilité obtenu

### Tableau des automatisations
| Déclenchement | Effet visuel | Effet sonore | Effet interactif |
| --- | --- | --- | --- |
| Début de la scène | Transition vers l’écran des résultats | Son de transition | Calcul du pourcentage de compatibilité |
| Fin du calcul | Animation du pourcentage de compatibilité | Son de révélation | Affichage du résultat final |
| Compatibilité élevée | Animation joyeuse du NPC | Réaction positive du NPC | Aucun |
| Compatibilité moyenne | Animation neutre du NPC | Réaction mitigée du NPC | Aucun |
| Compatibilité faible | Animation déçue du NPC | Réaction négative du NPC | Aucun |
| Fin de la réaction du NPC | Apparition du bouton « Rejouer » | Aucun | Activation du bouton « Rejouer » |

### Tableau des actions
| Verbe d’action | Condition / contexte | Effet visuel | Effet sonore | Effet interactif |
| --- | --- | --- | --- | --- |
| Retirer | Le joueur retire son casque VR | Aucun | Aucun | Fin de son utilisation de la station VR |
| Observer | Les joueurs regardent leur résultat | Aucun | Aucun | Découverte de leur compatibilité |
| Appuyer | Un joueur appuie sur le bouton « Rejouer » | Transition vers l’écran d’accueil | Son de confirmation | Réinitialisation du jeu et retour à la scène 1 |
| Quitter | Les joueurs quittent l’installation | Aucun | Aucun | Fin de leur expérience |
