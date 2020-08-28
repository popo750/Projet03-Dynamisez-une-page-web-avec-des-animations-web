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
( exemple : git add sass_style/pages/accueil.scss,
            git add sass_style/pages/accueil.css.map
            git add sass_style/pages/accueil.css )
puis : git commit -m "xxx"
et git push origin master


Pour git bash, 
pour écrire plus vite les fichiers qui sont en rouge,
après avoir écrit git add,
d'après mon mentor Kevin Hart :

exemple : git add sass_style/pages/accueil.scss,
          git add sass_style/pages/accueil.css.map
          git add sass_style/pages/accueil.css

ecrire : git add ... , 
taper d'abord "s" 
puis appuyer sur la touche "tab" ( symbole : --->| )
Et cela fera apparaitre le mot "sass_style/" tout en entier

Pareil pour "pages",
taper d'abord "p"
puis appuyer sur la touche "tab" ( symbole : --->| )
Et cela fera apparaitre le mot "pages/" tout en entier

Cela ajoutera les 3 fichiers "accueil" en vert 
(en ayant taper git status après avoir fait git add ... )
Ensuite comme d'habitude, git commit -m "votre message"
Puis git push origin master pour l'envoyer dans l'hébergeur "github"