# PratiquesGit

## Prérequis
### Installation de Git
Suivre les instructions : [Démarrage rapide - Installation de Git](https://git-scm.com/book/fr/v2/D%C3%A9marrage-rapide-Installation-de-Git).
### Création d’un compte GitHub
Se créer un compte sur le site.
Me donner vos comptes pour vous donner les accès.

### Exercices
Exercice 1 : Récupérer un dépôt

Instructions :

Il faut cloner ce dépot, pour l'avoir en local sur son pc.
- Récupérer l'URL de ce dépôt.
- Ouvrir un terminal et entrer la commande qui vous permet de récupérer le dépot 😉.

<details>
<summary>Solution mais attendez, rappelez vous </summary>
<br>

```sh  
git clone https://github.com/alopesmendes/PratiquesGit
```
</details>

Exercice 2 : Ajouter et committer un fichier

Instructions :

- Créer un nouveau fichier depuis votre machine local et renommer le avec votre nom et terminant par .md comme par exemple `ailton.md`.
- Ajouter `Hello world!`dans votre fichier.
- D'abord ajouter le fichier grâce à la commande adapté puis faites la commande `git status` pour voir l'état actuelle.
- Ensuite committer le fichier avec le message "Mon premier commit"

<details>
<summary>Solution, on est gentil</summary>
<br>
  
```sh  
git add <nom du ficier>
git status
git commit -m "Mon Premier commit"
```  
</details>  
  
Exercice 3 : Pousser les modifications vers le dépôt distant

Instructions :

- Faut envoyer vos modifications !

<details>
<summary>Solution, trop compliqué</summary>
<br>
  
```sh  
git push
```  
</details>  

Exercice 4 : Récuperer les modifications de tout le monde

Instructions :

- Il faut récuperer chacun des commit !
- Mettez à jour votre dépot local.

<details>
<summary>Solution, encore plus compliqué</summary>
<br>
  
```sh  
git pull
```  
</details>  











