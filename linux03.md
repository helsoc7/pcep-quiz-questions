# Dateien und Verzeichnisse verwalten - 40 Quiz-Fragen

# Frage 1
Was macht der touch-Befehl?
- [ ] Löscht eine Datei
- [x] Erstellt eine leere Datei oder aktualisiert Zeitstempel
- [ ] Kopiert eine Datei
- [ ] Zeigt Dateiinhalt an

# Frage 2
Wie erstellt man mehrere Dateien mit einem touch-Befehl?
- [ ] touch datei1; touch datei2
- [x] touch datei1 datei2 datei3
- [ ] touch datei1 && datei2
- [ ] touch (datei1, datei2)

# Frage 3
Wie erstellt man eine Datei mit Leerzeichen im Namen?
- [ ] touch datei mit leerzeichen.txt
- [ ] touch "datei mit leerzeichen.txt"
- [ ] touch datei\ mit\ leerzeichen.txt
- [x] Sowohl b) als auch c)

# Frage 4
Was macht mkdir -p?
- [ ] Erstellt nur leere Verzeichnisse
- [ ] Erstellt Verzeichnisse mit besonderen Rechten
- [x] Erstellt verschachtelte Verzeichnisse und fehlende Eltern-Verzeichnisse
- [ ] Löscht Verzeichnisse

# Frage 5
Welcher Befehl erstellt die Struktur a/b/c/d in einem Schritt?
- [ ] mkdir a b c d
- [ ] mkdir a/b/c/d
- [x] mkdir -p a/b/c/d
- [ ] mkdir -r a/b/c/d

# Frage 6
Was ist der Unterschied zwischen cp und mv?
- [ ] Kein Unterschied
- [x] cp kopiert, mv verschiebt/benennt um
- [ ] mv ist schneller
- [ ] cp funktioniert nur mit Dateien

# Frage 7
Wie kopiert man ein Verzeichnis rekursiv?
- [ ] cp verzeichnis ziel
- [x] cp -r verzeichnis ziel
- [ ] cp -d verzeichnis ziel
- [ ] cp * ziel

# Frage 8
Was macht cp -i?
- [ ] Kopiert schneller
- [x] Kopiert interaktiv und fragt bei Überschreibung
- [ ] Ignoriert Fehler
- [ ] Kopiert nur neue Dateien

# Frage 9
Was macht mv datei1.txt datei2.txt?
- [ ] Kopiert datei1.txt zu datei2.txt
- [ ] Löscht beide Dateien
- [x] Benennt datei1.txt zu datei2.txt um
- [ ] Verbindet beide Dateien

# Frage 10
Wie verschiebt man mehrere Dateien in einen Ordner?
- [ ] mv datei1 datei2 ordner/
- [ ] mv datei* ordner/
- [ ] mv *.txt ordner/
- [x] Alle Antworten sind korrekt

# Frage 11
Was ist der Unterschied zwischen rm und rmdir?
- [ ] Kein Unterschied
- [x] rm löscht Dateien, rmdir nur leere Verzeichnisse
- [ ] rmdir ist sicherer
- [ ] rm funktioniert nicht mit Verzeichnissen

# Frage 12
Wie löscht man ein Verzeichnis mit Inhalt?
- [ ] rm verzeichnis
- [x] rm -r verzeichnis
- [ ] rmdir -r verzeichnis
- [ ] del verzeichnis

# Frage 13
Was ist rm -rf?
- [x] Rekursiv und force (ohne Nachfrage)
- [ ] Read-only files
- [ ] Recent files
- [ ] Root files

# Frage 14
Welche rm-Option fragt vor jedem Löschen nach?
- [ ] rm -f
- [x] rm -i
- [ ] rm -r
- [ ] rm -v

# Frage 15
Was bedeutet das * Wildcard?
- [ ] Ein beliebiges Zeichen
- [x] Null oder mehr beliebige Zeichen
- [ ] Genau ein Zeichen
- [ ] Nur Buchstaben

# Frage 16
Was bedeutet das ? Wildcard?
- [ ] Null oder mehr Zeichen
- [x] Genau ein beliebiges Zeichen
- [ ] Nur Zahlen
- [ ] Fragezeichen im Dateinamen

# Frage 17
Was macht ls [abc].txt?
- [ ] Listet alle .txt Dateien
- [x] Listet a.txt, b.txt und c.txt
- [ ] Listet Dateien die [abc] im Namen haben
- [ ] Gibt einen Fehler

# Frage 18
Was macht ls [0-9].*?
- [ ] Listet alle Dateien
- [x] Listet Dateien die mit einer Ziffer beginnen
- [ ] Listet nur Zahlen-Dateien
- [ ] Listet Dateien von 0 bis 9

