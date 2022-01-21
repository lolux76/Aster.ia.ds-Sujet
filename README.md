<div align="center">
	<h1> Aster.ia.ds </h1>
</div>

<p align="center">@Wele oumar 🎙️
	Jeu-vidéo - Interface graphique - IA - Rendu 2D / 3D
</p>

Basé sur le jeu [Asteroids](https://fr.wikipedia.org/wiki/Asteroids) des années 80,
Aster.ia.ds est un remake de ce dernier mais avec des technologies plus récentes et vus à l'Université.

L'objectif final est de réaliser un jeu multijoueur, dans lequel des étudiants de l'Université pourrait aussi bien joué eux-même
ou faire joué une IA qu'ils auraient conçu. Le tout réalisé et mis à jour par des étudiants pour des étudiants.


## Pourquoi nous ? 🤔

 Un stage avec un cadre clair, mais avec la possibilité d'adadpté à tes gouts.
 Un projet avec une réel application derrière, et orienté jeux-vidéo.
 Qui met en application tes cours.
 Encadrer par des étudiants compétents, qui répondent vite, dans un cadre bien préparé.

## Technologies

 - c++
 - Qt
 - OpenGL / GLU / GLUT
 - git \*

D'autres technologies pourront être utilisées si elles sont correctement justifiées

\* : optionnel et possibilité d'avoirs de l'aide sur ces points, les autres sont fortement recommandé

## Méthodologie

Le stage sera deroulera avec une méthode agile dont la durée des sprint et leurs contenu varieront en fonction de l'avancement du projet. 

## Étapes

 - Création, préparation et maturation par [PC[i]](https://projetcohesion.info)
 - Dépos du projet auprès des enseignants qui gère la L3 à l'Université d'Angers
 - Développement initial par des étudiants en L3 dans le cadre de leur stage de fin d'année,il sera encadrer par l'association [PC[i]](https://projetcohesion.info) (8 semaines minimum)
 - Reprise du projet par PC[i] en interne pour rajouter des fonctionnalités manquantes et préparé le déploiement
 - Première pré-release reservé aux membres de PC[i] et aux étudiants ayant contribuer (aux environs de juillet 2022)
 - Déploiement de la première release (Première de date de sortie espéré aux environs de début aout 2022)
 
## Contenu attendu

  - Une interface graphique comportant :
    - Un menu :
      - Permet la saisie d'un :
        - pseudo 
        - mot de passe 
        - d'un skin (changement de couleur et/ou de la forme (sans changement autre que rendu visuel))
      - Permet le lancement du jeu
    - Le jeu :
      - Devra comporter les éléments suivants :
        - le vaisseau du joueur :
          - restera centrer sur l'écran
          - se dirigera vers le pointeur de la souris
          - tirera des projectiles avec un clic souris
        - les astéroïdes :
          - pourront êtres détruites par les joueurs
            - si grosse elles se divisent
            - si petite elles disparaissent
        - les adversaires :
          - les mêmes possibilités que le joueur
          - action choisi par un code arbitraire
        - des bordures de cartes
    - Une fenêtre de résultat
  - Le code :
    - Ré-utilisable ( commenté, indenté, propre, ... )
    - Sans erreurs ( warning et erreur de compilation, crash avec par exemple erreurs de segmentation ...)
    - Structuré ( plusieurs fichier séparé avec une logique clair )
  - Tout élément ambigüe ou absent de cette liste pourra être choisi par les étudiants, après confirmation par les encadrants

## Contenu suplémentaire


#### 🧠 Axe Intélligence artificiel :
*Si vous avez fait IPSI et/ou TDPy, cette partie peut vous intérréssé*

Les ennemis sont pour l'instant des scripts,
mais il serait intérressant d'implémenter les algo d'IA que vous avez pu apprendres durant votre cursus.

Et peut-être réalisé plusieurs IA avec plusieurs méthodes pour les comparés ou fw	aire différentes difficultés.
à vous de voir ce que vous pouvez et voullez faire.


#### 🎮 Axe Jeu Vidéo :
*Si vous avez fait SI et/ou DIGA, cette partie peut vous intérréssé*

 - Graphique :
 	Le jeu de base est demandé en 2D, mais s'il fonctionne en 2D pourquoi ne pas l'étendre en 3D ?
 	avec toutes les difficultés et gestion à adapté.


 - Résultat :
 	La fenêtre de résultat de base ne doit rendre qu'un classement des joueurs et si l'on a perdu ou gagner
 	mais pourquoi ne pas pousser plus loin l'interface et ajouter un graphique de l'évolution des scores de joueurs au fur et à mesures
 	ou tout autre donnée du jeu qui serait intérressantes


 - Options :
 	Un systèmes de configuration de paramètre tel que la qualité de rendu, sans éditer le code ou un fichier de configuration
 	directement une fois le jeu lancer pourrait être un énorme atout au jeu
   
   
## Une question ❓

N'hésite pas à envoyer un mail à contact@projetcohesion.info

Ou [à venir nous voir](https://projetcohesion.info/a-propos/#bureau) on est souvent dans le batiment H (H001/2/3/7)

*[IPSI]: Initiation à la Programmation de Systèmes Intelligents
*[TDPy]: Traitement de données en Python
*[SI]: Synthèse d’images
*[DIGA]:  Développement d’Interfaces Graphiques Avancées
