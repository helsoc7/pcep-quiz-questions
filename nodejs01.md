# Node.js und Backend-Grundlagen - 50 Quiz-Fragen

# Frage 1
Was ist Node.js?
- [ ] Ein Frontend-Framework
- [x] Eine JavaScript-Laufzeitumgebung für Server
- [ ] Eine Datenbank
- [ ] Ein CSS-Framework

# Frage 2
Welcher Befehl überprüft die installierte Node.js-Version?
- [ ] `npm --version`
- [x] `node --version`
- [ ] `nodejs --version`
- [ ] `node -v`

# Frage 3
Wie führt man eine JavaScript-Datei mit Node.js aus?
- [ ] `npm run datei.js`
- [x] `node datei.js`
- [ ] `javascript datei.js`
- [ ] `js datei.js`

# Frage 4
Was ist Express.js?
- [ ] Ein Frontend-Framework
- [x] Ein Backend-Framework für Node.js
- [ ] Eine Datenbank
- [ ] Ein CSS-Preprocessor

# Frage 5
Welcher Befehl installiert Express in einem Projekt?
- [ ] `node install express`
- [x] `npm install express`
- [ ] `npm get express`
- [ ] `install express`

# Frage 6
Wie erstellt man eine Express-App?
- [ ] `const app = new Express();`
- [x] `const app = express();`
- [ ] `const app = Express.create();`
- [ ] `const app = new express();`

# Frage 7
Welche HTTP-Methode wird für das Abrufen von Daten verwendet?
- [x] GET
- [ ] POST
- [ ] PUT
- [ ] DELETE

# Frage 8
Wie definiert man eine GET-Route in Express?
- [ ] `app.route('/', 'GET')`
- [x] `app.get('/', function)`
- [ ] `app.GET('/', function)`
- [ ] `express.get('/', function)`

# Frage 9
Welcher Port wird standardmäßig in dem Tutorial für den Express-Server verwendet?
- [ ] 8080
- [ ] 8000
- [x] 3000
- [ ] 5000

# Frage 10
Wie startet man einen Express-Server?
- [ ] `app.start(3000)`
- [x] `app.listen(3000)`
- [ ] `app.run(3000)`
- [ ] `express.start(3000)`

# Frage 11
Welche Methode sendet JSON-Daten als Antwort?
- [ ] `res.send()`
- [x] `res.json()`
- [ ] `res.data()`
- [ ] `res.sendJSON()`

# Frage 12
Was ist das Flask-Äquivalent zu `res.json()` in Express?
- [ ] `return json(data)`
- [x] `return jsonify(data)`
- [ ] `return data.json()`
- [ ] `return JSON(data)`

# Frage 13
Welche Middleware ist nötig, um JSON-Request-Bodies zu verarbeiten?
- [ ] `app.use(express.body())`
- [x] `app.use(express.json())`
- [ ] `app.use(express.parseJSON())`
- [ ] `app.use(json.parse())`

# Frage 14
Wie greift man auf URL-Parameter zu (z.B. `/user/:id`)?
- [ ] `req.url.id`
- [x] `req.params.id`
- [ ] `req.id`
- [ ] `req.parameter.id`

# Frage 15
Welche HTTP-Methode wird zum Erstellen neuer Daten verwendet?
- [ ] GET
- [x] POST
- [ ] PUT
- [ ] DELETE

# Frage 16
Wie greift man auf den Request-Body in Express zu?
- [ ] `req.data`
- [x] `req.body`
- [ ] `req.content`
- [ ] `req.payload`

# Frage 17
Welcher HTTP-Status-Code wird für "Created" (erfolgreich erstellt) verwendet?
- [ ] 200
- [x] 201
- [ ] 202
- [ ] 204

# Frage 18
Wie setzt man einen HTTP-Status-Code in Express?
- [ ] `res.code(404)`
- [x] `res.status(404)`
- [ ] `res.setStatus(404)`
- [ ] `res.httpStatus(404)`

# Frage 19
Welche HTTP-Methode wird zum Aktualisieren von Daten verwendet?
- [ ] GET
- [ ] POST
- [x] PUT
- [ ] DELETE

# Frage 20
Welche HTTP-Methode wird zum Löschen von Daten verwendet?
- [ ] GET
- [ ] POST
- [ ] PUT
- [x] DELETE

# Frage 21
Wie serviert man statische Dateien (HTML, CSS, JS) in Express?
- [ ] `app.static('public')`
- [x] `app.use(express.static('public'))`
- [ ] `app.serveStatic('public')`
- [ ] `express.files('public')`

# Frage 22
Wie macht man einen POST-Request mit fetch() im Frontend?
- [ ] `fetch(url, {type: 'POST'})`
- [x] `fetch(url, {method: 'POST'})`
- [ ] `fetch(url, {request: 'POST'})`
- [ ] `fetch.post(url)`

# Frage 23
Welcher Content-Type wird für JSON-Daten verwendet?
- [ ] `text/json`
- [x] `application/json`
- [ ] `data/json`
- [ ] `content/json`

# Frage 24
Was ist CRUD?
- [ ] Ein Datenbank-System
- [x] Create, Read, Update, Delete - die grundlegenden Datenbankoperationen
- [ ] Eine JavaScript-Library
- [ ] Ein HTTP-Protokoll

# Frage 25
Wie greift man auf Query-Parameter zu (z.B. `/search?name=Max`)?
- [ ] `req.params.name`
- [x] `req.query.name`
- [ ] `req.search.name`
- [ ] `req.url.name`

# Frage 26
Was macht `parseInt()` in JavaScript?
- [ ] Konvertiert zu einem String
- [x] Konvertiert einen String zu einer ganzen Zahl
- [ ] Konvertiert zu einem Float
- [ ] Überprüft ob etwas eine Zahl ist

