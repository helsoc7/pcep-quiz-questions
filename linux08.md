# Frage 1
Was bedeutet sudo?
- [ ] Super User Do
- [x] Substitute User Do
- [ ] System User Do
- [ ] Switch User Do

# Frage 2
Was ist der Hauptvorteil von sudo gegenüber su?
- [ ] Ist schneller
- [x] Behält ursprüngliche Benutzer-Identität und loggt Aktivitäten
- [ ] Braucht weniger Speicher
- [ ] Funktioniert nur bei root

# Frage 3
Welcher Befehl sollte NIEMALS zur Bearbeitung von /etc/sudoers verwendet werden?
- [ ] visudo
- [ ] nano /etc/sudoers
- [ ] vim /etc/sudoers
- [x] Sowohl b) als auch c)

# Frage 4
Warum sollte man visudo verwenden?
- [ ] Ist schneller
- [x] Hat Syntax-Prüfung und File-Locking
- [ ] Sieht schöner aus
- [ ] Ist einfacher

# Frage 5
Wie lange ist eine sudo-Session standardmäßig gültig?
- [ ] 5 Minuten
- [ ] 10 Minuten
- [x] 15 Minuten
- [ ] 30 Minuten

# Frage 6
Welcher Befehl zeigt meine sudo-Berechtigungen an?
- [ ] sudo -s
- [x] sudo -l
- [ ] sudo -i
- [ ] sudo --list

# Frage 7
Was macht sudo -v?
- [ ] Zeigt sudo-Version
- [x] Erneuert sudo-Session (verlängert Timeout)
- [ ] Validiert sudoers-Datei
- [ ] Zeigt verfügbare Befehle

# Frage 8
Was bedeutet diese sudoers-Zeile: anna ALL=(root) /bin/systemctl?
- [ ] anna darf alle Befehle ausführen
- [x] anna darf nur systemctl als root ausführen
- [ ] anna darf systemctl als jeder Benutzer ausführen
- [ ] anna darf keine Befehle ausführen

# Frage 9
Was bedeutet NOPASSWD in sudoers?
- [ ] Benutzer hat kein Passwort
- [x] Benutzer muss kein Passwort für diese Befehle eingeben
- [ ] Passwort wird nicht geloggt
- [ ] Passwort wird automatisch generiert

# Frage 10
Wie fügt man einen Benutzer zur sudo-Gruppe hinzu?
- [ ] sudo adduser username sudo
- [ ] sudo usermod -a -G sudo username
- [ ] sudo gpasswd -a username sudo
- [x] Alle Antworten sind korrekt

# Frage 11
Was bedeutet % vor einem Gruppennamen in sudoers?
- [ ] Prozentzeichen ist ein Kommentar
- [x] Kennzeichnet eine Gruppe
- [ ] Bedeutet "alle Benutzer"
- [ ] Ist ein Syntax-Fehler

# Frage 12
Wo werden sudo-Aktivitäten in Ubuntu geloggt?
- [ ] /var/log/sudo.log
- [x] /var/log/auth.log
- [ ] /var/log/secure
- [ ] /var/log/admin.log

# Frage 13
Was macht sudo -k?
- [ ] Startet sudo-Session
- [x] Beendet sudo-Session
- [ ] Zeigt sudo-Konfiguration
- [ ] Installiert sudo

# Frage 14
Welcher Befehl startet einen systemd-Service?
- [ ] sudo service start servicename
- [x] sudo systemctl start servicename
- [ ] sudo start servicename
- [ ] sudo init start servicename

# Frage 15
Was macht systemctl enable servicename?
- [ ] Startet den Service
- [ ] Stoppt den Service
- [x] Konfiguriert Autostart beim Boot
- [ ] Löscht den Service

# Frage 16
Welcher Befehl zeigt den Status aller Services?
- [ ] systemctl list-all
- [ ] systemctl status
- [x] systemctl list-units --type=service
- [ ] systemctl show-services

# Frage 17
Was ist der Unterschied zwischen systemctl restart und systemctl reload?
- [ ] Kein Unterschied
- [x] restart stoppt und startet neu, reload lädt nur Konfiguration neu
- [ ] restart ist schneller
- [ ] reload funktioniert nur bei bestimmten Services

# Frage 18
Was macht sudo -i?
- [ ] Zeigt Informationen
- [x] Startet interaktive root-Shell
- [ ] Installiert sudo
- [ ] Initialisiert sudo

# Frage 19
Wie kann man sudoers-Syntax testen ohne zu speichern?
- [x] sudo visudo -c
- [ ] sudo test-sudoers
- [ ] sudo visudo --test
- [ ] sudo validate-sudoers

# Frage 20
Was bedeutet diese Zeile: Defaults timestamp_timeout=0?
- [ ] Kein Timeout
- [ ] Immer nach Passwort fragen
- [ ] 0 Minuten Timeout
- [x] Sowohl b) als auch c)

# Frage 21
Welche Gruppe hat in Ubuntu standardmäßig sudo-Rechte?
- [ ] admin
- [ ] wheel
- [x] sudo
- [ ] root

