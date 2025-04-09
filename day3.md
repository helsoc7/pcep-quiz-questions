# Frage 1
Was bewirkt der Parameter `sep` in der `print()`-Funktion?
- [ ] Er definiert das Trennzeichen zwischen aufeinanderfolgenden `print()`-Aufrufen
- [x] Er definiert das Trennzeichen zwischen mehreren Argumenten einer `print()`-Funktion
- [ ] Er definiert den Zeichensatz für die Ausgabe
- [ ] Er definiert, ob die Ausgabe im Terminal oder in einer Datei erfolgen soll

# Frage 2
Was ist die Ausgabe des folgenden Codes?
```python
print("Python", "ist", "cool", sep="-")
```
- [ ] Python ist cool
- [x] Python-ist-cool
- [ ] Python-ist-cool-
- [ ] Pythonistcool

# Frage 3
Welcher Parameter der `print()`-Funktion bestimmt, was am Ende der Ausgabe steht?
- [ ] finish
- [ ] separator
- [x] end
- [ ] last

# Frage 4
Was ist die Ausgabe des folgenden Codes?
```python
print("Hallo", end="")
print("Welt")
```
- [ ] Hallo
      Welt
- [x] HalloWelt
- [ ] Hallo Welt
- [ ] HalloWelt\n

# Frage 5
Welchen Datentyp gibt die `input()`-Funktion immer zurück?
- [ ] int
- [ ] float
- [ ] Der Datentyp hängt von der Eingabe ab
- [x] str

# Frage 6
Wie konvertiert man eine vom Benutzer eingegebene Zahl korrekt in einen Integer?
- [ ] `integer(input("Gib eine Zahl ein: "))`
- [x] `int(input("Gib eine Zahl ein: "))`
- [ ] `input(int("Gib eine Zahl ein: "))`
- [ ] `convert.int(input("Gib eine Zahl ein: "))`

# Frage 7
Was passiert, wenn ein Benutzer "abc" eingibt und Sie versuchen, die Eingabe mit `int()` zu konvertieren?
- [ ] Die Eingabe wird zu 0 konvertiert
- [ ] Die Eingabe wird zu einer ASCII-Zahl konvertiert
- [x] Es wird ein ValueError ausgelöst
- [ ] Die Eingabe bleibt ein String und wird nicht konvertiert

# Frage 8
Welche der folgenden String-Formatierungsmethoden ist in modernem Python bevorzugt?
- [ ] Konkatenation mit dem `+`-Operator
- [ ] Die `%`-Formatierung
- [ ] Die `.format()`-Methode
- [x] f-Strings

# Frage 9
Was ist die Ausgabe des folgenden Codes?
```python
name = "Max"
alter = 25
print(f"{name} ist {alter} Jahre alt.")
```
- [ ] "{name} ist {alter} Jahre alt."
- [ ] "Max ist 25 Jahre alt"
- [x] Max ist 25 Jahre alt.
- [ ] name ist alter Jahre alt.

# Frage 10
Was ist die Ausgabe des folgenden Codes?
```python
print("Zahl: %.2f" % 3.14159)
```
- [ ] Zahl: 3.14159
- [x] Zahl: 3.14
- [ ] Zahl: %.2f
- [ ] Zahl: 3

# Frage 11
Welche Escape-Sequenz wird für einen Tabulator verwendet?
- [ ] \s
- [ ] \tab
- [x] \t
- [ ] \b

# Frage 12
Was ist die Ausgabe des folgenden Codes?
```python
print("Erste Zeile\nZweite Zeile")
```
- [x] Erste Zeile
      Zweite Zeile
- [ ] Erste Zeile\nZweite Zeile
- [ ] Erste ZeileZweite Zeile
- [ ] Erste Zeile Zweite Zeile

# Frage 13
Wie kann man die Benutzereingabe validieren, um sicherzustellen, dass eine gültige Zahl eingegeben wurde?
- [ ] Die `input()`-Funktion tut dies automatisch
- [ ] Durch die Verwendung von `validateInput()`
- [x] Durch die Verwendung von try-except-Blöcken mit `ValueError`
- [ ] Durch die Verwendung der `is_numeric()`-Funktion

# Frage 14
Was ist das Ergebnis des folgenden Codes?
```python
text = "Hallo {0} und {1}".format("Welt", "Python")
print(text)
```
- [ ] Hallo {0} und {1}
- [ ] Hallo und
- [x] Hallo Welt und Python
- [ ] Hallo Python und Welt

# Frage 15
Welche Behauptung ist wahr?
- [ ] Ein String kann nach seiner Erstellung verändert werden
- [x] Die `.format()`-Methode kann indizierte Parameter wie `{0}`, `{1}` nutzen
- [ ] Die `input()`-Funktion konvertiert die Eingabe automatisch in eine Zahl, wenn möglich
- [ ] Die `print()`-Funktion kann maximal 5 Argumente verarbeiten

# Frage 16
Was ist die korrekte Syntax für die if-Anweisung in Python?
- [ ] if (bedingung) {code}
- [ ] if bedingung: then code
- [x] if bedingung: code
- [ ] if (bedingung): code:

