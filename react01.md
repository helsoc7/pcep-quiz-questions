# React Grundlagen - 50 Quiz-Fragen

# Frage 1
Was ist eine React-Komponente?
- [ ] Eine CSS-Datei
- [x] Ein wiederverwendbarer Baustein für die UI
- [ ] Eine HTML-Datei
- [ ] Ein JavaScript-Array

# Frage 2
Wie wird eine React-Komponente definiert?
- [ ] Als HTML-Tag
- [x] Als JavaScript-Funktion, die JSX zurückgibt
- [ ] Als CSS-Klasse
- [ ] Als JSON-Objekt

# Frage 3
Was ist JSX?
- [ ] Eine neue Programmiersprache
- [x] JavaScript-Syntax, die HTML-ähnlich aussieht
- [ ] Ein CSS-Framework
- [ ] Eine Datenbank

# Frage 4
Welcher HTML-Attribut-Name wird in JSX anders geschrieben?
- [ ] `id` → `reactId`
- [x] `class` → `className`
- [ ] `href` → `link`
- [ ] `src` → `source`

# Frage 5
Was ist State in React?
- [ ] Die CSS-Styles einer Komponente
- [x] Das "Gedächtnis" einer Komponente für veränderliche Daten
- [ ] Die HTML-Struktur einer Komponente
- [ ] Eine externe API

# Frage 6
Wie importiert man useState?
- [ ] `const useState = require('react');`
- [x] `import { useState } from 'react';`
- [ ] `import useState from 'react';`
- [ ] `const { useState } = react();`

# Frage 7
Wie wird useState verwendet?
- [ ] `const [value] = useState(0);`
- [x] `const [value, setValue] = useState(0);`
- [ ] `const value = useState(0);`
- [ ] `useState(value, 0);`

# Frage 8
Was passiert, wenn State geändert wird?
- [ ] Die Seite wird neu geladen
- [x] Die Komponente wird automatisch neu gerendert
- [ ] Nichts passiert
- [ ] Ein Fehler wird geworfen

# Frage 9
Wie erstellt man ein neues Vite-React-Projekt?
- [ ] `npm create react-app`
- [x] `npm create vite@latest`
- [ ] `npm install react`
- [ ] `npm new react`

# Frage 10
Welcher Befehl startet den Development-Server?
- [ ] `npm start`
- [x] `npm run dev`
- [ ] `npm build`
- [ ] `npm test`

# Frage 11
Was sind Props in React?
- [ ] CSS-Eigenschaften
- [x] Daten, die von Eltern- zu Kind-Komponente weitergegeben werden
- [ ] HTML-Attribute
- [ ] JavaScript-Variablen

# Frage 12
Wie werden Props in einer Komponente empfangen?
- [ ] `function MyComponent() { const props = getProps(); }`
- [x] `function MyComponent({ name, age }) { ... }`
- [ ] `function MyComponent() { return props.name; }`
- [ ] `function MyComponent(name, age) { ... }`

# Frage 13
Können Kind-Komponenten ihre Props direkt ändern?
- [x] Nein, Props sind schreibgeschützt
- [ ] Ja, Props können überall geändert werden
- [ ] Nur mit setState
- [ ] Nur in funktionalen Komponenten

# Frage 14
Welche Array-Methode wird verwendet, um Listen in React zu rendern?
- [ ] `forEach()`
- [x] `map()`
- [ ] `filter()`
- [ ] `reduce()`

# Frage 15
Was ist der key-Prop bei Listen?
- [ ] Ein CSS-Stil
- [x] Ein eindeutiger Identifikator für React's Rendering-Optimierung
- [ ] Eine Validierungsmethode
- [ ] Ein Event-Handler

# Frage 16
Warum ist der key-Prop wichtig?
- [ ] Für CSS-Styling
- [x] Damit React versteht, welche Listenelemente sich geändert haben
- [ ] Für API-Calls
- [ ] Für Error Handling

# Frage 17
Was ist useEffect?
- [ ] Ein CSS-Effekt
- [x] Ein Hook für Seiteneffekte wie API-Calls
- [ ] Ein Event-Handler
- [ ] Eine Validierungsmethode

