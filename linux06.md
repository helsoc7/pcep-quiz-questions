# Frage 1
Was ist das Root-Verzeichnis in Linux?
- [ ] /root
- [ ] /home
- [x] /
- [ ] C:\

# Frage 2
Was bedeutet FHS?
- [ ] File Handling System
- [x] Filesystem Hierarchy Standard
- [ ] File Host Service
- [ ] Fast Hardware System

# Frage 3
Wo befinden sich die Benutzerverzeichnisse?
- [ ] /users
- [x] /home
- [ ] /people
- [ ] /accounts

# Frage 4
Was befindet sich in /etc?
- [ ] Programme
- [x] Konfigurationsdateien
- [ ] Benutzerdateien
- [ ] Temporäre Dateien

# Frage 5
Wo finden sich System-Logs?
- [ ] /logs
- [ ] /system/logs
- [x] /var/log
- [ ] /etc/logs

# Frage 6
Was bedeutet /usr?
- [ ] User files
- [x] Unix System Resources
- [ ] User system root
- [ ] Universal system repository

# Frage 7
Wo werden temporäre Dateien gespeichert?
- [ ] /temp
- [ ] /temporary
- [x] /tmp
- [ ] /var/temp

# Frage 8
Was bedeutet ~ im Dateipfad?
- [ ] Root-Verzeichnis
- [ ] Aktuelles Verzeichnis
- [x] Home-Verzeichnis des Benutzers
- [ ] Temporäres Verzeichnis

# Frage 9
Was bedeutet 'r' in Dateiberechtigungen?
- [ ] run
- [x] read
- [ ] root
- [ ] recursive

# Frage 10
Was bedeutet 'w' in Dateiberechtigungen?
- [x] write
- [ ] watch
- [ ] wait
- [ ] world

# Frage 11
Was bedeutet 'x' in Dateiberechtigungen?
- [ ] extra
- [ ] exclude
- [x] execute
- [ ] exit

# Frage 12
Wie sieht die Berechtigung rwxr-xr-x in Zahlen aus?
- [ ] 777
- [x] 755
- [ ] 644
- [ ] 666

# Frage 13
Wie sieht die Berechtigung rw-r--r-- in Zahlen aus?
- [ ] 755
- [ ] 777
- [x] 644
- [ ] 600

# Frage 14
Was macht chmod +x datei?
- [ ] Löscht die Datei
- [x] Macht die Datei ausführbar
- [ ] Kopiert die Datei
- [ ] Versteckt die Datei

# Frage 15
Was macht chmod 600 datei.txt?
- [x] Nur Eigentümer kann lesen und schreiben
- [ ] Alle können lesen und schreiben
- [ ] Nur lesen für alle
- [ ] Alle Berechtigungen für alle

# Frage 16
Welcher Befehl ändert den Dateieigentümer?
- [ ] chmod
- [x] chown
- [ ] chgrp
- [ ] change

# Frage 17
Welcher Befehl ändert die Dateigruppe?
- [ ] chmod
- [ ] chown
- [x] chgrp
- [ ] group

# Frage 18
Was ist ein Hard Link?
- [ ] Eine Verknüpfung zu einer anderen Datei
- [x] Gleiche Datei mit einem anderen Namen
- [ ] Eine Kopie der Datei
- [ ] Ein symbolischer Link

# Frage 19
Wie erstellt man einen Symbolic Link?
- [ ] ln datei link
- [x] ln -s datei link
- [ ] link datei link
- [ ] symlink datei link

# Frage 20
Was passiert mit einem Hard Link, wenn die ursprüngliche Datei gelöscht wird?
- [x] Der Hard Link funktioniert noch
- [ ] Der Hard Link wird auch gelöscht
- [ ] Der Hard Link zeigt einen Fehler
- [ ] Der Hard Link wird zu einem Soft Link

# Frage 21
Was passiert mit einem Soft Link, wenn die ursprüngliche Datei gelöscht wird?
- [ ] Der Soft Link funktioniert noch
- [ ] Der Soft Link wird auch gelöscht
- [x] Der Soft Link wird "broken" (zeigt ins Leere)
- [ ] Der Soft Link wird zu einem Hard Link