# Frage 22
Was macht sudo -u username command?
- [x] Führt command als username aus
- [ ] Ändert Benutzer zu username
- [ ] Löscht username
- [ ] Zeigt username-Infos

# Frage 23
Wie kann man Command-Aliases in sudoers definieren?
- [ ] Alias SERVICES = /bin/systemctl
- [x] Cmnd_Alias SERVICES = /bin/systemctl
- [ ] Command_Alias SERVICES = /bin/systemctl
- [ ] CMD_ALIAS SERVICES = /bin/systemctl

# Frage 24
Was ist ein Sicherheitsvorteil von sudo gegenüber Root-Login?
- [ ] Ist schneller
- [x] Alle Aktionen werden mit ursprünglicher Benutzer-Identität geloggt
- [ ] Braucht weniger Passwörter
- [ ] Funktioniert auch ohne Passwort

# Frage 25
Was passiert wenn man visudo mit Syntax-Fehlern speichern will?
- [ ] Datei wird trotzdem gespeichert
- [x] visudo fragt nach Bestätigung und bietet Optionen
- [ ] System stürzt ab
- [ ] visudo startet neu

# Frage 26
Wie prüft man ob ein Service läuft?
- [ ] systemctl status servicename
- [ ] systemctl is-active servicename
- [ ] systemctl running servicename
- [x] Sowohl a) als auch b)

# Frage 27
Was bedeutet env_reset in sudoers?
- [x] Resettet Umgebungsvariablen für Sicherheit
- [ ] Löscht alle Dateien
- [ ] Startet System neu
- [ ] Resettet sudo-Konfiguration

# Frage 28
Wie kann man sudo in Scripts verwenden ohne Passwort-Prompt?
- [ ] sudo -n (non-interactive)
- [ ] NOPASSWD in sudoers konfigurieren
- [ ] Vorher sudo -v ausführen
- [x] Alle Antworten sind möglich

# Frage 29
Was ist der Unterschied zwischen su und sudo -i?
- [ ] Kein Unterschied
- [x] su braucht Root-Passwort, sudo -i das eigene Passwort
- [ ] su ist sicherer
- [ ] sudo -i funktioniert nur bei root

# Frage 30
Wie kann man Service-Logs anzeigen?
- [x] sudo journalctl -u servicename
- [ ] sudo systemctl logs servicename
- [ ] sudo tail /var/log/servicename
- [ ] sudo log servicename

# Frage 31
Was macht systemctl daemon-reload?
- [ ] Startet alle Services neu
- [x] Lädt systemd-Konfiguration neu
- [ ] Löscht alle Services
- [ ] Zeigt Service-Status

# Frage 32
Welche Option zeigt nur fehlgeschlagene Services?
- [x] systemctl --failed
- [ ] systemctl status --failed
- [ ] systemctl list-units --failed
- [ ] systemctl show-failed

# Frage 33
Was ist eine sichere Praxis für sudo-Konfiguration?
- [ ] Alle Befehle für alle erlauben
- [x] Minimale Rechte nach Bedarf vergeben
- [ ] Nur root-Zugang verwenden
- [ ] sudo komplett deaktivieren

# Frage 34
Wie kann man sudo-Logs nach Benutzern filtern?
- [x] grep username /var/log/auth.log
- [ ] sudo log username
- [ ] systemctl show sudo username
- [ ] journalctl user=username

# Frage 35
Was passiert bei sudo ohne Argumente?
- [ ] Startet root-Shell
- [ ] Zeigt Hilfe
- [x] Gibt Fehler aus
- [ ] Zeigt sudo-Status

# Frage 36
Welcher Befehl ist äquivalent zu sudo systemctl?
- [ ] su -c systemctl
- [ ] sudo service
- [x] Beide können ähnlich funktionieren je nach System
- [ ] Es gibt keine Äquivalente

# Frage 37
Was ist wichtig beim Deaktivieren von Services?
- [ ] Nur stoppen reicht
- [x] Sowohl stoppen als auch disable für Autostart
- [ ] Nur disable reicht
- [ ] Services können nicht deaktiviert werden

# Frage 38
Wie kann man temporär höhere sudo-Rechte testen?
- [ ] sudo su -
- [ ] sudo -i in separater Session
- [ ] sudo -l zur Überprüfung verwenden
- [x] Alle Methoden sind sinnvoll

# Frage 39
Was sollte man bei sudo-Troubleshooting zuerst prüfen?
- [ ] Netzwerk-Verbindung
- [x] Gruppen-Mitgliedschaft des Benutzers
- [ ] Festplatten-Platz
- [ ] System-Zeit

# Frage 40
Warum sollte der Root-Account in modernen Systemen deaktiviert bleiben?
- [ ] Spart Speicherplatz
- [x] Alle Admin-Aktionen laufen über sudo und sind auditierbar
- [ ] Root wird nicht benötigt
- [ ] Ist ein Security-Risiko ohne Vorteile
