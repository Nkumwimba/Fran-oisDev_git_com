# Documentation Du Tuto Github Avec Git 

## initialisation du depot

```bash
git init
git remote add origin SSH_REPO
```

## Rediger un commit (une bonne pratique)

````
Titre du commit

Description de notre commit avec des informations sur l'evolution du projet
L'enregistrement du commit est :wq 
 
````


# Envoyer un commit sur le dépot distant 

````
git add REAME.md 
git add .vscode

git commit -m " Titre du commit "
git push origin main 

````

# Creation d'un branch develop 

````branch 

git checkout -b Nom_De_La_Branch
````