# Frage 27
Welche Array-Methode findet ein Element anhand einer Bedingung?
- [ ] `array.search()`
- [x] `array.find()`
- [ ] `array.get()`
- [ ] `array.locate()`

# Frage 28
Welche Array-Methode findet den Index eines Elements anhand einer Bedingung?
- [ ] `array.find()`
- [x] `array.findIndex()`
- [ ] `array.indexOf()`
- [ ] `array.search()`

# Frage 29
Wie entfernt man ein Element aus einem Array an einem bestimmten Index?
- [ ] `array.remove(index)`
- [x] `array.splice(index, 1)`
- [ ] `array.delete(index)`
- [ ] `array.cut(index)`

# Frage 30
Was ist nodemon?
- [ ] Ein Debugging-Tool
- [x] Ein Tool, das den Server automatisch bei Änderungen neu startet
- [ ] Eine Datenbank
- [ ] Ein Test-Framework

# Frage 31
Wie installiert man nodemon global?
- [ ] `npm install nodemon`
- [x] `npm install -g nodemon`
- [ ] `npm global install nodemon`
- [ ] `node install -global nodemon`

# Frage 32
Wie startet man eine App mit nodemon?
- [ ] `node app.js`
- [x] `nodemon app.js`
- [ ] `npm start nodemon`
- [ ] `nodemon start app.js`

# Frage 33
Was ist Middleware in Express?
- [ ] Eine Datenbank
- [x] Funktionen, die zwischen Request und Response ausgeführt werden
- [ ] Ein Frontend-Framework
- [ ] Eine Art von Route

# Frage 34
Wie ruft man die nächste Middleware-Funktion auf?
- [ ] `continue()`
- [x] `next()`
- [ ] `forward()`
- [ ] `proceed()`

# Frage 35
Was macht `res.status(204).send()`?
- [ ] Sendet den Status-Code 204 mit Daten
- [x] Sendet den Status-Code 204 ohne Inhalt
- [ ] Sendet einen Fehler
- [ ] Leitet um

# Frage 36
Welcher HTTP-Status-Code bedeutet "Not Found"?
- [ ] 400
- [x] 404
- [ ] 500
- [ ] 403

# Frage 37
Welcher HTTP-Status-Code bedeutet "Bad Request"?
- [x] 400
- [ ] 404
- [ ] 500
- [ ] 401

# Frage 38
Wie kann man alle Eigenschaften eines Objekts mit Destructuring extrahieren?
- [ ] `const name, kurs = req.body;`
- [x] `const { name, kurs } = req.body;`
- [ ] `const [name, kurs] = req.body;`
- [ ] `const name = req.body.name, kurs = req.body.kurs;`

# Frage 39
Was ist package.json?
- [ ] Ein JavaScript-File
- [x] Eine Konfigurationsdatei für npm-Projekte
- [ ] Ein Server-Script
- [ ] Eine HTML-Datei

# Frage 40
Welcher Befehl erstellt eine package.json-Datei?
- [ ] `npm create`
- [x] `npm init -y`
- [ ] `npm new package`
- [ ] `npm generate`

# Frage 41
Was bedeutet CORS?
- [ ] Core Object Request System
- [x] Cross-Origin Resource Sharing
- [ ] Client-Origin Response Standard
- [ ] Cross-Operation Resource Security

# Frage 42
Wie installiert man das cors-Paket?
- [ ] `node install cors`
- [x] `npm install cors`
- [ ] `npm get cors`
- [ ] `express install cors`

# Frage 43
Was ist der Unterschied zwischen `req.params` und `req.query`?
- [x] `params` sind URL-Parameter (/user/:id), `query` sind Query-Parameter (?name=Max)
- [ ] `params` sind für POST, `query` für GET
- [ ] Es gibt keinen Unterschied
- [ ] `params` sind sicherer als `query`

# Frage 44
Wie macht man einen DELETE-Request mit fetch()?
- [ ] `fetch(url, {type: 'DELETE'})`
- [x] `fetch(url, {method: 'DELETE'})`
- [ ] `fetch.delete(url)`
- [ ] `fetch(url).delete()`

# Frage 45
Was passiert wenn man `return` vor `res.json()` schreibt?
- [ ] Es funktioniert nicht
- [x] Die Funktion wird beendet und keine weiteren Zeilen ausgeführt
- [ ] Es wird ein Fehler geworfen
- [ ] Es macht keinen Unterschied

# Frage 46
Welche Methode filtert ein Array anhand einer Bedingung?
- [ ] `array.find()`
- [x] `array.filter()`
- [ ] `array.search()`
- [ ] `array.select()`

# Frage 47
Wie konvertiert man einen String zu Kleinbuchstaben?
- [ ] `string.lower()`
- [x] `string.toLowerCase()`
- [ ] `string.small()`
- [ ] `string.downcase()`

# Frage 48
Was macht `array.push()`?
- [ ] Entfernt das letzte Element
- [x] Fügt ein Element am Ende hinzu
- [ ] Fügt ein Element am Anfang hinzu
- [ ] Sortiert das Array

# Frage 49
Wie überprüft man, ob ein String ein bestimmtes Wort enthält?
- [ ] `string.contains()`
- [x] `string.includes()`
- [ ] `string.has()`
- [ ] `string.find()`

# Frage 50
Was ist der Hauptvorteil von Node.js für Webentwickler?
- [ ] Es ist schneller als andere Sprachen
- [x] Man kann JavaScript für Frontend und Backend verwenden
- [ ] Es hat bessere Sicherheit
- [ ] Es benötigt weniger Speicher
