# Documentation with  Github and git


## to show hidden file 
```bash
Get_ChildItem
``` 
## verification
```bash
git status
git log
git show
```

## return back
```bash
git restore --staged filename or .
```

## configure my Git user information
```bash
git config --global user.email "gashimwea@gmail"
git config --global user.name "Gacadeau"
``` 

## Initialisation  du depot
```bash
git init
git remote add origin SSH_REPO
``` 

## Rediger un commit(bonne pratique)

```bash
Title du commit

Description de notre commit avec des informations sur l'evolution du projet
```
## Envoyer un commit sur un depot distant

```bash
git add .
git commit -m "Titre du commit"
git push origin master
```

## Creation d'une branche

```bash
git checkout -b NOM_BRANCHE
```