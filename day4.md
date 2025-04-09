# Frage 1
Wann ist eine while-Schleife einer for-Schleife vorzuziehen?
- [ ] Wenn die Anzahl der Durchläufe vor Beginn der Schleife bekannt ist
- [x] Wenn die Anzahl der Durchläufe vor Beginn der Schleife nicht bekannt ist
- [ ] When maximal 5 Durchläufe benötigt werden
- [ ] Wenn über eine Liste iteriert werden soll

# Frage 2
Was ist die Ausgabe des folgenden Codes?
```python
count = 1
while count < 5:
    print(count, end=" ")
    count += 1
```
- [ ] 1 2 3 4 5
- [x] 1 2 3 4
- [ ] 2 3 4 5
- [ ] 1 3 5 7

# Frage 3
Was passiert, wenn die Bedingung in einer while-Schleife niemals False wird?
- [ ] Die Schleife wird automatisch nach 1000 Durchläufen beendet
- [ ] Python wirft einen TimeoutError
- [x] Es entsteht eine Endlosschleife
- [ ] Die Schleife wird gar nicht erst ausgeführt

# Frage 4
Was ist die Ausgabe des folgenden Codes?
```python
i = 10
while i > 0:
    i -= 2
    if i == 4:
        continue
    print(i, end=" ")
```
- [ ] 8 6 4 2 0
- [ ] 8 6 2 0 -2
- [x] 8 6 2 0
- [ ] 10 8 6 2 0

# Frage 5
Was bewirkt die break-Anweisung in einer Schleife?
- [x] Sie beendet die Schleife sofort
- [ ] Sie springt zur nächsten Iteration der Schleife
- [ ] Sie pausiert die Schleife
- [ ] Sie setzt die Schleifenvariable auf den Anfangswert zurück

# Frage 6
Was bewirkt die continue-Anweisung in einer Schleife?
- [ ] Sie beendet die Schleife sofort
- [x] Sie springt zur nächsten Iteration der Schleife
- [ ] Sie pausiert die Schleife für eine Sekunde
- [ ] Sie inkrementiert die Schleifenvariable

# Frage 7
Was ist die Ausgabe des folgenden Codes?
```python
for i in range(5):
    if i == 3:
        break
    print(i, end=" ")
```
- [ ] 0 1 2 3 4
- [x] 0 1 2
- [ ] 0 1 2 4
- [ ] 3

# Frage 8
Wie oft wird der Körper der folgenden Schleife ausgeführt?
```python
for i in range(2, 10, 2):
    print(i)
```
- [ ] 10 mal
- [ ] 8 mal
- [x] 4 mal
- [ ] 5 mal

# Frage 9
Was ist die Ausgabe des folgenden Codes?
```python
for i in range(3):
    for j in range(2):
        print(f"{i},{j}", end=" ")
```
- [ ] 0,0 0,1 0,2 1,0 1,1 1,2 2,0 2,1 2,2
- [x] 0,0 0,1 1,0 1,1 2,0 2,1
- [ ] 0,0 1,1 2,2
- [ ] 0,0 0,1 0,2 1,0 1,1 1,2

# Frage 10
Was bedeutet der dritte Parameter in range(1, 10, 2)?
- [ ] Die Anzahl der Iterationen
- [ ] Der Endwert (inklusive)
- [x] Die Schrittweite
- [ ] Der Startwert

# Frage 11
Was ist die Ausgabe des folgenden Codes?
```python
for letter in "Python":
    if letter == "h":
        continue
    print(letter, end="")
```
- [ ] Python
- [x] Pyton
- [ ] Pytho
- [ ] ython

# Frage 12
Welche der folgenden Optionen ist die effizienteste Methode, um zu prüfen, ob eine Zahl in einer großen Liste enthalten ist?
- [ ] Eine for-Schleife verwenden und jedes Element vergleichen
- [ ] Eine while-Schleife verwenden und jedes Element vergleichen
- [x] Die Liste in ein Set umwandeln und den in-Operator verwenden
- [ ] Eine verschachtelte Schleife verwenden

# Frage 13
Was ist die Ausgabe des folgenden Codes?
```python
count = 0
while count < 5:
    count += 1
else:
    print(f"Schleife beendet bei count={count}")
```
- [ ] Schleife beendet bei count=0
- [ ] Schleife beendet bei count=4
- [x] Schleife beendet bei count=5
- [ ] Die Schleife ist eine Endlosschleife, es gibt keine Ausgabe

