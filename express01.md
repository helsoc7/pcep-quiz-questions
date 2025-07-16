# Node.js, Express & MySQL - 50 Quiz-Fragen

# Frage 1
Was ist der Hauptvorteil von MySQL gegenüber In-Memory Arrays?
- [ ] MySQL ist schneller
- [x] Daten bleiben nach Server-Neustart erhalten
- [ ] MySQL ist einfacher zu verwenden
- [ ] MySQL benötigt weniger Speicher

# Frage 2
Welches npm-Paket wird für MySQL-Verbindungen empfohlen?
- [ ] mysql
- [x] mysql2
- [ ] mysql-connector
- [ ] node-mysql

# Frage 3
Was ist ein Connection Pool?
- [ ] Eine Datenbank für Verbindungen
- [x] Ein System zur Wiederverwendung von Datenbankverbindungen
- [ ] Ein Backup-System
- [ ] Eine Art von SQL-Query

# Frage 4
Wie installiert man mysql2?
- [ ] `node install mysql2`
- [x] `npm install mysql2`
- [ ] `npm get mysql2`
- [ ] `mysql install mysql2`

# Frage 5
Was ist der Zweck von Environment Variables?
- [ ] Sie beschleunigen die App
- [x] Sie halten sensible Daten wie Passwörter sicher
- [ ] Sie erstellen automatisch Datenbanken
- [ ] Sie verbessern die Performance

# Frage 6
Welches npm-Paket wird für Environment Variables verwendet?
- [ ] env
- [x] dotenv
- [ ] environment
- [ ] config

# Frage 7
Wie greift man auf Environment Variables zu?
- [ ] `env.DB_PASSWORD`
- [x] `process.env.DB_PASSWORD`
- [ ] `environment.DB_PASSWORD`
- [ ] `system.env.DB_PASSWORD`

# Frage 8
In welcher Datei werden Environment Variables gespeichert?
- [ ] .config
- [x] .env
- [ ] .environment
- [ ] config.env

# Frage 9
Welcher SQL-Befehl erstellt eine neue Datenbank?
- [ ] `MAKE DATABASE`
- [x] `CREATE DATABASE`
- [ ] `NEW DATABASE`
- [ ] `BUILD DATABASE`

# Frage 10
Welcher SQL-Befehl wählt eine Datenbank aus?
- [ ] `SELECT DATABASE`
- [x] `USE databasename`
- [ ] `CHOOSE DATABASE`
- [ ] `PICK DATABASE`

# Frage 11
Was bedeutet AUTO_INCREMENT in SQL?
- [ ] Automatische Backups
- [x] Automatische Erhöhung der ID bei jedem neuen Eintrag
- [ ] Automatische Löschung alter Daten
- [ ] Automatische Sortierung

# Frage 12
Welcher SQL-Datentyp wird für Wahrheitswerte verwendet?
- [ ] TRUE_FALSE
- [x] BOOLEAN
- [ ] YESNO
- [ ] BINARY

# Frage 13
Wie verhindert man SQL-Injection?
- [ ] Durch komplexe Passwörter
- [x] Durch Parameter-Binding mit ?
- [ ] Durch Verschlüsselung
- [ ] Durch Firewalls

# Frage 14
Was ist Parameter-Binding?
- [ ] Das Verbinden von Datenbanken
- [x] Das sichere Einfügen von Werten in SQL-Queries
- [ ] Das Erstellen von Tabellen
- [ ] Das Backup von Daten

# Frage 15
Welche Syntax wird für Parameter-Binding in mysql2 verwendet?
- [ ] `{param}`
- [x] `?`
- [ ] `$param`
- [ ] `#{param}`

# Frage 16
Wie erstellt man eine MySQL-Verbindung mit mysql2?
- [ ] `mysql.connect()`
- [x] `mysql.createConnection()`
- [ ] `mysql.newConnection()`
- [ ] `mysql.open()`

