# Suchen und Finden - 40 Quiz-Fragen

# Frage 1
Was macht der which-Befehl?
- [ ] Sucht nach Dateien
- [x] Zeigt wo sich ein Programm im PATH befindet
- [ ] Löscht Programme
- [ ] Installiert Programme

# Frage 2
Was ist der Unterschied zwischen which und whereis?
- [ ] Kein Unterschied
- [x] whereis zeigt auch Manpages und Source-Code-Pfade
- [ ] which ist schneller
- [ ] whereis funktioniert nur bei System-Befehlen

# Frage 3
Was macht type im Vergleich zu which?
- [ ] Ist identisch mit which
- [x] Unterscheidet zwischen Aliases, Builtins und externen Programmen
- [ ] Ist langsamer
- [ ] Funktioniert nur bei Bash

# Frage 4
Warum ist locate so schnell?
- [ ] Es ist ein neues Programm
- [x] Es arbeitet mit einem Index statt Live-Suche
- [ ] Es sucht nur in wichtigen Verzeichnissen
- [ ] Es verwendet spezielle Hardware

# Frage 5
Wie aktualisiert man den locate-Index?
- [ ] locate --update
- [x] sudo updatedb
- [ ] locate -refresh
- [ ] sudo locate --index

# Frage 6
Was ist ein Nachteil von locate?
- [ ] Ist zu langsam
- [ ] Findet nur Programme
- [x] Index kann veraltet sein
- [ ] Funktioniert nicht bei großen Dateien

# Frage 7
Was macht find . -name "*.txt"?
- [ ] Erstellt .txt-Dateien
- [ ] Löscht alle .txt-Dateien
- [x] Sucht alle .txt-Dateien im aktuellen Verzeichnis
- [ ] Kopiert .txt-Dateien

# Frage 8
Warum sollte man Wildcards in find in Anführungszeichen setzen?
- [ ] Das ist nicht nötig
- [x] Um Shell-Expansion zu vermeiden
- [ ] Für bessere Performance
- [ ] Nur bei großen Dateien

# Frage 9
Was macht find . -type f?
- [ ] Sucht nach Dateien mit Namen "f"
- [x] Sucht nur nach normalen Dateien (nicht Verzeichnisse)
- [ ] Sucht nach großen Dateien
- [ ] Formatiert Dateien

# Frage 10
Was macht find . -type d?
- [x] Sucht nach Verzeichnissen
- [ ] Löscht Verzeichnisse
- [ ] Sucht nach Dateien mit "d" im Namen
- [ ] Zeigt Datum der Dateien

# Frage 11
Was bedeutet find . -size +100M?
- [ ] Dateien kleiner als 100 MB
- [x] Dateien größer als 100 MB
- [ ] Genau 100 MB große Dateien
- [ ] Dateien mit 100 Zeichen Namen

# Frage 12
Was bedeutet find . -mtime -7?
- [ ] Dateien älter als 7 Tage
- [x] Dateien neuer als 7 Tage
- [ ] Dateien mit Namen "7"
- [ ] Dateien um 7 Uhr erstellt

# Frage 13
Was macht find . -mtime +30?
- [ ] Dateien neuer als 30 Tage
- [x] Dateien älter als 30 Tage
- [ ] 30 große Dateien finden
- [ ] Dateien am 30. des Monats

# Frage 14
Was ist die Funktion von {} in find -exec?
- [ ] Erstellt geschweifte Klammern
- [x] Platzhalter für die gefundene Datei
- [ ] Startet einen neuen Prozess
- [ ] Ist ein Syntaxfehler

# Frage 15
Wie beendet man eine find -exec Aktion?
- [ ] Mit ;
- [x] Mit \;
- [ ] Mit }
- [ ] Mit Ende

# Frage 16
Was macht find . -name "*.tmp" -exec rm {} \;?
- [ ] Erstellt .tmp-Dateien
- [x] Löscht alle .tmp-Dateien
- [ ] Zeigt .tmp-Dateien an
- [ ] Kopiert .tmp-Dateien

# Frage 17
Was ist der Unterschied zwischen -exec und -ok in find?
- [ ] Kein Unterschied
- [x] -ok fragt vor jeder Aktion nach Bestätigung
- [ ] -exec ist schneller
- [ ] -ok funktioniert nur bei Dateien

# Frage 18
Was macht find . -name "*.txt" -o -name "*.md"?
- [ ] Sucht .txt UND .md Dateien
- [x] Sucht .txt ODER .md Dateien
- [ ] Sucht weder .txt noch .md Dateien
- [ ] Gibt einen Fehler aus

# Frage 19
Was bedeutet ! in find . ! -name "*.tmp"?
- [ ] Sucht nur .tmp-Dateien
- [x] Sucht alle Dateien außer .tmp-Dateien
- [ ] Macht Dateien ausführbar
- [ ] Ist ein Syntaxfehler

# Frage 20
Wie kombiniert find standardmäßig mehrere Kriterien?
- [ ] Mit ODER
- [x] Mit AND
- [ ] Mit NOT
- [ ] Gar nicht

