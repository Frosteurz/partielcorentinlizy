D�placement dans le cmd au dossier correspondant,

git init 
git add readme.txt
git commit -m "Saving readme"
git branch branche1
git checkout branche1
git add code.txt (Avec hello world � l'int�rieur)
git commit -m "First code hello world"
git add code.txt (Avec hello git)
git commit -m "Second code hello git"
(Suppression du fichier code.txt)
git commit -a -m "Suppr code"
git checkout master
git merge branche1
git add readme.txt
git commit -m "Saving final readme"
