# Frage 1
Was ist das Hauptziel dieser Übung?
- [ ] Eine neue Datenbank erstellen
- [x] Eine zweite Entität (Owners) zur bestehenden Animal-API hinzufügen
- [ ] Die Animal-API komplett neu schreiben
- [ ] Nur die Datenbank erweitern ohne neue Routes

# Frage 2
Welche Tabelle soll in diesem Tutorial neu hinzugefügt werden?
- [ ] `animals`
- [x] `owners`
- [ ] `pets`
- [ ] `users`

# Frage 3
Welche Felder soll die neue `owners` Tabelle haben?
- [ ] id, name, age, genus
- [x] id, name, email, phone
- [ ] id, name, password, role
- [ ] id, owner_name, address, city

# Frage 4
Was ist der erste Schritt vor dem Hinzufügen neuer Features?
- [ ] Sofort mit dem Programmieren beginnen
- [x] Ein Backup der bestehenden Dateien erstellen
- [ ] Die Datenbank löschen
- [ ] Neue Dependencies installieren

# Frage 5
Wo wird die neue `owners` Tabelle definiert?
- [ ] In einer separaten Datei
- [x] In der erweiterten `init_db()` Funktion
- [ ] In einer neuen `create_owners.py` Datei
- [ ] Automatisch von Flask

# Frage 6
Welcher SQL-Befehl erstellt die `owners` Tabelle?
- [ ] `INSERT TABLE owners`
- [x] `CREATE TABLE IF NOT EXISTS owners`
- [ ] `ADD TABLE owners`
- [ ] `NEW TABLE owners`

# Frage 7
Was bedeutet `IF NOT EXISTS` in einem CREATE TABLE-Befehl?
- [ ] Die Tabelle wird gelöscht falls sie existiert
- [x] Die Tabelle wird nur erstellt, wenn sie noch nicht existiert
- [ ] Die Tabelle wird überschrieben
- [ ] Es wird ein Fehler geworfen falls sie existiert

# Frage 8
Welche Hilfsfunktionen werden für Owners benötigt?
- [ ] Nur `get_owner_by_id()`
- [x] `get_owner_by_id()` und `owner_exists()`
- [ ] Nur `owner_exists()`
- [ ] Keine zusätzlichen Funktionen

# Frage 9
Warum sind die Owner-Hilfsfunktionen fast identisch zu den Animal-Hilfsfunktionen?
- [ ] Das ist Zufall
- [x] Weil sie das gleiche Pattern verwenden (nur andere Tabelle)
- [ ] Weil SQLite das so verlangt
- [ ] Weil Flask das so vorschreibt

# Frage 10
Wie lautet die Route für alle Owners anzeigen?
- [ ] `/api/owner`
- [x] `/api/owners`
- [ ] `/owners`
- [ ] `/api/all-owners`

# Frage 11
Was ist der HTTP-Status-Code für erfolgreich erstellte Ressourcen?
- [ ] 200 (OK)
- [x] 201 (Created)
- [ ] 202 (Accepted)
- [ ] 204 (No Content)

# Frage 12
Welches Feld ist bei Owners ein Pflichtfeld?
- [x] `name`
- [ ] `email`
- [ ] `phone`
- [ ] Alle Felder sind optional

# Frage 13
Wie testet man die neue GET-Route für Owners?
- [ ] `curl http://localhost:5050/api/animals`
- [x] `curl http://localhost:5050/api/owners`
- [ ] `curl http://localhost:5050/owners`
- [ ] `curl http://localhost:5050/api/owner`

# Frage 14
Was macht die Funktion `owner_exists()`?
- [ ] Sie erstellt einen neuen Owner
- [x] Sie prüft ob ein Owner mit der gegebenen ID existiert
- [ ] Sie löscht einen Owner
- [ ] Sie zeigt alle Owners an

# Frage 15
Welche HTTP-Methode wird für das Hinzufügen neuer Owners verwendet?
- [x] POST
- [ ] GET
- [ ] PUT
- [ ] DELETE

# Frage 16
Was passiert wenn man versucht einen Owner ohne Name zu erstellen?
- [ ] Es wird automatisch ein Name generiert
- [x] Es wird ein Fehler (400 Bad Request) zurückgegeben
- [ ] Der Owner wird trotzdem erstellt
- [ ] Die App stürzt ab

# Frage 17
Welche HTTP-Methode wird zum Löschen von Owners verwendet?
- [ ] POST
- [ ] GET
- [ ] PUT
- [x] DELETE

# Frage 18
Was ist eine 1:n-Beziehung (one-to-many)?
- [ ] Jedes Tier kann mehrere Owners haben
- [x] Ein Owner kann mehrere Tiere haben, aber jedes Tier hat maximal einen Owner
- [ ] Alle Tiere gehören allen Owners
- [ ] Keine Beziehung zwischen Tieren und Owners

