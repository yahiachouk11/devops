Comment vérifier la configuration actuelle de Git sur votre machine, notamment le nom d’utilisateur et l’adresse e-mail ? Utilisez la commande git config --list

*Comment modifier votre adresse e-mail si vous l'avez mal configurée lors de l'installation de Git ? Exécutez git config --global user.email "votre-nouvelle-email@example.com"

*Si vous avez oublié de créer un fichier README.md lors de l'initialisation du projet, comment pouvez-vous l'ajouter après coup et commiter les changements ? Créez le fichier avec touch README.md, ajoutez du contenu, puis utilisez git add README.md et git commit -m "Ajout du fichier README.md" pour le committer.

*Comment définir un dépôt distant si vous n'en avez pas configuré un lors de la création du projet ? Utilisez la commande git remote add origin <URL_DU_DEPOT> .

*Comment annuler les modifications locales d'un fichier avant de les ajouter à l'index ? Utilisez git checkout -- nom_du_fichier

*Comment visualiser les fichiers qui sont prêts à être commités dans Git (staging) ? Exécutez git status .

*Comment suivre (track) un dépôt distant et récupérer toutes les branches de ce dépôt ? Utilisez git fetch origin

*Comment supprimer une branche locale après l'avoir fusionnée dans master ? Exécutez git branch -d nom_de_la_branche

*Comment interrompre un rebase en cours si vous avez commis une erreur ? Utilisez git rebase --abort

*Comment lister les commits qui vont être rebasés avant de lancer un rebase ? Exécutez git log --oneline ma-fonctionnalite ^master

*Comment afficher la liste des branches actives et en cours de développement dans Git Flow ? Utilisez git flow feature list

*Comment annuler une branche de correctif (hotfix) avant de la finaliser si vous constatez une erreur ? Exécutez git flow hotfix cancel nom_du_correctif