# Frage 14
Wann wird der else-Block in einer while-Schleife NICHT ausgeführt?
- [ ] Wenn die Schleife gar nicht ausgeführt wird
- [x] Wenn die Schleife mit break beendet wird
- [ ] Wenn die Schleife mit continue fortgesetzt wird
- [ ] Wenn die Schleife normal beendet wird

# Frage 15
Was ist die Ausgabe des folgenden Codes?
```python
for i in range(1, 5):
    if i == 3:
        continue
    print(i, end=" ")
else:
    print("Ende")
```
- [ ] 1 2 3 4 Ende
- [x] 1 2 4 Ende
- [ ] 1 2 4
- [ ] 1 2 Ende

# Frage 16
Was bewirkt der folgende Code?
```python
while True:
    response = input("Möchtest du fortfahren? (j/n): ")
    if response.lower() == 'n':
        break
```
- [ ] Der Code führt zu einem Syntaxfehler
- [ ] Der Code wird nur einmal ausgeführt
- [x] Der Code fragt wiederholt nach Eingabe, bis der Benutzer 'n' eingibt
- [ ] Der Code wird genau dreimal ausgeführt

# Frage 17
Welche der folgenden Aussagen zur for-Schleife in Python ist korrekt?
- [ ] Eine for-Schleife kann nur mit numerischen Werten arbeiten
- [ ] Eine for-Schleife kann nicht vorzeitig beendet werden
- [x] Eine for-Schleife kann über jedes iterierbare Objekt laufen
- [ ] Eine for-Schleife muss mindestens einmal ausgeführt werden

# Frage 18
Was ist die Ausgabe des folgenden Codes?
```python
text = "Python"
for i, char in enumerate(text):
    print(f"{i}:{char}", end=" ")
```
- [ ] P:0 y:1 t:2 h:3 o:4 n:5
- [x] 0:P 1:y 2:t 3:h 4:o 5:n
- [ ] 1:P 2:y 3:t 4:h 5:o 6:n
- [ ] P y t h o n

# Frage 19
Was ist der Unterschied zwischen `range(5)` und `range(1, 6)`?
- [ ] Es gibt keinen Unterschied, beide erzeugen die Werte 1, 2, 3, 4, 5
- [x] `range(5)` erzeugt 0, 1, 2, 3, 4, während `range(1, 6)` erzeugt 1, 2, 3, 4, 5
- [ ] `range(5)` erzeugt 1, 2, 3, 4, 5, während `range(1, 6)` erzeugt 1, 2, 3, 4, 5, 6
- [ ] `range(5)` erzeugt 0, 1, 2, 3, 4, 5, während `range(1, 6)` erzeugt 1, 2, 3, 4, 5

# Frage 20
Was ist die Zeitkomplexität einer einfachen Iteration über eine Liste mit n Elementen?
- [x] O(n)
- [ ] O(log n)
- [ ] O(n²)
- [ ] O(1)

# Frage 21
Was ist die Ausgabe des folgenden Codes?
```python
for i in range(3):
    print(i, end=" ")
    for j in range(2):
        print(j, end=" ")
    print()
```
- [ ] 0 1 2 0 1
- [ ] 0 0 1 1 2 2
- [x] 0 0 1 
     1 0 1 
     2 0 1
- [ ] 0 0 
     0 1 
     1 0 
     1 1 
     2 0 
     2 1

# Frage 22
Wie kann man in Python rückwärts von 10 bis 1 zählen?
- [ ] `for i in range(10, 1)`
- [ ] `for i in range(10, 1, 1)`
- [x] `for i in range(10, 0, -1)`
- [ ] `for i in range(10, 0)`

# Frage 23
Was ist die Ausgabe des folgenden Codes?
```python
a = [1, 2, 3]
for i in a:
    i = i * 2
print(a)
```
- [x] [1, 2, 3]
- [ ] [2, 4, 6]
- [ ] []
- [ ] Ein Fehler wird ausgegeben

# Frage 24
Wie oft wird die innere Schleife im folgenden Code ausgeführt?
```python
for i in range(3):
    for j in range(4):
        print(i, j)
```
- [ ] 3 mal
- [ ] 4 mal
- [ ] 7 mal
- [x] 12 mal

# Frage 25
Was ist ein häufiger Grund für unbeabsichtigte Endlosschleifen?
- [ ] Die Verwendung von `break`
- [ ] Die Verwendung von `continue`
- [x] Das Vergessen, die Laufvariable zu aktualisieren
- [ ] Die Verwendung von verschachtelten Schleifen