# Frage 17
Was ist der Unterschied zwischen createConnection und createPool?
- [ ] createPool ist schneller
- [x] createPool verwaltet mehrere Verbindungen
- [ ] createConnection ist sicherer
- [ ] Es gibt keinen Unterschied

# Frage 18
Welcher SQL-Befehl fügt neue Daten ein?
- [ ] `ADD INTO`
- [x] `INSERT INTO`
- [ ] `PUT INTO`
- [ ] `CREATE INTO`

# Frage 19
Welcher SQL-Befehl aktualisiert bestehende Daten?
- [ ] `CHANGE`
- [x] `UPDATE`
- [ ] `MODIFY`
- [ ] `EDIT`

# Frage 20
Welcher SQL-Befehl löscht Daten?
- [ ] `REMOVE`
- [x] `DELETE`
- [ ] `DROP`
- [ ] `CLEAR`

# Frage 21
Was macht `res.status(201)` in Express?
- [ ] Setzt den Status auf "Error"
- [x] Setzt den Status auf "Created"
- [ ] Setzt den Status auf "OK"
- [ ] Setzt den Status auf "Not Found"

# Frage 22
Welcher HTTP-Status-Code wird für "Internal Server Error" verwendet?
- [ ] 404
- [ ] 400
- [x] 500
- [ ] 401

# Frage 23
Was ist nodemon?
- [ ] Ein Datenbank-Tool
- [x] Ein Tool zum automatischen Neustart bei Änderungen
- [ ] Ein Testing-Framework
- [ ] Ein Deployment-Tool

# Frage 24
Wie installiert man nodemon global?
- [ ] `npm install nodemon`
- [x] `npm install -g nodemon`
- [ ] `npm global nodemon`
- [ ] `node install -g nodemon`

# Frage 25
Was ist Middleware in Express?
- [ ] Ein Datenbank-System
- [x] Funktionen die zwischen Request und Response ausgeführt werden
- [ ] Ein Frontend-Framework
- [ ] Ein Debugging-Tool

# Frage 26
Welche Middleware wird für JSON-Parsing benötigt?
- [ ] `app.use(express.body())`
- [x] `app.use(express.json())`
- [ ] `app.use(express.parser())`
- [ ] `app.use(json.parse())`

# Frage 27
Was macht `morgan` in Express?
- [ ] Erstellt Datenbanken
- [x] Loggt HTTP-Requests
- [ ] Handhabt Fehler
- [ ] Parsiert JSON

# Frage 28
Wie bindet man statische Dateien in Express ein?
- [ ] `app.static('public')`
- [x] `app.use(express.static('public'))`
- [ ] `app.files('public')`
- [ ] `express.serve('public')`

# Frage 29
Was ist async/await in JavaScript?
- [ ] Ein Datenbank-Feature
- [x] Eine Möglichkeit, asynchronen Code zu schreiben
- [ ] Ein HTTP-Protokoll
- [ ] Ein Error-Handling-System

# Frage 30
Warum muss man `await` vor Datenbankoperationen verwenden?
- [ ] Für bessere Performance
- [x] Weil Datenbankoperationen asynchron sind
- [ ] Für Sicherheit
- [ ] Für Kompatibilität

# Frage 31
Was passiert wenn man `await` vergisst?
- [ ] Die App wird langsamer
- [x] Man bekommt ein Promise-Objekt statt des Ergebnisses
- [ ] Die Datenbank wird gelöscht
- [ ] Es passiert nichts

# Frage 32
Wie fängt man Fehler bei async/await ab?
- [ ] `catch(error)`
- [x] `try/catch`
- [ ] `error.handle()`
- [ ] `await.error()`

# Frage 33
Was ist der Rückgabewert von `pool.execute()`?
- [ ] Die Daten direkt
- [x] Ein Array mit [rows, fields]
- [ ] Ein Promise
- [ ] Ein String

# Frage 34
Wie greift man auf die Daten von `pool.execute()` zu?
- [ ] `result.data`
- [x] `const [rows] = await pool.execute()`
- [ ] `result.rows`
- [ ] `result[0]`

