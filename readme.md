------------------ LOKAL REPOSITORY -------------
sudo = super user do ; admin rechte
git init heist erstelle lokales repository / projekt folder
sudo git init 

adde all changes die in den dateien gemacht worden sind in die staging area
git add .

zeige all dateien die veraendert worden sind
git status

speicher alle veranderungen in einem checkpoint
git commit -m "eine nachricht um zu verstehen was du gemacht hast"

zeige alle checkpoints 
git log 

----------------- REMOTE : WAS AUF GITHUB IST REPOSITORY -------------
ERSTELLE EINE REFERENZ ZU GITHUB REPOISTORY 
git remote add origin <link>

SENDE ALL VERANDERUNGEN ZUM REMOTE REPO 
git push origin master

