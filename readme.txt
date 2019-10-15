Déplacement dans le cmd au dossier correspondant,

git init 
git add readme.txt
git commit -m "Saving readme"
git branch branche1
git checkout branche1
git add code.txt (Avec hello world à l'intérieur)
git commit -m "First code hello world"
git add code.txt (Avec hello git)
git commit -m "Second code hello git"
(Suppression du fichier code.txt)
git commit -a -m "Suppr code"
git checkout master
git merge branche1
git add readme.txt
git commit -m "Saving final readme"
git remote add origin https://github.com/Frosteurz/partielcorentinlizy.git
git push -u origin master
git add readme.txt 
git commit -m "Saving final2 readme"

