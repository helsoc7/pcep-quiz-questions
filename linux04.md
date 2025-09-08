# Textverarbeitung und Pipes - 40 Quiz-Fragen

# Frage 1
Was macht der cat-Befehl?
- [ ] Löscht Dateien
- [x] Zeigt Dateiinhalt an und verknüpft Dateien
- [ ] Kopiert Dateien
- [ ] Erstellt Verzeichnisse

# Frage 2
Was ist der Unterschied zwischen less und more?
- [ ] Kein Unterschied
- [x] less kann rückwärts navigieren, more nicht
- [ ] more ist moderner
- [ ] less zeigt nur Textdateien

# Frage 3
Wie beendet man less?
- [ ] Esc
- [ ] Ctrl+C
- [x] q
- [ ] exit

# Frage 4
Was macht head -20 datei.txt?
- [ ] Zeigt die letzten 20 Zeilen
- [x] Zeigt die ersten 20 Zeilen
- [ ] Löscht die ersten 20 Zeilen
- [ ] Kopiert die ersten 20 Zeilen

# Frage 5
Was macht tail -f log.txt?
- [ ] Zeigt die letzten Zeilen einmalig
- [ ] Löscht die letzten Zeilen
- [x] Zeigt die letzten Zeilen und folgt neuen Einträgen live
- [ ] Kopiert die Datei

# Frage 6
Welche grep-Option ignoriert Groß-/Kleinschreibung?
- [ ] grep -n
- [x] grep -i
- [ ] grep -v
- [ ] grep -c

# Frage 7
Was macht grep -v "pattern" datei.txt?
- [ ] Zeigt nur Zeilen mit "pattern"
- [x] Zeigt alle Zeilen außer denen mit "pattern"
- [ ] Zählt Zeilen mit "pattern"
- [ ] Löscht Zeilen mit "pattern"

# Frage 8
Was macht grep -n?
- [ ] Ignoriert Groß-/Kleinschreibung
- [x] Zeigt Zeilennummern an
- [ ] Zählt Treffer
- [ ] Invertiert die Suche

# Frage 9
Was ist eine Pipe (|)?
- [ ] Ein Kommentar
- [x] Verbindet Ausgabe eines Befehls mit Eingabe des nächsten
- [ ] Ein Löschen-Operator
- [ ] Ein Kopierbefehle

# Frage 10
Was macht ls -la | head -5?
- [ ] Listet 5 Dateien auf
- [x] Listet alle Dateien und zeigt dann die ersten 5 Zeilen der Ausgabe
- [ ] Löscht die ersten 5 Dateien
- [ ] Kopiert 5 Dateien

# Frage 11
Was macht sort datei.txt?
- [ ] Löscht die Datei
- [x] Sortiert die Zeilen alphabetisch
- [ ] Kopiert die Datei
- [ ] Zählt Zeilen

# Frage 12
Welche sort-Option sortiert numerisch?
- [ ] sort -a
- [x] sort -n
- [ ] sort -r
- [ ] sort -u

# Frage 13
Was macht uniq?
- [ ] Erstellt eindeutige Dateien
- [x] Entfernt aufeinanderfolgende doppelte Zeilen
- [ ] Zählt Zeilen
- [ ] Sortiert Zeilen

# Frage 14
Warum sollte man sort vor uniq verwenden?
- [ ] Das ist nicht nötig
- [ ] uniq funktioniert nur bei sortierten Daten richtig
- [ ] sort ist schneller
- [x] uniq braucht sortierte Eingabe für alle Duplikate

# Frage 15
Was macht wc -l datei.txt?
- [ ] Zählt Wörter
- [ ] Zählt Zeichen
- [x] Zählt Zeilen
- [ ] Zählt Dateien

# Frage 16
Was macht cut -d',' -f2 datei.csv?
- [ ] Löscht die 2. Spalte
- [x] Extrahiert die 2. Spalte (Komma-getrennt)
- [ ] Kopiert die 2. Zeile
- [ ] Sortiert nach 2. Spalte

# Frage 17
Was macht tr 'a-z' 'A-Z' < datei.txt?
- [x] Wandelt Kleinbuchstaben in Großbuchstaben um
- [ ] Löscht Buchstaben
- [ ] Sortiert Buchstaben
- [ ] Zählt Buchstaben

# Frage 18
Was ist der Unterschied zwischen > und >>?
- [ ] Kein Unterschied
- [x] > überschreibt, >> hängt an
- [ ] >> überschreibt, > hängt an
- [ ] > ist für Texte, >> für Binärdateien

# Frage 19
Was macht echo "Hello" > datei.txt?
- [ ] Zeigt "Hello" an
- [x] Schreibt "Hello" in datei.txt (überschreibt)
- [ ] Hängt "Hello" an datei.txt an
- [ ] Löscht datei.txt

