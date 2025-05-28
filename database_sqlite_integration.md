# Frage 1
Was ist SQLite?
- [ ] Eine serverbasierte Datenbank wie MySQL
- [x] Eine dateibasierte Datenbank, die alle Daten in einer einzigen .db-Datei speichert
- [ ] Ein Python-Modul für Datenbankverbindungen
- [ ] Eine NoSQL-Datenbank

# Frage 2
Welcher SQL-Befehl wird verwendet, um eine neue Tabelle zu erstellen?
- [ ] `INSERT TABLE`
- [x] `CREATE TABLE`
- [ ] `NEW TABLE`
- [ ] `ADD TABLE`

# Frage 3
Was bewirkt `con.row_factory = sqlite3.Row` in SQLite?
- [ ] Es erstellt automatisch neue Zeilen
- [x] Es ermöglicht Dictionary-ähnlichen Zugriff auf Spalten (z.B. `animal['name']`)
- [ ] Es formatiert die Ausgabe als Tabelle
- [ ] Es aktiviert automatische Backups

# Frage 4
Warum sollten Platzhalter (?) in SQL-Queries verwendet werden?
- [ ] Um die Performance zu verbessern
- [x] Um SQL-Injection-Angriffe zu verhindern
- [ ] Um Speicher zu sparen
- [ ] Um automatische Typenkonvertierung zu aktivieren

# Frage 5
Was ist der Zweck der `get_db_connection()` Hilfsfunktion?
- [ ] Um die Datenbank zu erstellen
- [x] Um Code-Wiederholung zu vermeiden und zentrale Konfiguration zu ermöglichen
- [ ] Um die Verbindung automatisch zu schließen
- [ ] Um SQL-Befehle zu validieren

# Frage 6
Welcher Befehl wird benötigt, um Änderungen in der Datenbank dauerhaft zu speichern?
- [ ] `con.save()`
- [ ] `con.write()`
- [x] `con.commit()`
- [ ] `con.flush()`

# Frage 7
Was ist der Hauptvorteil einer Datenbank gegenüber Python-Listen?
- [ ] Datenbanken sind schneller
- [x] Daten bleiben nach dem Neustart der Anwendung erhalten (Persistenz)
- [ ] Datenbanken benötigen weniger Speicher
- [ ] Datenbanken sind einfacher zu programmieren

# Frage 8
Welche HTTP-Methode wird typischerweise für das vollständige Ersetzen eines Datensatzes verwendet?
- [ ] POST
- [ ] PATCH
- [x] PUT
- [ ] GET

# Frage 9
Was macht `executemany()` in SQLite?
- [ ] Es führt mehrere verschiedene SQL-Befehle aus
- [x] Es führt denselben SQL-Befehl mit verschiedenen Parametern aus
- [ ] Es erstellt mehrere Verbindungen zur Datenbank
- [ ] Es führt Befehle parallel aus

# Frage 10
Warum ist `con.close()` wichtig?
- [ ] Um Speicher freizugeben
- [ ] Um die Datenbank zu sperren
- [x] Um Datenbankverbindungen zu schließen und Ressourcen freizugeben
- [ ] Um Transaktionen rückgängig zu machen

# Frage 11
Was ist ein Primärschlüssel (Primary Key)?
- [ ] Ein verschlüsseltes Passwort für die Datenbank
- [x] Eine eindeutige Identifikation für jede Zeile in einer Tabelle
- [ ] Der erste Eintrag in einer Tabelle
- [ ] Ein Index für bessere Performance

# Frage 12
Welcher SQL-Befehl wird verwendet, um Daten in eine Tabelle einzufügen?
- [x] `INSERT INTO`
- [ ] `ADD TO`
- [ ] `CREATE INTO`
- [ ] `PUT INTO`