# Frage 22
Wo befinden sich die meisten ausführbaren Programme?
- [ ] /programs
- [ ] /usr/bin
- [ ] /bin
- [x] Sowohl b) als auch c)

# Frage 23
Was ist /proc?
- [ ] Ein normales Verzeichnis
- [x] Ein virtuelles Dateisystem mit Prozess-Informationen
- [ ] Programme-Verzeichnis
- [ ] Protokoll-Verzeichnis

# Frage 24
Was zeigt cat /proc/cpuinfo?
- [ ] CPU-Temperatur
- [x] CPU-Informationen
- [ ] CPU-Geschwindigkeit
- [ ] CPU-Fehler

# Frage 25
Was ist ein Mount Point?
- [x] Ein Verzeichnis wo externe Dateisysteme eingehängt werden
- [ ] Ein Backup-Punkt
- [ ] Ein Netzwerk-Punkt
- [ ] Ein Sicherheits-Punkt

# Frage 26
Wo werden automatisch gemountete USB-Sticks normalerweise angezeigt?
- [ ] /usb
- [x] /media
- [ ] /mnt
- [ ] /devices

# Frage 27
Was ist /etc/fstab?
- [ ] Eine Backup-Datei
- [x] Filesystem Table - definiert permanente Mounts
- [ ] Eine Benutzer-Datei
- [ ] Eine Log-Datei

# Frage 28
Was bedeutet die Berechtigung 777?
- [ ] Nur Eigentümer alle Rechte
- [x] Alle haben alle Rechte (gefährlich!)
- [ ] Nur lesen für alle
- [ ] Keine Berechtigungen

# Frage 29
Bei Verzeichnissen bedeutet 'x':
- [ ] Das Verzeichnis löschen
- [x] In das Verzeichnis wechseln können
- [ ] Das Verzeichnis ausführen
- [ ] Das Verzeichnis verstecken

# Frage 30
Bei Verzeichnissen bedeutet 'w':
- [ ] Das Verzeichnis lesen
- [x] Dateien im Verzeichnis erstellen/löschen
- [ ] Das Verzeichnis schreiben
- [ ] Das Verzeichnis kopieren

# Frage 31
Was ist eine sichere Berechtigung für normale Dateien?
- [ ] 777
- [ ] 666
- [x] 644
- [ ] 755

# Frage 32
Was ist eine sichere Berechtigung für ausführbare Dateien?
- [ ] 644
- [x] 755
- [ ] 777
- [ ] 600

# Frage 33
Welche Berechtigung macht eine Datei nur für den Eigentümer zugänglich?
- [ ] 755
- [ ] 644
- [x] 600
- [ ] 700

# Frage 34
Was macht sudo vor einem Befehl?
- [ ] Macht den Befehl schneller
- [x] Führt den Befehl als root/Administrator aus
- [ ] Macht den Befehl sicherer
- [ ] Loggt den Befehl

# Frage 35
Wo befinden sich persönliche Konfigurationsdateien?
- [ ] /etc
- [x] Im Home-Verzeichnis als .dotfiles
- [ ] /config
- [ ] /settings

# Frage 36
Was ist .bashrc?
- [ ] Eine Backup-Datei
- [x] Persönliche Bash-Konfigurationsdatei
- [ ] Eine Systemdatei
- [ ] Eine temporäre Datei

# Frage 37
Warum sollte man niemals chmod 777 verwenden?
- [ ] Es ist zu langsam
- [x] Es gibt allen Benutzern alle Rechte (Sicherheitsrisiko)
- [ ] Es funktioniert nicht
- [ ] Es ist deprecated

# Frage 38
Was zeigt ls -la im Vergleich zu ls?
- [ ] Mehr Dateien
- [x] Versteckte Dateien und detaillierte Informationen
- [ ] Weniger Dateien
- [ ] Nur Verzeichnisse

# Frage 39
Welcher Befehl zeigt alle gemounteten Dateisysteme?
- [ ] ls
- [x] mount
- [ ] df
- [ ] disk

# Frage 40
Was ist der wichtigste Grundsatz für Dateiberechtigungen?
- [ ] Alle Berechtigungen geben
- [x] Minimal Privileges - nur nötige Berechtigungen geben
- [ ] Keine Berechtigungen geben
- [ ] Nur root-Berechtigungen verwenden
