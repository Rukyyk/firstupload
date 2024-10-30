…or create a new repository on the command line
echo "# firstupload" >> README.md
git init   //Initialing git for the first time in a folder
git add .  //Adding all the file to git
git commit -m "first commit"   //Comming the added files
git branch -M main  //setting the branch to maain
git remote add origin https://github.com/Rukyyk/firstupload.git   //Connecting to the remotegit folder /repository url
git push -u origin main  //pushing the codes to the repository

===== AFTER SET UP (DURING UPDATE) =====
git add .
git commit -m "your commit message"   
git push -u origin main  
