Apres avoir creer un new projet sur GitHub, les étapes dans le terminal pour creer un new commit sont
creer un dossier du meme nom que le projet github : mkdir machin
on initialise le depot : get init
on cree le dossier : touch dossier.truc
on envoie le fichier en staging area : git add dossier.truc
on verifie que le fichier est bien creer et qu'il est est commitable : git status
on le commit : git commit -m 'commentaire que lon veut'
on peut verifier que ca bien ete fait avec un git status des familles

Pour aller plus loin: c'est à dire pour envoyer le fichier sur GitHub
git remote add origin urlduprojetcreesurgithub
git push -u origin master pour premier depot
puis git push pour la suite des docs

Voilà, voilà...
