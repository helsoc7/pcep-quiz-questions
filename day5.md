# Frage 1
Was ist der Unterschied zwischen Listen und Tupeln in Python?
- [ ] Listen können nur Zahlen enthalten, Tupel können beliebige Datentypen enthalten
- [ ] Listen sind schneller als Tupel
- [x] Listen sind veränderbar (mutable), Tupel sind unveränderbar (immutable)
- [ ] Tupel können mehr Elemente enthalten als Listen

# Frage 2
Wie erstellt man eine leere Liste in Python?
- [x] `my_list = []` oder `my_list = list()`
- [ ] `my_list = {}`
- [ ] `my_list = ()`
- [ ] `my_list = new List()`

# Frage 3
Was ist die Ausgabe des folgenden Codes?
```python
numbers = [1, 2, 3, 4, 5]
print(numbers[1:4])
```
- [ ] [1, 2, 3, 4]
- [x] [2, 3, 4]
- [ ] [1, 2, 3]
- [ ] [2, 3]

# Frage 4
Wie fügt man ein Element am Ende einer Liste hinzu?
- [ ] `list.insert(element)`
- [x] `list.append(element)`
- [ ] `list.add(element)`
- [ ] `list.extend(element)`

# Frage 5
Was bewirkt die Methode `extend()` bei Listen?
- [ ] Sie vergrößert die Kapazität der Liste
- [ ] Sie fügt ein Element mehrfach hinzu
- [x] Sie fügt alle Elemente eines iterierbaren Objekts zur Liste hinzu
- [ ] Sie erweitert eine Liste um eine bestimmte Anzahl von leeren Elementen

# Frage 6
Was ist die Ausgabe des folgenden Codes?
```python
fruits = ["Apfel", "Banane", "Kirsche"]
fruits.insert(1, "Orange")
print(fruits)
```
- [ ] ["Orange", "Apfel", "Banane", "Kirsche"]
- [x] ["Apfel", "Orange", "Banane", "Kirsche"]
- [ ] ["Apfel", "Banane", "Orange", "Kirsche"]
- [ ] Ein Fehler wird ausgelöst

# Frage 7
Welche Methode entfernt ein Element aus einer Liste und gibt den Wert zurück?
- [ ] `remove()`
- [x] `pop()`
- [ ] `delete()`
- [ ] `extract()`

# Frage 8
Was ist das Ergebnis des folgenden Ausdrucks?
```python
[1, 2, 3] + [4, 5, 6]
```
- [x] [1, 2, 3, 4, 5, 6]
- [ ] [5, 7, 9]
- [ ] [[1, 2, 3], [4, 5, 6]]
- [ ] Ein Fehler wird ausgelöst

# Frage 9
Wie erzeugt man eine Liste mit den Zahlen von 1 bis 10?
- [ ] `range(1, 10)`
- [x] `list(range(1, 11))`
- [ ] `list(range(10))`
- [ ] `[1-10]`

# Frage 10
Was ist die Ausgabe des folgenden Codes?
```python
numbers = [10, 20, 30, 40, 50]
print(numbers[-2])
```
- [ ] -2
- [ ] 20
- [x] 40
- [ ] Ein Fehler wird ausgelöst

# Frage 11
Wie sortiert man eine Liste in aufsteigender Reihenfolge?
- [ ] `sort(list)`
- [x] `list.sort()` oder `sorted(list)`
- [ ] `list.order()`
- [ ] `list.arrange()`

# Frage 12
Was gibt die Methode `count()` einer Liste zurück?
- [ ] Die Länge der Liste
- [ ] Die Position eines Elements in der Liste
- [x] Die Anzahl der Vorkommen eines bestimmten Elements in der Liste
- [ ] Eine neue Liste mit gezählten Elementen

# Frage 13
Wie erstellt man eine Kopie einer Liste?
- [ ] `new_list = list`
- [x] `new_list = list.copy()` oder `new_list = list[:]` oder `new_list = list(list)`
- [ ] `new_list = copy(list)`
- [ ] Listen werden automatisch kopiert, wenn man sie einer neuen Variable zuweist

