#hello
…or create a new repository on the command line

echo "# Teszt1" >> README.md #fájl létrehozása az első sorba "# teszt" kerül
git init a git mappa inicializálása
git add README.md változtatásaok mentése
git commit -m "first commit" változtatásaok jóváhagyása
git branch -M main a fejlesztési ág átnevezése main-re 
git remote add origin https://github.com/gamerboy2011/Teszt1.git fejlesztési ág feltöltése első alkalommal.
git push -u origin main

…or push an existing repository from the command line

git remote add origin https://github.com/gamerboy2011/Teszt1.git
git branch -M main
git push -u origin main