# Frage 20
Was macht 2> in einer Umleitung?
- [ ] Leitet die Ausgabe um
- [x] Leitet Fehlermeldungen (stderr) um
- [ ] Leitet die Eingabe um
- [ ] Verdoppelt die Ausgabe

# Frage 21
Was ist /dev/null?
- [ ] Ein Fehler
- [x] Ein "Black Hole" für ungewollte Ausgaben
- [ ] Ein Nullzeichen
- [ ] Ein Laufwerk

# Frage 22
Was macht tee in einer Pipeline?
- [ ] Splittet die Pipeline
- [x] Speichert Zwischenergebnisse und leitet weiter
- [ ] Beendet die Pipeline
- [ ] Startet die Pipeline

# Frage 23
Was bedeutet ^ in einem grep-Pattern?
- [ ] Beliebiges Zeichen
- [x] Zeilenanfang
- [ ] Zeilenende
- [ ] Wiederholung

# Frage 24
Was bedeutet $ in einem grep-Pattern?
- [ ] Beliebiges Zeichen
- [ ] Zeilenanfang
- [x] Zeilenende
- [ ] Geldzeichen suchen

# Frage 25
Was macht grep "[0-9]" datei.txt?
- [x] Sucht nach Ziffern
- [ ] Sucht nach Buchstaben
- [ ] Sucht nach [0-9] literal
- [ ] Sucht nach 9 Zeichen

# Frage 26
Welche grep-Option aktiviert erweiterte Regex?
- [ ] grep -r
- [x] grep -E
- [ ] grep -v
- [ ] grep -i

# Frage 27
Was macht grep -r "pattern" /ordner/?
- [ ] Sucht nur in /ordner/
- [x] Sucht rekursiv in /ordner/ und Unterordnern
- [ ] Löscht das Pattern
- [ ] Kopiert den Ordner

# Frage 28
Was ist effizienter?
- [ ] cat große_datei.txt | grep "pattern"
- [x] grep "pattern" große_datei.txt
- [ ] Beide gleich
- [ ] Kommt auf die Datei an

# Frage 29
Wie debuggt man eine komplexe Pipeline am besten?
- [ ] Alles auf einmal ausführen
- [x] Step-by-Step jeden Teil einzeln testen
- [ ] Mit einem Debugger
- [ ] Gar nicht, Pipelines sind immer korrekt

# Frage 30
Was macht ps aux | grep firefox | wc -l?
- [ ] Zeigt Firefox-Prozesse
- [x] Zählt Firefox-Prozesse
- [ ] Startet Firefox
- [ ] Beendet Firefox

# Frage 31
Welches Pattern zeigt die häufigsten Werte?
- [x] sort | uniq -c | sort -nr
- [ ] uniq | sort -c
- [ ] sort -n | uniq
- [ ] grep -c | sort

# Frage 32
Was macht tail -f log.txt | grep --line-buffered "ERROR"?
- [ ] Sucht einmalig nach ERROR
- [x] Folgt dem Log und filtert ERROR-Zeilen live
- [ ] Löscht ERROR-Zeilen
- [ ] Zählt ERROR-Zeilen

# Frage 33
Was ist ein häufiger Fehler bei uniq?
- [x] Daten nicht vorher zu sortieren
- [ ] Falsche Optionen
- [ ] Zu große Dateien
- [ ] Falsche Berechtigung

# Frage 34
Was macht set -o pipefail?
- [ ] Deaktiviert Pipes
- [x] Pipeline scheitert wenn ein Befehl scheitert
- [ ] Aktiviert Pipes
- [ ] Zeigt Pipeline-Fehler

# Frage 35
Wie kann man IP-Adressen aus einem Log extrahieren?
- [x] grep -E "\b[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\b"
- [ ] grep "IP"
- [ ] cut -f1
- [ ] sort -n

# Frage 36
Was macht history | cut -d' ' -f2 | sort | uniq -c | sort -nr | head -10?
- [ ] Zeigt die Historie
- [x] Zeigt die 10 häufigsten Befehle
- [ ] Löscht die Historie
- [ ] Sortiert die Historie

# Frage 37
Wann sollte man tail -f verwenden?
- [ ] Bei statischen Dateien
- [x] Für Live-Monitoring von Log-Dateien
- [ ] Zum Bearbeiten von Dateien
- [ ] Zum Löschen von Dateien

# Frage 38
Was macht less im Vergleich zu cat bei großen Dateien?
- [ ] Ist langsamer
- [x] Lädt nicht die ganze Datei in den Speicher
- [ ] Zeigt mehr Details
- [ ] Ist schneller

# Frage 39
Wie sucht man in less nach Text?
- [ ] Ctrl+F
- [x] /suchtext
- [ ] grep
- [ ] find

# Frage 40
Was ist der Vorteil der Unix-Pipeline-Philosophie?
- [ ] Komplexe Programme schreiben
- [x] Einfache Tools kombinieren für komplexe Aufgaben
- [ ] Schnellere Computer
- [ ] Bessere Grafiken