# Frage 14
Was ist die Ausgabe des folgenden Codes?
```python
numbers = [1, 2, 3, 4, 5]
numbers.reverse()
print(numbers)
```
- [ ] [1, 2, 3, 4, 5]
- [x] [5, 4, 3, 2, 1]
- [ ] None
- [ ] [1, 3, 5]

# Frage 15
Wie erstellt man ein Tupel mit einem einzigen Element?
- [ ] `single_tuple = (1)`
- [x] `single_tuple = (1,)` oder `single_tuple = 1,`
- [ ] `single_tuple = Tuple(1)`
- [ ] `single_tuple = tuple[1]`

# Frage 16
Was ist die Ausgabe des folgenden Codes?
```python
t = (1, 2, 3, 4, 5)
print(t[1:4])
```
- [ ] (1, 2, 3, 4)
- [x] (2, 3, 4)
- [ ] [2, 3, 4]
- [ ] Ein Fehler wird ausgelöst

# Frage 17
Welche der folgenden Operationen ist mit Tupeln NICHT möglich?
- [ ] Slicing (`tuple[1:3]`)
- [ ] Konkatenation (`tuple1 + tuple2`)
- [x] Elemente hinzufügen (`tuple.append(element)`)
- [ ] Länge ermitteln (`len(tuple)`)

# Frage 18
Was bewirkt der folgende Code?
```python
x, y, z = (1, 2, 3)
```
- [ ] Es wird ein Fehler ausgelöst
- [x] Die Variablen x, y und z erhalten die Werte 1, 2 bzw. 3
- [ ] x erhält den Wert (1, 2, 3), y und z bleiben undefiniert
- [ ] Alle drei Variablen erhalten den Wert (1, 2, 3)

# Frage 19
Welche der folgenden Aussagen über Dictionaries ist korrekt?
- [ ] Dictionaries sind immer alphabetisch nach Schlüsseln sortiert
- [ ] Dictionaries können nur Strings als Schlüssel verwenden
- [x] Dictionaries bestehen aus Schlüssel-Wert-Paaren und bieten schnellen Zugriff auf Werte anhand ihrer Schlüssel
- [ ] Dictionaries können nicht verschachtelt werden (kein Dictionary innerhalb eines Dictionary)

# Frage 20
Wie fügt man ein neues Schlüssel-Wert-Paar zu einem bestehenden Dictionary hinzu?
- [x] `dict[new_key] = new_value`
- [ ] `dict.append(new_key, new_value)`
- [ ] `dict.add(new_key, new_value)`
- [ ] `dict.insert(new_key, new_value)`

# Frage 21
Was ist die Ausgabe des folgenden Codes?
```python
person = {"name": "Max", "alter": 30}
print(person.get("beruf", "Nicht angegeben"))
```
- [ ] Ein KeyError wird ausgelöst
- [ ] None
- [x] Nicht angegeben
- [ ] beruf

# Frage 22
Welche Methode entfernt alle Elemente aus einem Dictionary?
- [ ] `remove_all()`
- [ ] `delete()`
- [x] `clear()`
- [ ] `reset()`

# Frage 23
Was ist die Ausgabe des folgenden Codes?
```python
colors = {"rot": "#FF0000", "grün": "#00FF00", "blau": "#0000FF"}
for item in colors:
    print(item)
```
- [ ] #FF0000, #00FF00, #0000FF
- [x] rot, grün, blau
- [ ] rot: #FF0000, grün: #00FF00, blau: #0000FF
- [ ] Ein Fehler wird ausgelöst

# Frage 24
Wie greift man auf alle Schlüssel eines Dictionaries zu?
- [ ] `dict.keys`
- [x] `dict.keys()`
- [ ] `dict.get_keys()`
- [ ] `keys(dict)`