# Frage 19
Wie wird eine 1:n-Beziehung in der Datenbank umgesetzt?
- [ ] Mit einer separaten Beziehungstabelle
- [x] Mit einer Foreign Key-Spalte (owner_id) in der animals Tabelle
- [ ] Mit zwei separaten Datenbanken
- [ ] Automatisch von SQLite

# Frage 20
Was ist ein Foreign Key?
- [ ] Ein verschlüsselter Schlüssel
- [x] Eine Spalte, die auf den Primärschlüssel einer anderen Tabelle verweist
- [ ] Der erste Schlüssel in einer Tabelle
- [ ] Ein besonders wichtiger Schlüssel

# Frage 21
Welcher SQL-Befehl fügt eine neue Spalte zu einer existierenden Tabelle hinzu?
- [ ] `ADD COLUMN TO animals owner_id`
- [x] `ALTER TABLE animals ADD COLUMN owner_id INTEGER`
- [ ] `INSERT COLUMN animals.owner_id`
- [ ] `CREATE COLUMN owner_id IN animals`

# Frage 22
Was bedeutet `owner_id INTEGER` in der animals Tabelle?
- [ ] Der Owner muss eine Zahl als Namen haben
- [x] Die Owner-ID wird als Ganzzahl gespeichert
- [ ] Jeder Owner kann nur eine ID haben
- [ ] Owner-IDs müssen eindeutig sein

# Frage 23
Was bedeutet `owner_id` = NULL?
- [ ] Das Tier gehört dem Owner NULL
- [x] Das Tier hat keinen Owner (ist adoptierbar)
- [ ] Die Datenbank ist kaputt
- [ ] Der Owner wurde gelöscht

# Frage 24
Welche Route wird verwendet um ein Tier zu adoptieren?
- [ ] `POST /api/animals/<id>/adopt`
- [x] `POST /api/owners/<owner_id>/adopt/<animal_id>`
- [ ] `PUT /api/adopt`
- [ ] `GET /api/adoption`

# Frage 25
Was passiert wenn man versucht ein Tier zu adoptieren, das bereits einen Owner hat?
- [ ] Die Adoption wird automatisch durchgeführt
- [x] Es wird ein Fehler zurückgegeben
- [ ] Der alte Owner wird überschrieben
- [ ] Das Tier bekommt zwei Owners

# Frage 26
Wie gibt man ein Tier wieder frei (setzt owner_id auf NULL)?
- [ ] `DELETE /api/animals/<id>`
- [x] `POST /api/animals/<id>/release`
- [ ] `PUT /api/animals/<id>/free`
- [ ] `GET /api/animals/<id>/release`

# Frage 27
Was ist eine n:m-Beziehung (many-to-many)?
- [x] Jeder Owner kann mehrere Tiere füttern, jedes Tier kann von mehreren Owners gefüttert werden
- [ ] Ein Owner hat ein Tier
- [ ] Alle Owners haben alle Tiere
- [ ] Keine Beziehung zwischen Entitäten

# Frage 28
Wie wird eine n:m-Beziehung in der Datenbank umgesetzt?
- [ ] Mit Foreign Keys in beiden Tabellen
- [x] Mit einer separaten Zwischentabelle (z.B. feedings)
- [ ] Automatisch von SQLite
- [ ] Mit JSON-Feldern

# Frage 29
Welche Tabelle wird für die Fütterungen erstellt?
- [ ] `food`
- [x] `feedings`
- [ ] `meals`
- [ ] `feeding_history`

# Frage 30
Welche Felder hat die `feedings` Tabelle?
- [ ] id, animal_name, owner_name, food
- [x] id, owner_id, animal_id, feed_time, food_type, amount
- [ ] id, feeding_date, notes
- [ ] owner_id, animal_id

# Frage 31
Was macht `DATETIME DEFAULT CURRENT_TIMESTAMP`?
- [ ] Setzt das Datum auf NULL
- [x] Setzt automatisch die aktuelle Zeit als Standard-Wert
- [ ] Fragt den Benutzer nach der Zeit
- [ ] Verwendet immer das gleiche Datum

# Frage 32
Welche HTTP-Methode wird zum Füttern verwendet?
- [x] POST
- [ ] GET
- [ ] PUT
- [ ] DELETE

# Frage 33
Was ist ein JOIN in SQL?
- [ ] Eine neue Tabelle erstellen
- [x] Daten aus mehreren Tabellen verknüpfen und gemeinsam abfragen
- [ ] Zwei Datenbanken verbinden
- [ ] Tabellen löschen

# Frage 34
Wie zeigt man alle Fütterungen eines Tiers an?
- [ ] `GET /api/feedings/<animal_id>`
- [x] `GET /api/animals/<animal_id>/feedings`
- [ ] `GET /api/food/<animal_id>`
- [ ] `POST /api/animals/<animal_id>/history`