# Frage 13
Was bedeutet `AUTOINCREMENT` bei einem Primärschlüssel?
- [ ] Der Wert wird automatisch verschlüsselt
- [x] Der Wert wird automatisch um 1 erhöht für jeden neuen Eintrag
- [ ] Der Wert wird automatisch sortiert
- [ ] Der Wert wird automatisch validiert

# Frage 14
Welcher SQL-Befehl wird verwendet, um Daten aus einer Tabelle abzurufen?
- [ ] `GET`
- [ ] `FETCH`
- [x] `SELECT`
- [ ] `RETRIEVE`

# Frage 15
Was macht `fetchone()` in SQLite?
- [ ] Es holt alle Zeilen aus dem Ergebnis
- [x] Es holt die nächste einzelne Zeile aus dem Ergebnis
- [ ] Es holt die erste Zeile und löscht sie
- [ ] Es zählt die Anzahl der Zeilen

# Frage 16
Was macht `fetchall()` in SQLite?
- [x] Es holt alle verbleibenden Zeilen aus dem Ergebnis
- [ ] Es holt nur die erste Zeile
- [ ] Es zählt alle Zeilen
- [ ] Es löscht alle Zeilen

# Frage 17
Welcher SQL-Befehl wird verwendet, um Daten zu aktualisieren?
- [ ] `CHANGE`
- [ ] `MODIFY`
- [x] `UPDATE`
- [ ] `ALTER`

# Frage 18
Welcher SQL-Befehl wird verwendet, um Daten zu löschen?
- [ ] `REMOVE`
- [x] `DELETE`
- [ ] `DROP`
- [ ] `CLEAR`

# Frage 19
Was ist der Unterschied zwischen `DELETE` und `DROP`?
- [x] `DELETE` löscht Zeilen, `DROP` löscht die gesamte Tabelle
- [ ] `DELETE` ist schneller als `DROP`
- [ ] `DROP` löscht nur eine Zeile, `DELETE` löscht alle
- [ ] Es gibt keinen Unterschied

# Frage 20
Wie erstellt man eine Verbindung zu einer SQLite-Datenbank in Python?
- [ ] `sqlite3.open("database.db")`
- [x] `sqlite3.connect("database.db")`
- [ ] `sqlite3.create("database.db")`
- [ ] `sqlite3.new("database.db")`

# Frage 21
Was passiert, wenn man `sqlite3.connect()` auf eine nicht existierende Datei anwendet?
- [ ] Es wird ein Fehler geworfen
- [x] Die Datei wird automatisch erstellt
- [ ] Das Programm stürzt ab
- [ ] Es wird nach einer existierenden Datei gesucht

# Frage 22
Wozu dient ein Cursor in SQLite?
- [ ] Zum Navigieren zwischen Datenbanken
- [x] Zum Ausführen von SQL-Befehlen und Abrufen von Ergebnissen
- [ ] Zum Sperren der Datenbank
- [ ] Zum Erstellen von Backups

# Frage 23
Wie erstellt man einen Cursor in SQLite?
- [ ] `sqlite3.cursor()`
- [x] `con.cursor()`
- [ ] `cursor.create()`
- [ ] `db.get_cursor()`

# Frage 24
Was ist eine Transaktion in einer Datenbank?
- [ ] Eine einzelne SQL-Abfrage
- [x] Eine Gruppe von Operationen, die entweder alle erfolgreich sind oder alle rückgängig gemacht werden
- [ ] Eine Verbindung zur Datenbank
- [ ] Ein Backup der Datenbank

# Frage 25
Wann sollte man `commit()` aufrufen?
- [ ] Nach jeder SELECT-Abfrage
- [x] Nach INSERT, UPDATE oder DELETE-Operationen
- [ ] Beim Öffnen der Datenbankverbindung
- [ ] Nur beim Schließen der Verbindung

# Frage 26
Was passiert, wenn man `commit()` vergisst?
- [ ] Die Daten werden automatisch gespeichert
- [x] Die Änderungen gehen verloren
- [ ] Es wird ein Fehler geworfen
- [ ] Die Datenbank wird gesperrt

