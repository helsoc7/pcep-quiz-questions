# Cookies & localStorage - 40 Quiz-Fragen (Einfach)

# Frage 1
Warum braucht man Cookies?
- [ ] Für bessere Performance
- [x] Weil HTTP zustandslos ist und der Server sich nicht an Clients erinnert
- [ ] Für Verschlüsselung
- [ ] Für Komprimierung

# Frage 2
Wie setzt ein Server ein Cookie?
- [ ] Mit dem GET-Header
- [x] Mit dem Set-Cookie-Header in der HTTP-Response
- [ ] Mit dem POST-Body
- [ ] Mit der URL

# Frage 3
Wie sendet ein Browser ein Cookie zurück an den Server?
- [x] Automatisch im Cookie-Header bei jeder Anfrage
- [ ] Nur wenn der Benutzer es erlaubt
- [ ] Nur bei POST-Requests
- [ ] Nur bei GET-Requests

# Frage 4
Wie groß kann ein Cookie maximal sein?
- [ ] 1 MB
- [x] Etwa 4 KB
- [ ] 100 KB
- [ ] Unbegrenzt

# Frage 5
Was bedeutet das HttpOnly-Flag bei Cookies?
- [ ] Das Cookie funktioniert nur über HTTP
- [x] Das Cookie kann nicht per JavaScript ausgelesen werden
- [ ] Das Cookie wird nur einmal gesendet
- [ ] Das Cookie ist verschlüsselt

# Frage 6
Was ist ein First-Party-Cookie?
- [x] Ein Cookie von der Domain, die der Nutzer gerade besucht
- [ ] Ein Cookie von einem Werbetreibenden
- [ ] Das erste Cookie einer Session
- [ ] Ein verschlüsseltes Cookie

# Frage 7
Was ist ein Third-Party-Cookie?
- [ ] Ein Cookie von der aktuellen Domain
- [x] Ein Cookie von einer anderen Domain als der besuchten
- [ ] Das dritte Cookie einer Session
- [ ] Ein unverschlüsseltes Cookie

# Frage 8
Wofür werden Third-Party-Cookies hauptsächlich verwendet?
- [ ] Für Login-Sessions
- [x] Für Cross-Site-Tracking und Werbung
- [ ] Für Website-Einstellungen
- [ ] Für Sicherheit

# Frage 9
Warum haben moderne Browser Third-Party-Cookies oft blockiert?
- [ ] Sie sind zu groß
- [x] Datenschutzbedenken wegen Cross-Site-Tracking
- [ ] Sie sind unsicher
- [ ] Sie verlangsamen die Website

# Frage 10
Was bedeutet SameSite=Lax bei einem Cookie?
- [x] Das Cookie wird nicht bei Cross-Site-Requests gesendet
- [ ] Das Cookie ist verschlüsselt
- [ ] Das Cookie ist nur für HTTPS
- [ ] Das Cookie ist sehr groß

# Frage 11
Warum gibt es oft mehrere Cookies auf einer Website?
- [x] Verschiedene Zwecke brauchen verschiedene Cookies
- [ ] Cookies sind zu klein für alle Daten
- [ ] Das ist ein Fehler
- [ ] Für bessere Performance

# Frage 12
Sind Cookies an die IP-Adresse des Benutzers gebunden?
- [x] Nein, Cookies sind an die Domain gebunden
- [ ] Ja, Cookies sind immer IP-gebunden
- [ ] Nur bei HTTPS
- [ ] Nur bei Third-Party-Cookies

# Frage 13
Was ist localStorage?
- [ ] Ein Server-seitiger Speicher
- [x] Ein Browser-seitiger Speicher für Daten
- [ ] Eine Art von Cookie
- [ ] Eine Datenbank

# Frage 14
Wie groß kann localStorage sein?
- [ ] 4 KB wie Cookies
- [x] Etwa 5-10 MB
- [ ] Unbegrenzt
- [ ] 1 KB

# Frage 15
Werden localStorage-Daten automatisch an den Server gesendet?
- [x] Nein, nur per JavaScript zugänglich
- [ ] Ja, bei jeder Anfrage
- [ ] Nur bei POST-Requests
- [ ] Nur bei Login

# Frage 16
Wann sollte man localStorage verwenden?
- [ ] Für Login-Sessions
- [x] Für Client-seitige Einstellungen und Cache
- [ ] Für Passwörter
- [ ] Für Server-Kommunikation

# Frage 17
Wann sollte man Cookies verwenden?
- [x] Für Sessions und Server-Kommunikation
- [ ] Für große Datenmengen
- [ ] Für Client-seitige Berechnungen
- [ ] Für Bilder

# Frage 18
Was ist sicherer gegen XSS-Angriffe?
- [x] HttpOnly-Cookies
- [ ] localStorage
- [ ] sessionStorage
- [ ] Normale Cookies