# Frage 35
Was macht dieser SQL-Befehl: `SELECT * FROM animals WHERE owner_id IS NULL`?
- [ ] Zeigt alle Tiere an
- [x] Zeigt nur Tiere ohne Owner an (adoptierbare Tiere)
- [ ] Löscht Tiere ohne Owner
- [ ] Setzt alle owner_id auf NULL

# Frage 36
Welche Route zeigt alle Tiere eines Owners an?
- [ ] `GET /api/animals/by-owner/<id>`
- [x] `GET /api/owners/<id>/animals`
- [ ] `GET /api/owner-animals/<id>`
- [ ] `POST /api/owners/<id>/pets`

# Frage 37
Was ist der Vorteil von verschachtelten Routes wie `/api/owners/<id>/animals`?
- [ ] Sie sind kürzer
- [x] Sie zeigen die Beziehung zwischen Entitäten klar an
- [ ] Sie sind schneller
- [ ] Sie sind einfacher zu programmieren

# Frage 38
Wie kann man zählen wie viele Tiere adoptiert sind?
- [ ] `SELECT animals FROM adopted`
- [x] `SELECT COUNT(*) FROM animals WHERE owner_id IS NOT NULL`
- [ ] `COUNT(animals.adopted)`
- [ ] `SELECT SUM(animals) WHERE adopted = true`

# Frage 39
Was macht `GROUP BY` in SQL?
- [ ] Sortiert Ergebnisse
- [x] Fasst Zeilen mit gleichen Werten zusammen
- [ ] Filtert Ergebnisse
- [ ] Löscht doppelte Einträge

# Frage 40
Wie findet man den Owner mit den meisten Tieren?
- [ ] `SELECT owner FROM animals LIMIT 1`
- [x] `SELECT owner_id, COUNT(*) FROM animals GROUP BY owner_id ORDER BY COUNT(*) DESC LIMIT 1`
- [ ] `MAX(owner_id) FROM animals`
- [ ] `SELECT ALL owners WHERE animals > 1`

# Frage 41
Was ist `LEFT JOIN` vs `INNER JOIN`?
- [ ] LEFT JOIN ist schneller
- [x] LEFT JOIN zeigt auch Einträge aus der linken Tabelle ohne Match, INNER JOIN nur bei beiden
- [ ] LEFT JOIN ist für linke Spalten, INNER JOIN für innere
- [ ] Es gibt keinen Unterschied

# Frage 42
Welcher HTTP-Status-Code wird für "nicht gefunden" verwendet?
- [ ] 400 (Bad Request)
- [ ] 401 (Unauthorized)
- [ ] 403 (Forbidden)
- [x] 404 (Not Found)

# Frage 43
Was ist das Prinzip der Code-Wiederverwendung in diesem Tutorial?
- [ ] Alles neu schreiben
- [x] Bestehende Patterns kopieren und minimal anpassen
- [ ] Externe Libraries verwenden
- [ ] Automatische Code-Generierung

# Frage 44
Warum ist Konsistenz in API-Design wichtig?
- [ ] Es sieht schöner aus
- [x] Es macht die API vorhersagbar und einfacher zu verwenden
- [ ] Es ist gesetzlich vorgeschrieben
- [ ] Es reduziert die Dateigröße

# Frage 45
Was ist ein Workflow-Test?
- [ ] Ein Test der nur eine Funktion prüft
- [x] Ein Test der mehrere zusammenhängende Schritte durchläuft
- [ ] Ein automatischer Test
- [ ] Ein Test der Geschwindigkeit misst

# Frage 46
Welche URL zeigt verfügbare (adoptierbare) Tiere an?
- [ ] `/api/animals/free`
- [x] `/api/animals/available`
- [ ] `/api/animals/adoptable`
- [ ] `/api/animals/no-owner`

# Frage 47
Was macht diese Route: `POST /api/feed`?
- [ ] Zeigt Futter an
- [x] Fügt eine neue Fütterung hinzu
- [ ] Löscht Futter
- [ ] Kauft Futter

# Frage 48
Welche Felder sind beim Füttern erforderlich?
- [ ] Nur animal_id
- [x] owner_id, animal_id, food_type, amount
- [ ] Nur food_type
- [ ] feed_time und amount

# Frage 49
Was zeigt die erweiterte Statistik-Route `/api/stats`?
- [ ] Nur die Anzahl der Tiere
- [x] Adoptierte vs. verfügbare Tiere, Top-Owner, beliebtestes Futter
- [ ] Nur Owner-Informationen
- [ ] Die Datenbankgröße

# Frage 50
Was ist der wichtigste Lernerfolg dieses Tutorials?
- [ ] Neue SQL-Befehle lernen
- [x] Verstehen wie man bestehende Code-Patterns wiederverwenden und erweitern kann
- [ ] Eine komplexe Datenbank erstellen
- [ ] Alle Flask-Features kennenlernen