# Frage 27
Was macht die `init_db()` Funktion im Tutorial?
- [ ] Sie löscht die Datenbank
- [x] Sie erstellt die Tabelle und fügt Beispieldaten ein
- [ ] Sie stellt eine Verbindung her
- [ ] Sie führt ein Backup durch

# Frage 28
Was bedeutet `IF NOT EXISTS` in einem CREATE TABLE-Befehl?
- [ ] Die Tabelle wird nur erstellt, wenn sie Daten enthält
- [x] Die Tabelle wird nur erstellt, wenn sie noch nicht existiert
- [ ] Die Tabelle wird gelöscht, falls sie existiert
- [ ] Die Tabelle wird überschrieben

# Frage 29
Welcher HTTP-Status-Code wird typischerweise für erfolgreich erstellte Ressourcen zurückgegeben?
- [ ] 200 (OK)
- [x] 201 (Created)
- [ ] 202 (Accepted)
- [ ] 204 (No Content)

# Frage 30
Welcher HTTP-Status-Code wird zurückgegeben, wenn eine Ressource nicht gefunden wird?
- [ ] 400 (Bad Request)
- [ ] 401 (Unauthorized)
- [ ] 403 (Forbidden)
- [x] 404 (Not Found)

# Frage 31
Was ist der Unterschied zwischen PUT und PATCH?
- [x] PUT ersetzt die gesamte Ressource, PATCH aktualisiert nur bestimmte Felder
- [ ] PUT ist für neue Ressourcen, PATCH für Updates
- [ ] PUT ist schneller als PATCH
- [ ] Es gibt keinen Unterschied

# Frage 32
Wie kann man in Flask JSON-Daten aus einer POST-Anfrage abrufen?
- [ ] `request.json()`
- [x] `request.get_json()`
- [ ] `request.data.json()`
- [ ] `request.form.json()`

# Frage 33
Was macht `jsonify()` in Flask?
- [ ] Es validiert JSON-Daten
- [x] Es konvertiert Python-Objekte in JSON-Antworten
- [ ] Es parst JSON-Strings
- [ ] Es komprimiert JSON-Daten

# Frage 34
Wie kann man URL-Parameter in Flask-Routen definieren?
- [ ] `@app.route("/animals?id=<int:id>")`
- [x] `@app.route("/animals/<int:animal_id>")`
- [ ] `@app.route("/animals/{id}")`
- [ ] `@app.route("/animals/:id")`

# Frage 35
Was ist ein Context Manager in Python?
- [ ] Eine Klasse für Datenbankverbindungen
- [x] Ein Objekt, das `__enter__` und `__exit__` Methoden implementiert
- [ ] Eine Funktion für Fehlerbehandlung
- [ ] Ein Decorator für Flask-Routen

# Frage 36
Welcher Vorteil hat ein Context Manager für Datenbankverbindungen?
- [ ] Er macht die Verbindung schneller
- [x] Er schließt die Verbindung automatisch, auch wenn ein Fehler auftritt
- [ ] Er erstellt mehrere Verbindungen
- [ ] Er validiert SQL-Befehle

# Frage 37
Wie kann man in SQL nach Mustern suchen?
- [ ] Mit dem `MATCH` Operator
- [x] Mit dem `LIKE` Operator
- [ ] Mit dem `SEARCH` Operator
- [ ] Mit dem `FIND` Operator

# Frage 38
Was bedeutet das `%` Zeichen in einem SQL LIKE-Operator?
- [ ] Genau ein beliebiges Zeichen
- [x] Null oder mehr beliebige Zeichen
- [ ] Ein Prozentzeichen
- [ ] Ein Platzhalter für Zahlen