# Frage 25
Was ist die Ausgabe des folgenden Codes?
```python
d = {"a": 1, "b": 2}
d.update({"b": 3, "c": 4})
print(d)
```
- [ ] {"a": 1, "b": 2, "c": 4}
- [x] {"a": 1, "b": 3, "c": 4}
- [ ] {"a": 1, "b": 2, "b": 3, "c": 4}
- [ ] Ein Fehler wird ausgelöst

# Frage 26
Wie erstellt man ein leeres Set in Python?
- [ ] `my_set = {}`
- [x] `my_set = set()`
- [ ] `my_set = Set()`
- [ ] `my_set = new Set()`

# Frage 27
Was ist die Ausgabe des folgenden Codes?
```python
set1 = {1, 2, 3, 4, 5}
set2 = {4, 5, 6, 7, 8}
print(set1 | set2)
```
- [ ] {1, 2, 3, 4, 5, 4, 5, 6, 7, 8}
- [x] {1, 2, 3, 4, 5, 6, 7, 8}
- [ ] {4, 5}
- [ ] Ein Fehler wird ausgelöst

# Frage 28
Welche Operation entspricht der Schnittmenge zweier Sets?
- [ ] `set1 | set2`
- [x] `set1 & set2`
- [ ] `set1 - set2`
- [ ] `set1 ^ set2`

# Frage 29
Was ist das Ergebnis des folgenden Ausdrucks?
```python
{1, 2, 3} - {2, 3, 4}
```
- [x] {1}
- [ ] {4}
- [ ] {1, 4}
- [ ] {1, 2, 3, 4}

# Frage 30
Was passiert, wenn man versucht, ein bereits vorhandenes Element zu einem Set hinzuzufügen?
- [ ] Es wird ein Fehler ausgelöst
- [ ] Das Element wird ein zweites Mal hinzugefügt
- [x] Das Element wird ignoriert, das Set bleibt unverändert
- [ ] Das Element ersetzt das vorhandene Element

# Frage 31
Wie überprüft man, ob ein Element in einer Liste vorhanden ist?
- [x] `element in list`
- [ ] `list.contains(element)`
- [ ] `list.has(element)`
- [ ] `element.in(list)`

# Frage 32
Was ist die Zeitkomplexität für die Operation `element in list` bei einer Liste?
- [ ] O(1)
- [x] O(n)
- [ ] O(log n)
- [ ] O(n²)

# Frage 33
Was ist die Zeitkomplexität für die Operation `element in set` bei einem Set?
- [x] O(1)
- [ ] O(n)
- [ ] O(log n)
- [ ] O(n²)

# Frage 34
Welcher Code erzeugt eine Liste mit den Quadratzahlen der Zahlen von 1 bis 5?
- [ ] `[x² for x in range(1, 6)]`
- [x] `[x**2 for x in range(1, 6)]`
- [ ] `[x*x for x in range(1, 6)]`
- [ ] Alle obigen Antworten sind korrekt

# Frage 35
Was ist die Ausgabe des folgenden Codes?
```python
numbers = [1, 2, 3, 4, 5]
doubled = [x * 2 for x in numbers if x % 2 == 0]
print(doubled)
```
- [ ] [2, 4, 6, 8, 10]
- [x] [4, 8]
- [ ] [2, 6, 10]
- [ ] Ein Fehler wird ausgelöst

# Frage 36
Wie entfernt man Duplikate aus einer Liste?
- [ ] `list.remove_duplicates()`
- [ ] `remove_duplicates(list)`
- [x] `list(set(my_list))`
- [ ] `list.unique()`

# Frage 37
Was ist die Ausgabe des folgenden Codes?
```python
a = [1, 2, 3]
b = a
b.append(4)
print(a)
```
- [ ] [1, 2, 3]
- [x] [1, 2, 3, 4]
- [ ] [1, 2, 3, [4]]
- [ ] Ein Fehler wird ausgelöst