# Frage 18
Wann läuft useEffect mit leerem Dependency-Array?
- [ ] Nach jedem Render
- [x] Nur einmal nach dem ersten Render
- [ ] Nie
- [ ] Bei jedem State-Update

# Frage 19
Wie macht man einen API-Call in React?
- [ ] Mit jQuery
- [x] Mit fetch() in useEffect
- [ ] Mit innerHTML
- [ ] Mit localStorage

# Frage 20
Was ist "Lifting State Up"?
- [ ] State in localStorage speichern
- [x] State von Kind- in Eltern-Komponente verschieben
- [ ] State löschen
- [ ] State kopieren

# Frage 21
Warum ist "Lifting State Up" notwendig?
- [ ] Für bessere Performance
- [x] Damit mehrere Komponenten den gleichen State teilen können
- [ ] Für Sicherheit
- [ ] Für CSS-Styling

# Frage 22
Wie gibt eine Eltern-Komponente eine Funktion an ein Kind weiter?
- [ ] Mit return
- [x] Als Prop
- [ ] Mit useState
- [ ] Mit localStorage

# Frage 23
Was macht `todos.filter(todo => todo.id !== todoId)`?
- [x] Es gibt ein neues Array zurück ohne das Todo mit der gegebenen ID
- [ ] Es löscht das Todo direkt aus dem Original-Array
- [ ] Es sortiert alle Todos alphabetisch
- [ ] Es zählt die Todos

# Frage 24
Was macht `setTodos([savedTodo, ...todos])`?
- [ ] Es überschreibt alle Todos mit einem leeren Array
- [x] Es fügt ein neues Todo vorne in die bestehende Liste ein
- [ ] Es löscht alle Todos aus dem State
- [ ] Es sortiert die Todos

# Frage 25
Was ist ein Controlled Component?
- [ ] Eine Komponente mit CSS
- [x] Ein Input-Element, dessen Wert von React kontrolliert wird
- [ ] Eine Komponente mit Props
- [ ] Eine Komponente mit State

# Frage 26
Wie erstellt man ein Controlled Input?
- [ ] `<input />`
- [x] `<input value={inputValue} onChange={handleChange} />`
- [ ] `<input defaultValue="text" />`
- [ ] `<input ref={inputRef} />`

# Frage 27
Was macht `event.preventDefault()`?
- [ ] Verhindert State-Updates
- [x] Verhindert das Standard-Browser-Verhalten
- [ ] Verhindert Component-Rendering
- [ ] Verhindert API-Calls

# Frage 28
Welcher Event-Handler wird für Button-Klicks verwendet?
- [ ] `onPress`
- [x] `onClick`
- [ ] `onTap`
- [ ] `onSelect`

# Frage 29
Welcher Event-Handler wird für Input-Änderungen verwendet?
- [ ] `onInput`
- [x] `onChange`
- [ ] `onType`
- [ ] `onEdit`

# Frage 30
Welcher Event-Handler wird für Formular-Absendung verwendet?
- [ ] `onSend`
- [x] `onSubmit`
- [ ] `onPost`
- [ ] `onSave`

# Frage 31
Was passiert, wenn State direkt verändert wird ohne setState?
- [ ] Die Komponente wird sofort aktualisiert
- [x] React erkennt keine Änderung und rendert nicht neu
- [ ] Ein Fehler wird geworfen
- [ ] Die App stürzt ab

# Frage 32
Wie bindet man Bootstrap in ein Vite-Projekt ein?
- [ ] `npm install jquery`
- [x] CDN-Link in HTML oder `npm install bootstrap`
- [ ] Nur mit CSS-Dateien
- [ ] Bootstrap funktioniert nicht mit Vite

# Frage 33
Was ist Props-Drilling?
- [ ] Eine Debugging-Methode
- [x] Das Durchreichen von Props durch mehrere Komponenten-Ebenen
- [ ] Eine Performance-Optimierung
- [ ] Ein Fehler in React