# Frage 19
Wie kann man alle .txt Dateien kopieren?
- [x] cp *.txt backup/
- [ ] cp .txt backup/
- [ ] cp all.txt backup/
- [ ] cp txt backup/

# Frage 20
Was sind .dotfiles?
- [ ] Dateien mit Punkten
- [x] Versteckte Dateien die mit . beginnen
- [ ] Kaputte Dateien
- [ ] Temporäre Dateien

# Frage 21
Wie zeigt man versteckte Dateien an?
- [x] ls -a
- [ ] ls -h
- [ ] ls --hidden
- [ ] ls -d

# Frage 22
Welche Datei ist eine typische Dotfile?
- [ ] config.txt
- [x] .bashrc
- [ ] hidden.txt
- [ ] system.conf

# Frage 23
Was sollte man vor rm *.txt machen?
- [ ] Backup erstellen
- [ ] ls *.txt ausführen
- [ ] Berechtigungen prüfen
- [x] Sowohl a) als auch b)

# Frage 24
Was ist die sicherste Art wichtige Dateien zu löschen?
- [ ] rm -f datei
- [x] rm -i datei
- [ ] rm -rf datei
- [ ] del datei

# Frage 25
Was macht cp -v?
- [x] Verbose - zeigt was kopiert wird
- [ ] Kopiert nur Videos
- [ ] Validiert Dateien
- [ ] Kopiert virtuelle Dateien

# Frage 26
Wie erstellt man ein Backup mit Zeitstempel?
- [ ] cp datei backup
- [x] cp datei datei_backup_$(date +%Y%m%d)
- [ ] cp datei datei.bak
- [ ] cp --timestamp datei backup

# Frage 27
Was ist cp -a?
- [ ] Kopiert nur Archive
- [x] Archive-Modus (erhält alle Attribute)
- [ ] Automatic copy
- [ ] Async copy

# Frage 28
Wie kopiert man alle Dateien außer .txt?
- [ ] cp !*.txt backup/
- [ ] cp [!t][!x][!t] backup/
- [x] Man kann das nicht mit cp
- [ ] cp --exclude="*.txt" * backup/

# Frage 29
Was passiert bei mv datei.txt ordner/ wenn ordner nicht existiert?
- [ ] Fehler
- [ ] Ordner wird erstellt
- [x] datei.txt wird zu "ordner" umbenannt
- [ ] Nichts

# Frage 30
Wie benennt man mehrere Dateien um?
- [ ] mv *.txt *.bak
- [x] Das geht nicht direkt mit mv
- [ ] mv --rename *.txt *.bak
- [ ] rename *.txt *.bak

# Frage 31
Was ist der gefährlichste rm-Befehl?
- [ ] rm -i
- [ ] rm -v
- [x] rm -rf /
- [ ] rm -r

# Frage 32
Wie kann man versehentlich gelöschte Dateien wiederherstellen?
- [ ] Ctrl+Z
- [ ] restore befehl
- [x] Aus Backup oder mit spezieller Recovery-Software
- [ ] Das geht immer automatisch

# Frage 33
Was macht touch bei einer existierenden Datei?
- [ ] Löscht sie
- [ ] Überschreibt sie
- [x] Aktualisiert nur den Zeitstempel
- [ ] Erstellt eine Kopie

# Frage 34
Wie erstellt man 10 Dateien test1.txt bis test10.txt?
- [ ] touch test{1..10}.txt
- [ ] touch test1.txt test2.txt ... test10.txt
- [ ] touch test*.txt
- [x] Sowohl a) als auch b)

# Frage 35
Was ist der Unterschied zwischen cp und rsync?
- [ ] Kein Unterschied
- [x] rsync kann Progress anzeigen und ist effizienter
- [ ] rsync funktioniert nur über Netzwerk
- [ ] cp ist moderner

# Frage 36
Wie kopiert man nur neue oder geänderte Dateien?
- [ ] cp -n quelle ziel
- [x] cp -u quelle ziel
- [ ] rsync -u quelle ziel
- [ ] cp --new quelle ziel

# Frage 37
Was macht mkdir -m 755 ordner?
- [x] Erstellt Ordner mit spezifischen Berechtigungen
- [ ] Erstellt 755 Ordner
- [ ] Erstellt Ordner mit Metadaten
- [ ] Gibt einen Fehler

# Frage 38
Wie findet man heraus, was ein Wildcard-Pattern matchen würde?
- [ ] test *
- [ ] ls pattern
- [x] echo pattern
- [ ] match pattern

# Frage 39
Was ist sicherer: rm oder trash?
- [ ] rm
- [x] trash (moves to trash instead of permanent delete)
- [ ] Beides gleich sicher
- [ ] Kommt auf die Situation an

# Frage 40
Welcher Befehl ist am effizientesten für große Dateien?
- [ ] cp
- [x] mv (wenn auf demselben Dateisystem)
- [ ] rsync
- [ ] dd