# Frage 35
Was ist `result.insertId`?
- [ ] Die Anzahl eingefügter Zeilen
- [x] Die ID des neu eingefügten Datensatzes
- [ ] Der Tabellenname
- [ ] Der Zeitstempel

# Frage 36
Welcher SQL-Befehl prüft ob eine Tabelle existiert?
- [ ] `CHECK TABLE`
- [x] `SHOW TABLES`
- [ ] `LIST TABLES`
- [ ] `FIND TABLE`

# Frage 37
Was ist eine PRIMARY KEY in SQL?
- [ ] Ein Passwort
- [x] Ein eindeutiger Identifikator für jede Zeile
- [ ] Der erste Eintrag in der Tabelle
- [ ] Ein wichtiges Feld

# Frage 38
Was bedeutet `DEFAULT CURRENT_TIMESTAMP` in SQL?
- [ ] Die Zeit wird manuell gesetzt
- [x] Die aktuelle Zeit wird automatisch eingefügt
- [ ] Die Zeit wird auf null gesetzt
- [ ] Die Zeit wird ignoriert

# Frage 39
Wie macht man ein Feld in SQL erforderlich?
- [ ] `REQUIRED`
- [x] `NOT NULL`
- [ ] `MANDATORY`
- [ ] `NEEDED`

# Frage 40
Was ist der Unterschied zwischen VARCHAR und TEXT?
- [ ] TEXT ist schneller
- [x] VARCHAR hat eine feste Maximallänge
- [ ] TEXT ist sicherer
- [ ] Es gibt keinen Unterschied

# Frage 41
Welcher SQL-Befehl zeigt die Struktur einer Tabelle?
- [ ] `SHOW STRUCTURE`
- [x] `DESCRIBE tablename`
- [ ] `LIST COLUMNS`
- [ ] `DISPLAY TABLE`

# Frage 42
Was ist Swagger/OpenAPI?
- [ ] Ein Datenbank-Tool
- [x] Ein Tool zur API-Dokumentation
- [ ] Ein Frontend-Framework
- [ ] Ein Testing-Tool

# Frage 43
Welches npm-Paket wird für Swagger verwendet?
- [ ] swagger
- [x] swagger-ui-express
- [ ] swagger-docs
- [ ] api-docs

# Frage 44
Was ist der Zweck von `@swagger` Kommentaren?
- [ ] Code-Optimierung
- [x] Automatische API-Dokumentation
- [ ] Debugging
- [ ] Performance-Monitoring

# Frage 45
Wie kann man eine MySQL-Datenbank sichern?
- [ ] Mit `BACKUP DATABASE`
- [x] Mit `mysqldump`
- [ ] Mit `COPY DATABASE`
- [ ] Mit `SAVE DATABASE`

# Frage 46
Was ist ein Index in MySQL?
- [ ] Die Reihenfolge der Tabellen
- [x] Eine Datenstruktur zur Beschleunigung von Abfragen
- [ ] Die erste Spalte einer Tabelle
- [ ] Ein Backup-System

# Frage 47
Welcher SQL-Befehl erstellt einen Index?
- [ ] `MAKE INDEX`
- [x] `CREATE INDEX`
- [ ] `ADD INDEX`
- [ ] `BUILD INDEX`

# Frage 48
Was ist LIKE in SQL?
- [ ] Ein Gleichheitsoperator
- [x] Ein Operator für Muster-Matching
- [ ] Ein Sortierbefehl
- [ ] Ein Join-Operator

# Frage 49
Welches Zeichen wird als Platzhalter bei LIKE verwendet?
- [ ] `*`
- [x] `%`
- [ ] `?`
- [ ] `&`

# Frage 50
Was sollte man mit der .env-Datei machen bevor man Code committet?
- [ ] Sie löschen
- [x] Sie zur .gitignore hinzufügen
- [ ] Sie umbenennen
- [ ] Sie verschlüsseln
