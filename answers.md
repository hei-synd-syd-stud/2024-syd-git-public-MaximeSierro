# Answers of Maxime Sierro MaximeSierro

## Basics

### Task 1

Il contient le fichier.md qui est le fichier que l'on modifie de notre côté. Il y a aussi 2 dossier, "img" qui contiendra les sources des images que l'on mettra dans le fichier ainsi que ".git" qui stocke toutes les informations nécessaires pour gérer le projet et garder un historique de ses versions. Ce dossier est caché (il commence par un point, comme les autres fichiers cachés) et se trouve à la racine de chaque dépôt Git

### Task 2

Git status voit qu'il y a maintenant un fichier "readme.md" mais qu'il n'a pas été stage. 

git log --oneline nous donne le dernier commit qui a été fait c'est à dire "Initial commit". c'est le commit du repo avant les modifications faotes au point 1 et 2

### Task 3

On constate que cette fois ci, README.md à été stage afin d'est commit tandis que answer.md n'est toujours pas dans le stage

### Task 4

Cette fois-ci, README.md est à la fois en attente d'être commit  et en attente d'être stage. Car il y a eu un stage de sa création puis une modification qui n'a pas été stage.

### Task 5

* La  chaine de caractère "d3a6067" est le no. d'identifiant du commit

* Le HEAD est la position du dernier commit et main est là ou pointe HEAD lors du nouveau commit

* après les parenthèse on a le nom du commit, ici: "ADD: README file"

### Task 6

Lorsque je suis revenu sur le initial commit, mon dossier de projet est redevenu dans l'état qu'il avait au début du labo (sans readme et sans modifications). Lorsque je suis revenus au dernier commit toutes les modifications ont été remises.

## Gitgraph

### Task 7

* 1: develop est une branche différente de main

* 2: c'est le "hash" du commit, son id

* 3: message du merge qui dit que la branche "feature-auth" a été fusionnée sur la branche "develop"

* 4: auteur du commit

* 5: indique la version actuelle du main

* 6: merge de feature-auth into develop

* 7: chechout de feature-auth depuis main

* 8: merge de develop into main

* 9: checkout de la branche develop depuis main

* 10: initial commit, état du repository avant modif

![Gitgraph](img/gitgraph.svg)