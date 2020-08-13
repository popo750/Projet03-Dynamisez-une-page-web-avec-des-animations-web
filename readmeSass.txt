Pour regarder les modifications de sass en temps réel,
go to Terminal windows,
go to le chemin accès du dossier en question 
se finissant par "sass_style"
ecrire : sass --help
Puis ecrire : sass Nom du fichier.scss Nom du fichier.css --watch
"sass XXX --watch " FAIT compiler automatiquement le ficher css
à chaque modification enregistrée du fichier .scss 

pour la visualisation du site internet sur gitPages,
Tout d'abord, convertir le fichier sass en fichier css
(exemple : sass accueil.scss accueil.css )

Ensuite sur gitbash,
git add en ecrivant les 3 fichers ET NON cpoier-coller
( exemple : git add sass_style/accueil.scss,
            git add sass_style/accueil.css.map
            git add sass_style/accueil.css )
puis : git commit -m "xxx"
et git push origin master