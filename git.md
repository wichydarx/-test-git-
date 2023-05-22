# COURS GIT

## 1. Introduction

Git et Github permettent de créer des versions d'un projet. Cela permet de revenir à une version antérieure du projet si besoin.L'avanatge de Github est qu'il permet de travailler à plusieurs sur un même projet, de créer des branches pour travailler sur une fonctionnalité sans impacter le projet principal.


### GIT 

GIT est un `VCS` (Version Control System) qui permet de créer des versions d'un projet. Avec GIT, les versions de notre projet sont stockées dans un dossier caché nommé `.git`. Ce dossier contient l'historique des modifications apportées au projet.


### GITHUB

GITHUB est un service en ligne qui permet d'héberger des projets utilisant GIT. Donc grâce à GITHUB, on peut héberger nos projets en ligne afin de pouvoir y accéder depuis n'importe quel ordinateur.

## 2. Les commandes de base

### Dépot local

Pour initialiser git sur un projet, il faut ouvrir le projet dans le terminal en faisant : `cd chemin/vers/le/projet` => qui va pointer dans le dossier du projet. 

Ensuite, il faut faire `git init` pour initialiser git sur le projet.

Par défaut git ne va pas prendre en compte tous les fichiers du projet. 

Pour ajouter un fichier au suivi de git, il faut faire `git add nomDuFichier`. 

Pour ajouter tous les fichiers du projet, il faut faire `git add .` ou `git add -A`.

Pour vérifier l'état du projet, il faut faire `git status` qui va afficher les fichiers qui sont dans le suivi de git et ceux qui ne le sont pas.

# TODO 1: 
- Créer un fichier `about.html` et faites en sorte que ce fichier et le fichier `contact.html` soit pris en compte par git.