# Frage 34
Welche HTTP-Methode wird zum Erstellen neuer Daten verwendet?
- [ ] GET
- [x] POST
- [ ] PUT
- [ ] DELETE

# Frage 35
Welche HTTP-Methode wird zum Aktualisieren von Daten verwendet?
- [ ] GET
- [ ] POST
- [x] PUT
- [ ] DELETE

# Frage 36
Welche HTTP-Methode wird zum Löschen von Daten verwendet?
- [ ] GET
- [ ] POST
- [ ] PUT
- [x] DELETE

# Frage 37
Was ist ein Loading-State?
- [ ] Ein Fehler-Zustand
- [x] Ein State, der anzeigt, dass Daten geladen werden
- [ ] Ein leerer State
- [ ] Ein State für fertige Daten

# Frage 38
Wie behandelt man Fehler bei API-Calls?
- [ ] Mit if-Statements
- [x] Mit try/catch Blöcken
- [ ] Mit console.log
- [ ] Fehler können nicht behandelt werden

# Frage 39
Was ist der Spread-Operator `...`?
- [ ] Ein CSS-Selector
- [x] Eine JavaScript-Syntax zum "Ausbreiten" von Arrays/Objekten
- [ ] Ein React-Hook
- [ ] Ein HTML-Attribut

# Frage 40
Wie fügt man ein Element am Anfang eines Arrays hinzu?
- [ ] `array.push(newItem)`
- [x] `[newItem, ...array]`
- [ ] `array.unshift(newItem)`
- [ ] `array.concat(newItem)`

# Frage 41
Was ist besser für kleine statische Projekte?
- [x] Vanilla JavaScript
- [ ] React
- [ ] Angular
- [ ] Vue

# Frage 42
Wann sollte man React verwenden?
- [ ] Für statische Webseiten
- [x] Für interaktive Apps mit viel State-Management
- [ ] Für einfache HTML-Seiten
- [ ] Nur für große Unternehmen

# Frage 43
Wie kann man einen Event-Handler mit Parametern aufrufen?
- [ ] `onClick={handleClick(id)}`
- [x] `onClick={() => handleClick(id)}`
- [ ] `onClick={handleClick, id}`
- [ ] `onClick={handleClick.bind(id)}`

# Frage 44
Was ist async/await in JavaScript?
- [ ] Ein React-Hook
- [x] Eine Methode für asynchrone Programmierung
- [ ] Ein CSS-Feature
- [ ] Ein HTML-Attribut

# Frage 45
Warum verwendet man async/await bei API-Calls?
- [ ] Für bessere Performance
- [x] Weil API-Calls asynchron sind und Zeit brauchen
- [ ] Für Sicherheit
- [ ] Für CSS-Styling

# Frage 46
Was macht das Dependency-Array in useEffect?
- [ ] Es definiert Props
- [x] Es kontrolliert, wann der Effekt ausgeführt wird
- [ ] Es definiert State
- [ ] Es ist nur Dekoration

# Frage 47
Was passiert bei useEffect ohne Dependency-Array?
- [x] Der Effekt läuft nach jedem Render
- [ ] Der Effekt läuft nie
- [ ] Der Effekt läuft nur einmal
- [ ] Es gibt einen Fehler

# Frage 48
Wie kann man eine Komponente bedingt rendern?
- [ ] `if (condition) <Component />`
- [x] `{condition && <Component />}`
- [ ] `<Component if={condition} />`
- [ ] `condition ? <Component /> : null`

# Frage 49
Was ist der Unterschied zwischen funktionalen und Klassen-Komponenten?
- [ ] Funktionale Komponenten sind langsamer
- [x] Funktionale Komponenten verwenden Hooks, Klassen-Komponenten nicht
- [ ] Es gibt keinen Unterschied
- [ ] Klassen-Komponenten sind moderner

# Frage 50
Welches Tool wird empfohlen für React Developer Tools?
- [ ] Console.log
- [x] Browser-Extension "React Developer Tools"
- [ ] Visual Studio Code
- [ ] Node.js Debugger
