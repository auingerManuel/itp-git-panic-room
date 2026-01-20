# Panic Room


## Problem #1 - Tests sind rot

### Angabe:
Du kannst Unit-Tests auch auf Git nutzen und ausführen. Diese kannst du beispielsweise mit MAVEN ausführen. Nutzt dazu den passenden Befehl, und findet anschließend die Fehler im Code. Behebt diese, und versucht somit die Tests lauffähig zu machen. Ergänzt anschließend einen zweiten Test, welcher ebenfalls funktionsfähig sein soll! Dazu könnt ihr den Code nach Belieben auch erweitern/ergänzen.

Alle Änderungen sollen anschließend auch im Repo ersichtlich sein. Denkt an korrekte, aussagekräftige Commit-Messages! 

Befehl zum Testen mit Maven (Terminal): 
mvn test


### Ausführung

cmd: mvn test

Error: CalculatorTest.divide_works:14 » Arithmetic / by zero

Haben in der Datei Calculator.java die Division durch 0 entfernt und durch return a / b ersetzt.


## Problem #2 - schlechte Commit Message

### Angabe:
In der History gibt es mind. eine schlechte Commit Message.
Arbeitet euch durch die Commit-History und schaut, welche Message nicht sinnvoll ist. Notiert in eurem Markdown-File die fehlerhafte Commit-Message, und begründet, warum diese nicht gut ist. Schlagt Alternativen dazu vor. Auch dieses File soll am Ende im Repository zu finden sein!

### Ausführung

cmd: git log

Es gab ein paar Commits mit sinnloser Message z.B Commit:
commit 50da5b1caf09339b68ce5d4ace7368a7b99f013e - Update,
Grund: ist zu Ungenau ist ja logisch das sich bei einem Commit was Updatet es sei denn man redet von einem geplanten Update wo sich jeder auskennt

Oder commit f58dc085f86d5cf87fd448f94b294a1665db9fc9 - stuff

Grund: ist sogar noch schlimmer als Update ist extrem unprofessionel


## Problem #3 - Repository aufräumen

### Angabe:
Im Repository liegt eine Datei die dort nicht hingehört. Sie hat keinen weiteren Sinn für euer Programm. Findet sie, und entfernt sie!
Begründet in eurem MARKDOWN File, warum ihr diese Datei gewählt habt.


### Lösung:

Die Datei debug.log ist überflüssig sie hatte keinen Nutzen.

cmd: git rm debug.log

Die Datei wurde entfernt


## Problem #4 - Datei wiederherstellen


+ Anmerkung war mir nicht sicher ob sie die vorige Datei wieder haben wollten oder eine Andere die gelöscht wurde hab jtzt beides gemacht

### Angabe:
Hilfe - eine wichtige Datei wurde gelöscht!
Finde den Commit, in dem sie noch existierte und holt euch diese Datei zurück. Ergänze kurz deine Vorgehensweise in eurem Markdown-File.

Folgende Befehle können dir dabei (unter anderem) helfen. Hier gibt es mehrere Lösungswege:
+ git log 
+ git checkout
+ git status


### Lösung:

+ Variante 1
cmd: git checkout f58dc085f86d5cf87fd448f94b294a1665db9fc9 -- debug.log
cmd: git add debug.log

+ Variante 2
cmd: git checkout a8605e0c0717dda3a2644bf14d08a433e47c251d -- docs/usage.md

# Zusammenfassung

1. Team - allein arbeit

2. Probleme bei dem Panic Room - allgemein die Unerfahrung in Git Hub 

3. viel mehr am Projekt arbeiten :>

4. Im Grunde würden wahrscheinlich eher technische Probleme in unseren Jahresprojekt aufkommen. Hilfreich sind da gutes Zusammenarbeien und nichts überstürzen.
