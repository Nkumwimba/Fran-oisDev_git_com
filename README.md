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

git commit -m " Titre du commentaire "
git push origin main 

````

# Creation d'un branch develop 

````branch 

git checkout -b Nom_De_La_Branch
````


# Explication du workflow de review 
```` 
pour les bonnes patrique etant que professionnelle on va intégrer la notion de revue de code
Pour ce la, on va créer une branche, pour faires de modifications, puis les envoyer sur le depot distant, puis en suite créer un pull request pour demander une revue de code. en fin d'augmenter les qualitées de tes codes en que Developpeur et pour qu'il est de recomandation en cas de bien si une fois vous travaillez en équipe

````