
# GIT INFO


RawGit serves raw files directly from GitHub with proper Content-Type headers.

https://rawgit.com/



## Envoyer le dossier sur GIt Hub:

ls – ou je suis

pwd - chemin complet - ex : /var/www/html/site

cd Bureau

cd site

git init

git add .
(ou git add : choisir son modif / ou git add -i  > u  > 1-5 ( fichiers a choisir) > entre >q > entre)

git status

git commit -m “Commite SITE-BASE-1.2”


git remote add origin  https://github.com/NikEurope/SB.git   -  adresse  de dossier


git push -u origin master  / dev  / integration  etc ....


Cofirmer : Username for 'https://github.com': USER
Password for 'https://NikEurope@github.com': PASSE

git status


--------------------------------------------------------------------------------------------------


## GIT EN PLUS :

### Book :  https://git-scm.com/book/fr/v2


git clone https://github.com/.../nomProjet.git    - Importer un dossier depuis github

git pull  - récupérer les modifications

git checkout master - passer sur la branche de master

git checkout dev - passer sur la branche de dev

git branch - reg des branches

git log   - Afficher l'historique d'un dossier

git diff  - trouver les différences entre votre dernier commit

git checkout testing - basculer sur une branche existante

git checkout .    - Si il y a des problèmes et il faut annuler les dernières modification - Supprime toutes les modifications en cours qui ne sont pas dans le staging

git checkout -- <fichier>..." - pour annuler les modifications

git reset   -    # Équivalent à git reset --mixed HEAD, supprime toutes les modifications entre le dernier commit et la staging area

git reset --hard     -    # Supprime toutes les modifications par rapport au dernier commit

git tag -a v1.4 -m 'ma version 1.4'  - Créer des étiquettes annotées

git show v1.4 - visualiser les données de l’étiquette





--------------------------------------------------------------------------------------------------




