# Frage 1
Was ist der Hauptvorteil von Multi-User-Systemen?
- [ ] Sind schneller
- [x] Mehrere Benutzer können sicher das gleiche System verwenden
- [ ] Brauchen weniger Speicher
- [ ] Sind einfacher zu bedienen

# Frage 2
Welche UID-Bereiche werden normalerweise für System-Benutzer verwendet?
- [ ] 1000+
- [ ] 0-99
- [x] 0-999
- [ ] 500-1000

# Frage 3
Welche UID-Bereiche werden für normale Benutzer verwendet?
- [ ] 0-999
- [x] 1000+
- [ ] 1-100
- [ ] 500-999

# Frage 4
In welcher Datei werden Benutzerinformationen gespeichert?
- [ ] /etc/users
- [x] /etc/passwd
- [ ] /etc/accounts
- [ ] /etc/login

# Frage 5
In welcher Datei werden Gruppeninformationen gespeichert?
- [ ] /etc/groups
- [x] /etc/group
- [ ] /etc/groupinfo
- [ ] /etc/team

# Frage 6
Wo werden die Passwort-Hashes sicher gespeichert?
- [ ] /etc/passwd
- [ ] /etc/passwords
- [x] /etc/shadow
- [ ] /etc/secure

# Frage 7
Was bedeutet das "x" im zweiten Feld von /etc/passwd?
- [ ] Der Benutzer ist gesperrt
- [x] Passwort ist in /etc/shadow
- [ ] Kein Passwort gesetzt
- [ ] Externes Passwort-System

# Frage 8
Welcher Befehl erstellt einen neuen Benutzer?
- [ ] adduser
- [x] useradd
- [ ] newuser
- [ ] createuser

# Frage 9
Welche Option erstellt automatisch ein Home-Verzeichnis?
- [ ] useradd -h username
- [ ] useradd -d username
- [x] useradd -m username
- [ ] useradd -home username

# Frage 10
Wie setzt man die Shell für einen neuen Benutzer?
- [ ] useradd -shell /bin/bash username
- [x] useradd -s /bin/bash username
- [ ] useradd -sh /bin/bash username
- [ ] useradd --shell /bin/bash username

# Frage 11
Welcher Befehl ändert Benutzer-Eigenschaften?
- [ ] edituser
- [ ] changeuser
- [x] usermod
- [ ] moduser

# Frage 12
Wie fügt man einen Benutzer zu einer Gruppe hinzu, ohne ihn aus anderen Gruppen zu entfernen?
- [ ] usermod -G gruppe benutzer
- [x] usermod -a -G gruppe benutzer
- [ ] usermod -add gruppe benutzer
- [ ] usermod -append gruppe benutzer

# Frage 13
Was passiert ohne die -a Option bei usermod -G?
- [ ] Nichts
- [x] Der Benutzer wird aus allen anderen Gruppen entfernt
- [ ] Es gibt einen Fehler
- [ ] Alle Gruppen werden gelöscht

# Frage 14
Welcher Befehl löscht einen Benutzer?
- [ ] removeuser
- [ ] deleteuser
- [x] userdel
- [ ] deluser

# Frage 15
Welche Option löscht auch das Home-Verzeichnis?
- [ ] userdel -h username
- [x] userdel -r username
- [ ] userdel -d username
- [ ] userdel -remove username

# Frage 16
Welcher Befehl erstellt eine neue Gruppe?
- [ ] addgroup
- [ ] newgroup
- [x] groupadd
- [ ] creategroup

# Frage 17
Was ist der Unterschied zwischen primären und sekundären Gruppen?
- [ ] Kein Unterschied
- [x] Primäre Gruppe ist in /etc/passwd, sekundäre in /etc/group
- [ ] Sekundäre Gruppen haben mehr Rechte
- [ ] Primäre Gruppen sind für System-Benutzer

# Frage 18
Welcher Befehl zeigt alle Gruppen eines Benutzers?
- [x] groups username
- [ ] showgroups username
- [ ] listgroups username
- [ ] usergroups username

# Frage 19
Was zeigt der id-Befehl?
- [ ] Nur die UID
- [ ] Nur die GID
- [x] UID, GID und alle Gruppen
- [ ] Nur den Benutzernamen

# Frage 20
Welcher Befehl ändert das Passwort eines Benutzers?
- [ ] password
- [x] passwd
- [ ] setpass
- [ ] chpass