# Frage 21
Was macht find /etc -name "*.conf" 2>/dev/null?
- [ ] Erstellt .conf-Dateien
- [x] Sucht .conf-Dateien und unterdrückt Fehlermeldungen
- [ ] Löscht .conf-Dateien
- [ ] Kopiert .conf-Dateien nach /dev/null

# Frage 22
Was macht grep -r "pattern" /pfad/?
- [ ] Löscht "pattern" aus Dateien
- [x] Sucht rekursiv nach "pattern" in allen Dateien unter /pfad/
- [ ] Ersetzt "pattern" in Dateien
- [ ] Kopiert Dateien mit "pattern"

# Frage 23
Was ist effizienter für eine schnelle Dateinamen-Suche?
- [ ] find
- [x] locate
- [ ] grep
- [ ] ls

# Frage 24
Was ist besser für aktuelle, detaillierte Suche?
- [ ] locate
- [x] find
- [ ] which
- [ ] whereis

# Frage 25
Was macht find . -perm 777?
- [ ] Setzt Berechtigungen auf 777
- [x] Sucht Dateien mit exakt 777 Berechtigungen
- [ ] Löscht Dateien mit 777 Berechtigungen
- [ ] Zeigt alle Berechtigungen

# Frage 26
Was macht find / -perm -4000 -type f?
- [ ] Sucht große Dateien
- [x] Sucht SUID-Dateien (potentiell gefährlich)
- [ ] Sucht nach 4000 Dateien
- [ ] Löscht Systemdateien

# Frage 27
Was macht locate --statistics?
- [ ] Sucht nach Statistik-Dateien
- [x] Zeigt Informationen über den locate-Index
- [ ] Löscht den Index
- [ ] Erstellt Statistiken

# Frage 28
Wie kann man die Suchtiefe bei find begrenzen?
- [ ] find . -depth 3
- [x] find . -maxdepth 3
- [ ] find . -limit 3
- [ ] find . -levels 3

# Frage 29
Was macht apropos copy?
- [ ] Kopiert Dateien
- [x] Sucht nach Befehlen die mit "copy" zu tun haben
- [ ] Löscht Kopien
- [ ] Erstellt Backups

# Frage 30
Wo wird der locate-Index normalerweise gespeichert?
- [ ] /tmp/locate
- [x] /var/lib/locate/locatedb
- [ ] /etc/locate
- [ ] /usr/share/locate

# Frage 31
Was ist der Vorteil von find gegenüber locate?
- [ ] Ist schneller
- [x] Sucht immer aktuell (Live-Suche)
- [ ] Braucht weniger Speicher
- [ ] Ist einfacher zu verwenden

# Frage 32
Was macht find . -empty?
- [ ] Löscht leere Dateien
- [x] Sucht nach leeren Dateien und Verzeichnissen
- [ ] Erstellt leere Dateien
- [ ] Zeigt Dateigröße an

# Frage 33
Was passiert bei find . -name "*.txt" -exec cat {} \;?
- [ ] Löscht alle .txt-Dateien
- [x] Zeigt Inhalt aller .txt-Dateien an
- [ ] Kopiert .txt-Dateien
- [ ] Erstellt .txt-Dateien

# Frage 34
Wie findet man Dateien die größer als 1GB und älter als 30 Tage sind?
- [x] find . -size +1G -mtime +30
- [ ] find . -size 1GB -mtime 30
- [ ] find . -bigger 1G -older 30
- [ ] find . -large -old

# Frage 35
Was bedeutet locate -i pattern?
- [ ] Installiert pattern
- [x] Sucht case-insensitive nach pattern
- [ ] Ignoriert pattern
- [ ] Indexiert pattern

# Frage 36
Wie kann man find-Ergebnisse auf die ersten 10 begrenzen?
- [ ] find . -name "*.txt" -limit 10
- [x] find . -name "*.txt" | head -10
- [ ] find . -name "*.txt" -max 10
- [ ] find . -name "*.txt" -top 10

# Frage 37
Was ist ein guter Workflow für die Dateisuche?
- [ ] Immer nur find verwenden
- [x] Erst locate probieren, dann find für Details
- [ ] Nur locate verwenden
- [ ] Immer grep verwenden

# Frage 38
Was macht find . -newer reference_file?
- [ ] Erstellt neuere Dateien
- [x] Sucht Dateien die neuer als reference_file sind
- [ ] Löscht alte Dateien
- [ ] Vergleicht Dateien

# Frage 39
Wie sucht man nach Dateien mit bestimmten Wörtern im Dateinamen?
- [x] find . -name "*wort*"
- [ ] find . -word "wort"
- [ ] find . -contains "wort"
- [ ] find . -match "wort"

# Frage 40
Was ist wichtig beim Verwenden von find in Scripts?
- [ ] Immer sudo verwenden
- [x] Immer 2>/dev/null verwenden um Fehler zu unterdrücken
- [ ] Nur in /tmp suchen
- [ ] Immer -exec verwenden