# Frage 19
Wo sollte man JWT-Tokens am besten speichern?
- [ ] In localStorage
- [x] In HttpOnly-Cookies
- [ ] In sessionStorage
- [ ] Im HTML

# Frage 20
Warum ist localStorage problematisch für JWT-Tokens?
- [x] XSS-Angriffe können die Tokens stehlen
- [ ] localStorage ist zu klein
- [ ] Tokens funktionieren dort nicht
- [ ] Es ist zu langsam

# Frage 21
Was ist CommonJS?
- [x] Ein Modul-System für Node.js
- [ ] Eine neue JavaScript-Version
- [ ] Ein Webframework
- [ ] Eine Datenbank

# Frage 22
Welche Syntax verwendet CommonJS für Imports?
- [x] require()
- [ ] import
- [ ] include()
- [ ] load()

# Frage 23
Was sind ES Modules (ESM)?
- [ ] Ein Node.js-Feature
- [x] Der offizielle JavaScript-Standard für Module
- [ ] Eine Datenbank
- [ ] Ein Framework

# Frage 24
Welche Syntax verwenden ES Modules für Imports?
- [ ] require()
- [x] import
- [ ] include()
- [ ] load()

# Frage 25
Was ist neuer: CommonJS oder ES Modules?
- [ ] CommonJS
- [x] ES Modules
- [ ] Beide sind gleich alt
- [ ] Das ist unbekannt

# Frage 26
Welcher Wert in package.json aktiviert ES Modules?
- [ ] "type": "commonjs"
- [x] "type": "module"
- [ ] "type": "esm"
- [ ] "modules": true

# Frage 27
Was passiert ohne "type"-Feld in package.json?
- [x] Node.js verwendet standardmäßig CommonJS
- [ ] Node.js verwendet ES Modules
- [ ] Es gibt einen Fehler
- [ ] Beide Systeme funktionieren

# Frage 28
Was macht app.listen() in Express?
- [ ] Schließt den Server
- [x] Startet einen HTTP-Server auf einem Port
- [ ] Lädt eine Datei
- [ ] Sendet eine Antwort

# Frage 29
Warum bricht ein Express-Server manchmal ab?
- [ ] Das ist normal
- [x] Wegen unbehandelten Fehlern oder belegten Ports
- [ ] Express ist instabil
- [ ] Das passiert nie

# Frage 30
Welcher Standard-Port wird oft für Express-Server verwendet?
- [ ] 80
- [x] 3000
- [ ] 443
- [ ] 8080

# Frage 31
Was bedeutet EADDRINUSE-Fehler?
- [ ] Falsche Syntax
- [x] Der Port ist bereits belegt
- [ ] Fehlende Berechtigung
- [ ] Netzwerkfehler

# Frage 32
Was ist ein Session-Cookie?
- [x] Ein Cookie das beim Schließen des Browsers verschwindet
- [ ] Ein Cookie für Login-Daten
- [ ] Ein verschlüsseltes Cookie
- [ ] Ein sehr großes Cookie

# Frage 33
Was ist ein Persistent-Cookie?
- [ ] Ein Cookie das immer da ist
- [x] Ein Cookie mit festem Ablaufdatum
- [ ] Ein unverschlüsseltes Cookie
- [ ] Ein Cookie ohne Wert

# Frage 34
Wie kann man ein Cookie in Express löschen?
- [ ] res.deleteCookie()
- [x] res.clearCookie()
- [ ] res.removeCookie()
- [ ] res.eraseCookie()

# Frage 35
Was ist ein CSRF-Token?
- [ ] Ein Login-Token
- [x] Ein Sicherheits-Token gegen Cross-Site-Request-Forgery
- [ ] Ein Verschlüsselungs-Token
- [ ] Ein Session-Token

# Frage 36
Welches Flag macht Cookies sicherer für HTTPS?
- [ ] HttpOnly
- [x] Secure
- [ ] SameSite
- [ ] Path

# Frage 37
Was passiert mit localStorage beim Schließen des Browsers?
- [x] Die Daten bleiben gespeichert
- [ ] Die Daten werden gelöscht
- [ ] Das ist browserabhängig
- [ ] Die Daten werden komprimiert

# Frage 38
Welches npm-Paket wird für Cookie-Parsing in Express verwendet?
- [ ] express-cookies
- [x] cookie-parser
- [ ] cookie-middleware
- [ ] express-parser

# Frage 39
Was ist der Unterschied zwischen sessionStorage und localStorage?
- [x] sessionStorage wird beim Schließen des Tabs gelöscht
- [ ] sessionStorage ist größer
- [ ] sessionStorage ist sicherer
- [ ] Es gibt keinen Unterschied

# Frage 40
Warum sollte man Passwörter niemals in Cookies oder localStorage speichern?
- [x] Wegen Sicherheitsrisiken bei Client-seitiger Speicherung
- [ ] Sie sind zu groß
- [ ] Sie funktionieren nicht
- [ ] Es ist illegal
