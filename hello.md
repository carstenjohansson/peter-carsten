#Gör följande


**Skapa en katalog (I detta fall gislaved-test)**
md gislaved-test


**Gå in i katalogen**
cd gislaved-test


**initiera repo**
git init

**Skapa en filen exempel i notepad**
notepad hello.md

**Lägg till filen i repo**
git add hello.md

**Commit med en kommentar**
git commit -m "Hej hej detta är ett test"

**Skapa en repo på github.com**


**koppla den lokala repo till github, behöver inte ha samma namn**
git remote add origin http://github.com/carstenjohansson/gislaved-test.git

**Kör sedan en push för att lägga upp filerna**
git push origin main/master


##Använd följande för att få ner filerna om du inte har orginal repo


**Clona ner filen**
git clone http://github.com/carstenjohansson/gislaved-test.git lokalakatalogen

**Gå in i katalogen lokalakatalogen för att redigera eller lägga till filer**
cd lokalakatalogen

**Kör sedan git add och commit för att lägga den i den lokala repo**

**kör sedan push origin main/master för att lägga upp filerna igen**

##Har du orginal repo så kan du använda pull

**git pull origin main/master