# Frage 39
Wie fügt man eine neue Spalte zu einer existierenden Tabelle hinzu?
- [ ] `ADD COLUMN table_name column_name`
- [x] `ALTER TABLE table_name ADD COLUMN column_name`
- [ ] `INSERT COLUMN INTO table_name`
- [ ] `CREATE COLUMN table_name.column_name`

# Frage 40
Was ist SQL-Injection?
- [ ] Ein Fehler in der Datenbankverbindung
- [x] Ein Sicherheitsangriff, bei dem schädlicher SQL-Code in Eingaben eingeschleust wird
- [ ] Ein Verfahren zum Optimieren von Abfragen
- [ ] Ein Backup-Verfahren

# Frage 41
Welche ist die sichere Methode für SQL-Abfragen mit Benutzereingaben?
- [ ] String-Formatierung: `f"SELECT * FROM users WHERE name = '{name}'"`
- [ ] String-Konkatenation: `"SELECT * FROM users WHERE name = '" + name + "'"`
- [x] Parametrisierte Abfragen: `"SELECT * FROM users WHERE name = ?", (name,)`
- [ ] Escape-Zeichen: `"SELECT * FROM users WHERE name = \'{}\'".format(name)`

# Frage 42
Was macht `COUNT(*)` in SQL?
- [ ] Es zählt die Anzahl der Spalten
- [x] Es zählt die Anzahl der Zeilen
- [ ] Es zählt die Anzahl der Tabellen
- [ ] Es berechnet die Summe aller Werte

# Frage 43
Wozu dient `ORDER BY` in SQL?
- [ ] Um Daten zu filtern
- [x] Um Ergebnisse zu sortieren
- [ ] Um Daten zu gruppieren
- [ ] Um Daten zu zählen

# Frage 44
Was ist der Standard-Sortierbefehl bei `ORDER BY`?
- [x] Aufsteigend (ASC)
- [ ] Absteigend (DESC)
- [ ] Alphabetisch
- [ ] Zufällig

# Frage 45
Wie kann man mehrere Zeilen gleichzeitig in eine Tabelle einfügen?
- [ ] Mit mehreren `INSERT` Befehlen
- [x] Mit `INSERT INTO table VALUES (data1), (data2), (data3)`
- [ ] Mit `INSERT MULTIPLE`
- [ ] Mit `BULK INSERT`

# Frage 46
Was passiert, wenn man versucht, einen NULL-Wert in eine NOT NULL-Spalte einzufügen?
- [ ] Der Wert wird als leer-String gespeichert
- [x] Es wird ein Fehler geworfen
- [ ] Der Wert wird als 0 gespeichert
- [ ] Die Zeile wird übersprungen

# Frage 47
Was ist der Unterschied zwischen `rowcount` und `fetchall()`?
- [x] `rowcount` gibt die Anzahl betroffener Zeilen zurück, `fetchall()` gibt die Daten zurück
- [ ] `rowcount` ist schneller als `fetchall()`
- [ ] `fetchall()` ist für UPDATE, `rowcount` für SELECT
- [ ] Es gibt keinen Unterschied

# Frage 48
Welche Flask-Funktion wird verwendet, um URL-Parameter abzurufen?
- [x] `request.args.get()`
- [ ] `request.params.get()`
- [ ] `request.url.get()`
- [ ] `request.query.get()`

# Frage 49
Was ist eine RESTful API?
- [ ] Eine API, die nur GET-Requests unterstützt
- [x] Eine API, die HTTP-Methoden semantisch korrekt für CRUD-Operationen verwendet
- [ ] Eine API für Datenbanken
- [ ] Eine verschlüsselte API

# Frage 50
Was sollte man beim Schließen einer Flask-Anwendung mit Datenbankverbindungen beachten?
- [ ] Die Datenbank muss gelöscht werden
- [x] Alle offenen Verbindungen sollten ordnungsgemäß geschlossen werden
- [ ] Die Datenbank muss gesperrt werden
- [ ] Ein Backup muss erstellt werden