# Frage 21
Wie sperrt man ein Benutzer-Passwort?
- [x] passwd -l username
- [ ] passwd -lock username
- [ ] passwd -disable username
- [ ] passwd -block username

# Frage 22
Welcher Befehl zeigt erweiterte Passwort-Informationen?
- [ ] passwd -i
- [ ] passinfo
- [x] chage -l username
- [ ] userinfo

# Frage 23
Was ist /etc/skel?
- [ ] Backup-Verzeichnis
- [x] Template für neue Benutzer-Home-Verzeichnisse
- [ ] System-Konfiguration
- [ ] Temporäres Verzeichnis

# Frage 24
Wann wird /etc/skel verwendet?
- [ ] Bei jedem Login
- [x] Beim Erstellen neuer Benutzer mit -m Option
- [ ] Beim Löschen von Benutzern
- [ ] Bei Passwort-Änderungen

# Frage 25
Welcher Befehl zeigt alle angemeldeten Benutzer?
- [ ] users
- [x] who
- [ ] logged
- [ ] active

# Frage 26
Was macht der whoami-Befehl?
- [ ] Zeigt alle Benutzer
- [x] Zeigt den aktuellen Benutzernamen
- [ ] Zeigt die UID
- [ ] Zeigt die Gruppen

# Frage 27
Wie fügt man einen Benutzer mit gpasswd zu einer Gruppe hinzu?
- [x] gpasswd -a username groupname
- [ ] gpasswd -add username groupname
- [ ] gpasswd username groupname
- [ ] gpasswd -u username groupname

# Frage 28
Wie entfernt man einen Benutzer aus einer Gruppe mit gpasswd?
- [ ] gpasswd -r username groupname
- [x] gpasswd -d username groupname
- [ ] gpasswd -remove username groupname
- [ ] gpasswd -del username groupname

# Frage 29
Was macht chage -d 0 username?
- [ ] Löscht den Benutzer
- [x] Zwingt Passwort-Änderung beim nächsten Login
- [ ] Setzt das Passwort zurück
- [ ] Deaktiviert den Account

# Frage 30
Welche Datei können alle Benutzer lesen?
- [ ] /etc/shadow
- [x] /etc/passwd
- [ ] /etc/sudoers
- [ ] /etc/gshadow

# Frage 31
Welche Datei kann nur root lesen?
- [ ] /etc/passwd
- [ ] /etc/group
- [x] /etc/shadow
- [ ] /etc/hosts

# Frage 32
Was bedeutet die UID 0?
- [ ] System-Benutzer
- [x] Root (Superuser)
- [ ] Normaler Benutzer
- [ ] Gesperrter Benutzer

# Frage 33
Welcher Befehl zeigt die Login-Historie?
- [ ] history
- [x] last
- [ ] logins
- [ ] access

# Frage 34
Was ist eine sichere Praxis beim Löschen von Benutzern?
- [ ] Sofort löschen
- [x] Erst sperren, dann Backup, dann löschen
- [ ] Nur Home-Verzeichnis löschen
- [ ] Passwort auf "deleted" setzen

# Frage 35
Wie kann man Benutzer automatisch aus einer CSV-Datei erstellen?
- [ ] useradd -csv file.csv
- [ ] import-users file.csv
- [x] while-Schleife mit useradd
- [ ] batch-useradd file.csv

# Frage 36
Was sollte man vor dem Löschen eines Benutzers tun?
- [ ] Passwort ändern
- [x] Backup der Benutzerdateien erstellen
- [ ] Gruppe ändern
- [ ] Shell deaktivieren

# Frage 37
Welches Verzeichnis enthält normalerweise alle Benutzer-Home-Verzeichnisse?
- [ ] /users
- [x] /home
- [ ] /accounts
- [ ] /people

# Frage 38
Was ist ein typischer Gruppenname für Entwickler?
- [ ] coders
- [ ] programmers
- [ ] developers
- [x] Alle sind möglich

# Frage 39
Wie prüft man, ob ein Benutzer existiert?
- [ ] ls /home/username
- [ ] getent passwd username
- [ ] cat /etc/passwd | grep username
- [x] Sowohl b) als auch c)

# Frage 40
Was ist wichtig bei der Benutzer-Sicherheit?
- [ ] Starke Passwörter durchsetzen
- [ ] Regelmäßige Account-Audits
- [ ] Minimale Berechtigungen vergeben
- [x] Alle Antworten sind richtig