# Frage 17
Welches Zeichen kennzeichnet in Python den Beginn eines Codeblocks?
- [ ] {
- [ ] begin
- [x] : (Doppelpunkt)
- [ ] [

# Frage 18
Was ist in Python wichtig, um den Codeblock innerhalb einer if-Anweisung zu definieren?
- [ ] Geschweifte Klammern um den Code
- [ ] Das Schlüsselwort "begin" und "end"
- [x] Korrekte Einrückung des Codes
- [ ] Semikolons am Ende jeder Zeile

# Frage 19
Was ist die Ausgabe des folgenden Codes?
```python
x = 5
if x > 3:
    print("A")
if x > 4:
    print("B")
if x == 5:
    print("C")
```
- [ ] A
- [ ] C
- [ ] AB
- [x] ABC

# Frage 20
Was ist die Ausgabe des folgenden Codes?
```python
x = 10
if x > 5:
    print("A")
elif x > 8:
    print("B")
elif x > 12:
    print("C")
else:
    print("D")
```
- [x] A
- [ ] B
- [ ] C
- [ ] D

# Frage 21
Welcher Teil einer if-elif-else Struktur ist optional?
- [ ] if
- [x] elif und else
- [ ] Nur else
- [ ] Nur elif

# Frage 22
Was ist die Ausgabe des folgenden Codes?
```python
x = 7
if x > 10:
    print("A")
else:
    if x > 5:
        print("B")
    else:
        print("C")
```
- [ ] A
- [x] B
- [ ] C
- [ ] Keines der oben genannten

# Frage 23
Was ist die korrekte Syntax für eine if-elif-else-Anweisung in Python?
- [ ] if (bedingung1) {code1} elif (bedingung2) {code2} else {code3}
- [ ] if bedingung1 then code1 elif bedingung2 then code2 else code3
- [x] if bedingung1: code1 elif bedingung2: code2 else: code3
- [ ] if bedingung1 do code1 else if bedingung2 do code2 else do code3

# Frage 24
Welche der folgenden Anweisungen ist äquivalent zu `x = 5 if y > 0 else 10`?
- [ ] if y > 0 then x = 5 else x = 10
- [x] if y > 0: x = 5 else: x = 10
- [ ] x = (5 if y > 0) ? else 10
- [ ] x = (y > 0) ? 5 : 10

# Frage 25
Was ist die Ausgabe des folgenden Codes?
```python
x = 5
y = 10
print("Ja" if x < y else "Nein")
```
- [x] Ja
- [ ] Nein
- [ ] "Ja" if x < y else "Nein"
- [ ] Ein Syntaxfehler

# Frage 26
Welcher logische Operator prüft, ob beide Bedingungen wahr sind?
- [ ] ||
- [ ] &
- [x] and
- [ ] &&

# Frage 27
Was ist das Ergebnis des Ausdrucks `True and False`?
- [ ] True
- [x] False
- [ ] None
- [ ] Ein Syntaxfehler

# Frage 28
Was ist das Ergebnis des Ausdrucks `True or False`?
- [x] True
- [ ] False
- [ ] None
- [ ] Ein Syntaxfehler

# Frage 29
Was bedeutet die Kurzschlussauswertung bei logischen Operatoren?
- [ ] Die logischen Operatoren werden schneller als andere Operatoren ausgewertet
- [ ] Die Bedingungen werden in umgekehrter Reihenfolge ausgewertet
- [x] Der zweite Operand wird nur ausgewertet, wenn der erste Operand nicht ausreicht, um das Ergebnis zu bestimmen
- [ ] Die Operanden werden gleichzeitig ausgewertet

# Frage 30
Was ist das Ergebnis des folgenden Ausdrucks?
```python
5 > 3 and 10 > 20
```
- [ ] True
- [x] False
- [ ] Ein Fehler, da die Datentypen unterschiedlich sind
- [ ] None

# Frage 31
Was ist der Wert von `a` nach der Ausführung des folgenden Codes?
```python
a = 0
b = 5
if b > 0:
    a = 1
else:
    a = 2
```
- [x] 1
- [ ] 0
- [ ] 2
- [ ] 5

# Frage 32
Welcher logische Operator negiert eine Bedingung?
- [ ] not()
- [ ] !
- [x] not
- [ ] reverse

# Frage 33
Was ist die Ausgabe des folgenden Codes?
```python
x = 5
if x > 0:
    print("A", end="")
    if x > 10:
        print("B", end="")
    else:
        print("C", end="")
print("D")
```
- [ ] AD
- [x] ACD
- [ ] ABD
- [ ] D

# Frage 34
Welche der folgenden Aussagen ist wahr bezüglich der `else`-Klausel?
- [ ] Eine `else`-Klausel kann ohne vorherige `if`-Anweisung stehen
- [ ] Eine `if`-Anweisung kann mehrere `else`-Klauseln haben
- [x] Die `else`-Klausel wird ausgeführt, wenn keine der vorherigen Bedingungen wahr ist
- [ ] Die `else`-Klausel muss immer am Ende einer verschachtelten `if`-Struktur stehen

# Frage 35
Was ist die Ausgabe des folgenden Codes?
```python
for i in range(3):
    if i == 1:
        break
    print(i, end="")
```
- [x] 0
- [ ] 01
- [ ] 012
- [ ] Keine Ausgabe

# Frage 36
Was ist der Unterschied zwischen `==` und `is` in Python?
- [ ] Es gibt keinen Unterschied, beide prüfen auf Gleichheit
- [ ] `==` ist ein Syntax-Fehler, nur `is` kann für Vergleiche verwendet werden
- [x] `==` prüft auf Wertgleichheit, `is` prüft auf Identität (gleiches Objekt)
- [ ] `==` wird für Zahlen verwendet, `is` für Strings und andere Objekte

# Frage 37
Was ist die Ausgabe des folgenden Codes?
```python
a = True
b = False
c = True
print(a and b or c)
```
- [x] True
- [ ] False
- [ ] Ein Syntaxfehler
- [ ] None

# Frage 38
Was ist die Ausgabe des folgenden Codes?
```python
a = 5
b = 3
print("A" if a > b else "B" if a == b else "C")
```
- [x] A
- [ ] B
- [ ] C
- [ ] Ein Syntaxfehler

# Frage 39
Welcher Vergleichsoperator prüft auf Ungleichheit?
- [ ] <>
- [ ] =!
- [x] !=
- [ ] /=

# Frage 40
Was ist die Ausgabe des folgenden Codes?
```python
a = "10"
b = 10
print("Gleich" if a == b else "Ungleich")
```
- [ ] Gleich
- [x] Ungleich
- [ ] Ein TypeError wird ausgelöst
- [ ] Keine Ausgabe

# Frage 41
Was ist der Wert von `y` nach der Ausführung des folgenden Codes?
```python
x = 10
y = 0
if x > 5:
    if x > 15:
        y = 1
    else:
        y = 2
else:
    y = 3
```
- [ ] 0
- [ ] 1
- [x] 2
- [ ] 3

# Frage 42
Welche Aussage zur Kurzschlussauswertung bei `and` ist korrekt?
- [ ] Der zweite Operand wird immer ausgewertet
- [x] Wenn der erste Operand `False` ist, wird der zweite Operand nicht ausgewertet
- [ ] Kurzschlussauswertung funktioniert nur bei `or`, nicht bei `and`
- [ ] Kurzschlussauswertung ist ein Optimierungsfeature, das in Python nicht implementiert ist

# Frage 43
Was ist die Ausgabe des folgenden Codes?
```python
print("A", "B", "C", sep=":", end="!")
```
- [ ] A B C!
- [ ] A:B:C
- [x] A:B:C!
- [ ] ABC!

# Frage 44
Welche der folgenden ist keine gültige Methode zur String-Formatierung in Python?
- [ ] `"Name: " + name`
- [ ] `"Name: %s" % name`
- [ ] `"Name: {}".format(name)`
- [x] `"Name: @s".replace("@s", name)`

# Frage 45
Was ist das Ergebnis des folgenden Code-Fragments?
```python
a = 5
b = 0
if a > 0:
    b = 1
    if a > 10:
        b = 2
    elif a > 3:
        b = 3
print(b)
```
- [ ] 0
- [ ] 1
- [x] 3
- [ ] 2

# Frage 46
Was ist die Prioritätsreihenfolge der logischen Operatoren in Python (von höchster zu niedrigster Priorität)?
- [ ] or, and, not
- [ ] and, or, not
- [x] not, and, or
- [ ] not, or, and

# Frage 47
Welche der folgenden Aussagen über bedingte Ausdrücke in Python ist korrekt?
- [ ] Bedingte Ausdrücke (Ternary Operator) wurden erst in Python 3 eingeführt
- [ ] Bedingte Ausdrücke können nicht mit logischen Operatoren kombiniert werden
- [x] Ein bedingter Ausdruck hat die Form `wert_wenn_wahr if bedingung else wert_wenn_falsch`
- [ ] Bedingte Ausdrücke können in Python nur für String-Operationen verwendet werden

# Frage 48
Was ist die Ausgabe des folgenden Codes?
```python
x = 0
while x < 3:
    x += 1
    if x == 2:
        continue
    print(x, end="")
```
- [ ] 123
- [x] 13
- [ ] 1
- [ ] 23

# Frage 49
Was ist die korrekte Methode, um einen String in einem f-String zu formatieren, sodass er eine bestimmte Breite hat und rechtsbündig ist?
- [ ] `f"Der Wert ist: |{wert:>10}|"`
- [ ] `f"Der Wert ist: |{wert->10}|"`
- [x] `f"Der Wert ist: |{wert:>10}|"`
- [ ] `f"Der Wert ist: |{wert:right(10)}|"`

# Frage 50
Welche der folgenden Bedingungen ist äquivalent zu `not (a or b)`?
- [ ] not a or not b
- [x] not a and not b
- [ ] not a or b
- [ ] not (a and not b)
