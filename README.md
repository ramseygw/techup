# techup
git config --global user.name "ramseygw"
git config --global user.email gbamawilfried@gmail.com
git config --global color.diff auto
git config --global color.status auto
git config --global color.branch auto
git config --global core.editor notepad++
git config --global merge.tool vimdiff
git init
git remote add origin https://github.com/ramseygw/techup.git
cd ..
cd projetechup/
it init
git status
git add index.html style.css
git status
git commit -m "ajout fichiers html et css"
git remote add origin https://github.com/ramseygw/techup.git
git branch -M main
git push -u origin main
git status
git add index.html
git commit -m "ajout d'un sous titre h2"
git add index.html
git commit -m "ajout d'un sous titre h2"
git push origin main
git branch
git branch cagnotte
git branch
git checkout cagnotte
git branch
git commit -m "Réalisation de la partie cagnotte côté front end"
git status
git add index.html
git commit -m "Réalisation de la partie cagnotte côté front end"
git push origin main
git push origin cagnotte
git checkout main
git merge cagnotte
