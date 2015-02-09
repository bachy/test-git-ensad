    Initialiser un répertoire git
cd 'chemin/vers/le/dossier/ou/sera/le/nouveau/répertoire'
mkdir 'nomdudossier'
cd 'nomdudossier'
git init
vim README.md
    > i
    > taper le texte
    > echap
    > :wq
(git status)
git add README.md
git commit -m "initial commit"
(git status)
git push
    Récupérer un repository existant
git clone 'url-du-repository'
    quand on travaille sur un repository Git et que l'on veut "pusher" les modifications:
cd 'chemin/vers/le/dossier'
git pull
(git status)
git add .    -- ou --    git add 'nomdufichier.ext'
git commit -m 'commentaire sur la modification'
(git status)
git push   -- ou --   git push origin master
