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

további terminal parancsok
git pull  origin origin main friss repo lekérdezése

git remote -v távoli  lekérdezés aktuális távoli repo lekérdezése
gta status #change, stage commit, 
állapotának lekérdezése.
cd #Change Directory
mkdir #Make Directory 
cd.. egy mappával lejjebb lép
cd <directory name> 
  rmdir <directoy name> #remove directory
  ls #list könyvtár listázása 
  git config global list  #globális beállítás listázása 
  