# Frage 38
Was ist die Ausgabe des folgenden Codes?
```python
nested = ([1, 2], [3, 4])
nested[0][1] = 5
print(nested)
```
- [ ] Ein Fehler wird ausgelöst, da Tupel unveränderbar sind
- [x] ([1, 5], [3, 4])
- [ ] ([1, 2], [3, 4])
- [ ] [[1, 5], [3, 4]]

# Frage 39
Welche der folgenden Aussagen über List Comprehensions ist korrekt?
- [ ] List Comprehensions können nur mit Listen arbeiten, nicht mit anderen iterierbaren Objekten
- [ ] List Comprehensions sind immer langsamer als klassische for-Schleifen
- [x] List Comprehensions bieten eine kompakte Syntax zum Erstellen von Listen basierend auf bestehenden Listen
- [ ] List Comprehensions können keine bedingten Anweisungen (if) enthalten

# Frage 40
Was ist der Wert von `result` nach Ausführung des folgenden Codes?
```python
result = [i for i in range(10) if i % 2 == 0 if i % 3 == 0]
```
- [ ] [0, 2, 4, 6, 8]
- [ ] [0, 3, 6, 9]
- [x] [0, 6]
- [ ] [2, 4, 8]

# Frage 41
Wie kann man auf das letzte Element einer Liste zugreifen?
- [ ] `list.last()`
- [x] `list[-1]`
- [ ] `list[len(list)]`
- [ ] `list.end()`

# Frage 42
Was ist die Ausgabe des folgenden Codes?
```python
a = {}
print(type(a))
```
- [ ] <class 'set'>
- [x] <class 'dict'>
- [ ] <class 'list'>
- [ ] <class 'tuple'>

# Frage 43
Welche der folgenden Operationen ist nicht möglich mit Strings in Python?
- [ ] Konkatenation mit dem `+`-Operator
- [ ] Slicing wie bei Listen
- [x] Ändern einzelner Zeichen (z.B. `s[0] = 'X'`)
- [ ] Iteration mit einer for-Schleife

# Frage 44
Was ist die Ausgabe des folgenden Codes?
```python
a = {1, 2, 3}
b = {3, 4, 5}
print(a ^ b)
```
- [ ] {1, 2, 4, 5}
- [x] {1, 2, 4, 5}
- [ ] {3}
- [ ] {1, 2, 3, 4, 5}

# Frage 45
Welche Methode verwendet man, um alle Elemente eines Sets zu löschen?
- [ ] `remove_all()`
- [ ] `delete()`
- [x] `clear()`
- [ ] `empty()`

# Frage 46
Was ist die Ausgabe des folgenden Codes?
```python
tuple1 = (1, 2, 3)
tuple2 = (4, 5, 6)
print(tuple1 + tuple2)
```
- [ ] Es wird ein Fehler ausgelöst
- [x] (1, 2, 3, 4, 5, 6)
- [ ] ((1, 2, 3), (4, 5, 6))
- [ ] [1, 2, 3, 4, 5, 6]

# Frage 47
Wie viele Elemente enthält das Set nach Ausführung des folgenden Codes?
```python
s = set([1, 2, 3, 2, 3, 4, 5, 4, 3, 2, 1])
```
- [ ] 11
- [ ] 3
- [x] 5
- [ ] Ein Fehler wird ausgelöst

# Frage 48
Welche der folgenden Datenstrukturen ist am besten geeignet, um eine Sammlung eindeutiger Elemente zu speichern?
- [ ] Liste
- [ ] Tupel
- [ ] Dictionary
- [x] Set

# Frage 49
Was ist das Ergebnis des folgenden Ausdrucks?
```python
"Python"[1:4]
```
- [ ] "Python"
- [ ] "Pyt"
- [x] "yth"
- [ ] "ytho"

# Frage 50
Welche Datenstruktur ist am besten geeignet, um die Häufigkeit des Vorkommens von Wörtern in einem Text zu speichern?
- [ ] Liste
- [ ] Tupel
- [x] Dictionary
- [ ] Set