# Frage 26
Welche der folgenden Aussagen über die Verwendung von `else` mit Schleifen ist korrekt?
- [ ] Der `else`-Block wird nur ausgeführt, wenn die Schleife mit `break` beendet wird
- [x] Der `else`-Block wird nur ausgeführt, wenn die Schleife ohne `break` beendet wird
- [ ] Der `else`-Block wird nach jeder Iteration der Schleife ausgeführt
- [ ] Der `else`-Block wird nur ausgeführt, wenn die Schleifenbedingung von Anfang an `False` ist

# Frage 27
Was ist die Ausgabe des folgenden Codes?
```python
a = 0
while a < 5:
    a += 1
    if a == 3:
        continue
    print(a, end=" ")
```
- [ ] 1 2 3 4 5
- [x] 1 2 4 5
- [ ] 1 2 4
- [ ] 0 1 2 4 5

# Frage 28
Welche der folgenden Optionen zeigt korrekt, wie man über die Elemente eines Dictionaries iteriert?
- [ ] `for item in dictionary:`
- [ ] `for key, value in dictionary:`
- [x] `for key, value in dictionary.items():`
- [ ] `for item.key, item.value in dictionary:`

# Frage 29
Wie kann man mit der `enumerate()`-Funktion bei 1 statt bei 0 zu zählen beginnen?
- [ ] `for i, item in enumerate(items, start=1):`
- [x] `for i, item in enumerate(items, 1):`
- [ ] `for i, item in enumerate(1, items):`
- [ ] `for i, item in enumerate(items) + 1:`

# Frage 30
Was ist die Zeitkomplexität der folgenden Schleife?
```python
for i in range(n):
    for j in range(n):
        print(i, j)
```
- [ ] O(n)
- [x] O(n²)
- [ ] O(log n)
- [ ] O(2n)

# Frage 31
Was ist die Ausgabe des folgenden Codes?
```python
for num in range(10, 0, -2):
    print(num, end=" ")
```
- [ ] 10 8 6 4 2 0
- [x] 10 8 6 4 2
- [ ] 8 6 4 2 0
- [ ] 9 7 5 3 1

# Frage 32
Welche Aussage beschreibt am besten den Unterschied zwischen `break` und `continue`?
- [ ] `break` beendet nur die aktuelle Iteration, `continue` beendet die gesamte Schleife
- [x] `break` beendet die gesamte Schleife, `continue` überspringt die aktuelle Iteration
- [ ] `break` funktioniert nur in for-Schleifen, `continue` nur in while-Schleifen
- [ ] `break` springt zum Anfang der Schleife, `continue` springt zum Ende der Schleife

# Frage 33
Was passiert, wenn die Bedingung einer while-Schleife bereits beim ersten Durchlauf False ist?
- [ ] Die Schleife wird einmal ausgeführt
- [x] Die Schleife wird gar nicht ausgeführt
- [ ] Es wird ein ValueError ausgelöst
- [ ] Die Schleife wird unendlich oft ausgeführt

# Frage 34
Wie viele Werte erzeugt der Aufruf `range(5, 10)`?
- [ ] 4
- [x] 5
- [ ] 6
- [ ] 10

# Frage 35
Was ist die Ausgabe des folgenden Codes?
```python
s = "Python"
for char in s[::-1]:
    print(char, end="")
```
- [ ] Python
- [x] nohtyP
- [ ] P y t h o n
- [ ] n o h t y P

# Frage 36
Welche der folgenden Schleifen ist effizienter zum Aufsummieren aller Elemente einer Liste?
- [ ] Eine while-Schleife mit einem Index
- [ ] Eine for-Schleife mit enumerate()
- [x] Eine for-Schleife über die Liste
- [ ] Alle haben die gleiche Effizienz

# Frage 37
Was ist der Wert von `result` nach Ausführung des folgenden Codes?
```python
numbers = [1, 2, 3, 4, 5]
result = 0
for num in numbers:
    if num % 2 == 0:
        result += num
```
- [ ] 15
- [x] 6
- [ ] 9
- [ ] 0

# Frage 38
Welcher Mechanismus kann verwendet werden, um eine Endlosschleife sicher zu implementieren?
- [ ] Die Verwendung von `while 1 == 1:`
- [x] Die Verwendung von `while True:` mit einer `break`-Bedingung
- [ ] Die Verwendung einer for-Schleife ohne Aktualisierung der Laufvariable
- [ ] Die Verwendung der `infinity`-Funktion

