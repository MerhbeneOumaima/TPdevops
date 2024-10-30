# TPdevops
Par�e 1 : Prépara�on de l'environnement Git
4. Comment vérifier la configura�on actuelle de Git sur votre machine, notamment le nom
d’u�lisateur et l’adresse e-mail ?:git config --list
5. Comment modifier votre adresse e-mail si vous l'avez mal configurée lors de l'installa�on
de Git ?:git config --global user.email votre@email.com
Par�e 2: Créa�on d'un nouveau projet
6. Si vous avez oublié de créer un fichier README.md lors de l'ini�alisa�on du projet,
comment pouvez-vous l'ajouter après coup et commiter les changements ?:
touch README.md  
echo "# Mon Projet" > README.md  
git add README.md  
git commit -m "Ajout du fichier README.md"  
7. Comment définir un dépôt distant si vous n'en avez pas configuré un lors de la créa�on
du projet ?:
git remote add origin git@github.com:votre-nom-utilisateur/mon-projet.git
git push -u origin main  
Par�e 3 : Concepts de base de Git
3. Comment annuler les modifica�ons locales d'un fichier avant de les ajouter à l'index ?: git checkout -- nom_du_fichier
4. Comment visualiser les fichiers qui sont prêts à être commités dans Git (staging) ?:git status
Par�e 4 : Collaborer sur Git
4. Comment suivre (track) un dépôt distant et récupérer toutes les branches de ce dépôt ?:git fetch --all
5. Comment supprimer une branche locale après l'avoir fusionnée dans master ?:git branch -d ma-fonctionnalite

