# Récapitulatif des commandes git

## Gestion git en local

`git add .` permet d'ajouter tous les fichiers qui ont été modifié au prochain commit.

`git reset .` permet de retirer les fichier à la surveillance de git pour le prochain commit. 

`git commit -m "branche/nom_de_la_feature: message descriptif du commit"` Ajout d'un commit avec son message descriptif.

## Gestion de git en remote (GitHub, GitLab, BitBucket, etc)

Ajout du depot (repository) distant:

`git remote add nom_du_remote https://url_du_remote`

Par exemple:

`git remote add origin https://github.com/benoitsemifir/demo-git_idp_ibm`

Pour envoyer nos modif enrigistrés dans le repo *local*:

`git push nom_du_remote nom_de_la_branche_locale`

par exemple:

`git push origin main`

Il est possible de paramétrer la branhce pour toujour pousser au même endroit, ce qui vous permet de juste faire un push.

`git push --set-upstream origin main` ce qui permet de juste faire `git push` par la suite.