# Frage 39
Was ist der Unterschied zwischen `range(0, 5)` und `range(0, 5, 1)`?
- [x] Es gibt keinen funktionalen Unterschied
- [ ] `range(0, 5)` inkludiert die 5, während `range(0, 5, 1)` bei 4 endet
- [ ] `range(0, 5)` erzeugt genau 5 Werte, während `range(0, 5, 1)` 6 Werte erzeugt
- [ ] `range(0, 5, 1)` kann nur in for-Schleifen verwendet werden

# Frage 40
Welche Art von Datenstrukturen kann mit einer for-Schleife durchlaufen werden?
- [ ] Nur Listen und Tupel
- [ ] Nur Strings und Listen
- [ ] Nur iterierbare Objekte mit numerischen Indizes
- [x] Alle iterierbaren Objekte (Listen, Tupel, Strings, Dictionaries, Sets etc.)

# Frage 41
Was ist die Ausgabe des folgenden Codes?
```python
d = {"a": 1, "b": 2, "c": 3}
for k in d:
    print(k, end=" ")
```
- [ ] 1 2 3
- [x] a b c
- [ ] a:1 b:2 c:3
- [ ] a,1 b,2 c,3

# Frage 42
Wie kann man eine for-Schleife implementieren, die jedes zweite Element einer Liste verarbeitet?
- [ ] `for item in list[::2]:`
- [x] `for item in list[::2]:`
- [ ] `for item in list[1::2]:`
- [ ] `for i in range(len(list)): if i % 2 == 0: item = list[i]`

# Frage 43
Was ist die Ausgabe des folgenden Codes?
```python
total = 0
for i in range(1, 6):
    if i % 2 == 0:
        continue
    total += i
print(total)
```
- [ ] 15
- [x] 9
- [ ] 6
- [ ] 10

# Frage 44
In einer verschachtelten Schleife, auf welche Schleife wirkt sich ein `break`-Statement aus?
- [x] Auf die unmittelbar umgebende Schleife
- [ ] Auf alle umgebenden Schleifen
- [ ] Auf die äußerste Schleife
- [ ] Es hängt von der Art der Schleife ab (for oder while)

# Frage 45
Was ist die Ausgabe des folgenden Codes?
```python
def is_prime(n):
    if n <= 1:
        return False
    for i in range(2, int(n ** 0.5) + 1):
        if n % i == 0:
            return False
    return True

for num in range(10, 20):
    if is_prime(num):
        print(num, end=" ")
```
- [ ] 11 13 17 19 23 29
- [x] 11 13 17 19
- [ ] 10 11 13 17 19
- [ ] Es gibt keine Ausgabe

# Frage 46
Welche der folgenden Optionen zum Durchlaufen eines Dictionary gibt sowohl Schlüssel als auch Werte zurück?
- [ ] `for item in dict:`
- [ ] `for key, dict[key] in dict:`
- [x] `for key, value in dict.items():`
- [ ] `for key in dict.keys(): value = dict[key]`

# Frage 47
Was wird durch den folgenden Code berechnet?
```python
n = 5
result = 1
for i in range(1, n + 1):
    result *= i
print(result)
```
- [ ] Die Summe der Zahlen von 1 bis n
- [x] Die Fakultät von n (n!)
- [ ] n hoch n (n^n)
- [ ] Die n-te Primzahl

# Frage 48
Wie kann man die Laufzeit einer Schleife messen?
- [ ] Durch Zählen der Schleifendurchläufe
- [x] Durch Verwendung des `time`-Moduls und Messung vor und nach der Schleife
- [ ] Durch Analysieren des Bytecodes
- [ ] Durch Verwenden der eingebauten `measure()`-Funktion

# Frage 49
Was ist die Zeitkomplexität der folgenden Operation?
```python
if element in large_list:  # large_list hat n Elemente
    print("Element gefunden")
```
- [ ] O(1)
- [x] O(n)
- [ ] O(log n)
- [ ] O(n²)

# Frage 50
Welche der folgenden Methoden ist am effizientesten, um zu prüfen, ob ein Element in einer großen Sammlung von Daten vorhanden ist?
- [ ] Verwendung einer for-Schleife und Vergleich jedes Elements
- [ ] Verwendung der list.index()-Methode und Abfangen einer möglichen ValueError
- [x] Umwandlung der Sammlung in ein Set und Verwendung des in-Operators
- [ ] Sortieren der Sammlung und Verwendung einer binären Suche
