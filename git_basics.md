# Aufgabe 1:
In Github ein "New Repository" erstellt.
Den Repository namen angegeben

# Aufgabe 2:
Unter meinen dokumentne  einen git repo ordner erstellt

CMD:
- cd "path\git repo"
- git clone "https token"


# Aufgabe 3:
Markdown Cheatsheet in den neuen repo Ordner kopiert

CMD:
- git add Markodwn_cheatsheet.md
- git commit -m "Initial commit" 


# Aufgabe 4
Ein .gitignore file im repo erstellt und mit folgendem Inhalt befüllt:

```
*.log 
GeheimeBankInformationen.txt
```
CMD:
- git add .gitignore
- git commit -m "Add gitignore"


# Aufgabe 5
ein neuer Ordner  "Git Init" erstellt

CMD:
- git remote set-url origin "https link"
  - ERROR meldung: error: no such remote "origin"
- git remote add origin "https link"
- git clone "https token"
  -  "warning: You appear to have cloned an empty repository."

Da wir den originalen Ordner noch nicht ins repo gepushd haben, ist auch noch nichts herab zu kopieren.
Falls wir das repo vorher pushen, haetten wir hier jetzt eine kopie der Dateien.

# Aufgabe 6

Git hilft ein Softwarprojekt zu strukturieren und in Arbeitspakete zu unterteilen,
welche an verschiedene Softwareentwickler verteilt werden koennen, um gleichzeitig an einem
Projekt zu arbeiten.

Im falle eines Feuers, muessen die Aenderungen vor dem push zuerst committed werden, damit die Aenderungen auch mitgepushd werden
