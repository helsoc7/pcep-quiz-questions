# Frage 1
Was sind Literale in Python?
- [ ] Variablen, die sich während der Programmausführung ändern können
- [x] Feste Werte, die direkt im Code erscheinen
- [ ] Funktionen, die Werte zurückgeben
- [ ] Methoden zur Typkonvertierung

# Frage 2
Welche der folgenden sind gültige Variablennamen in Python?
- [x] benutzer_name
- [x] _alter
- [ ] 2wert
- [ ] class

# Frage 3
Welche Namenskonvention wird laut PEP 8 für Variablen empfohlen?
- [ ] CamelCase (maxMustermann)
- [x] snake_case (max_mustermann)
- [ ] UPPERCASE (MAXMUSTERMANN)
- [ ] PascalCase (MaxMustermann)

# Frage 4
Welche der folgenden Aussagen zu Variablen in Python sind korrekt?
- [x] Variablennamen sind case-sensitive
- [x] Variablennamen können Unterstriche enthalten
- [ ] Variablennamen müssen mit einem Buchstaben beginnen
- [ ] Python-Schlüsselwörter können als Variablennamen verwendet werden

# Frage 5
Was ist der Unterschied zwischen Variablen und Literalen?
- [ ] Literale können nur Zahlen sein, Variablen können beliebige Werte enthalten
- [ ] Variablen werden zur Laufzeit erstellt, Literale zur Kompilierzeit
- [x] Variablen sind benannte Speicherplätze, Literale sind feste Werte im Code
- [ ] Es gibt keinen Unterschied, beide Begriffe beschreiben dasselbe

# Frage 6
Welcher Wert entsteht durch die folgende Operation? 

\`\`\`python
int(float("3.14"))
\`\`\`
- [x] 3
- [ ] 3.14
- [ ] 4
- [ ] Dies führt zu einem ValueError

# Frage 7
Welche der folgenden Aussagen zur Typkonvertierung in Python sind wahr?
- [x] \`int("42")\` konvertiert den String "42" in die Ganzzahl 42
- [x] \`bool(0)\` gibt False zurück
- [ ] \`int("3.14")\` konvertiert den String "3.14" in die Ganzzahl 3
- [ ] \`str(True)\` gibt "1" zurück

# Frage 8
Was ist das Ergebnis von \`bool("")\`?
- [x] False
- [ ] True
- [ ] ""
- [ ] None

# Frage 9
Welche der folgenden Werte werden in einem booleschen Kontext als \`False\` interpretiert?
- [x] 0
- [x] ""
- [x] []
- [ ] "False"

# Frage 10
Wie überprüft man in Python, ob eine Variable den Typ Integer hat?
- [ ] \`variable.type() == int\`
- [ ] \`type(variable) == "int"\`
- [x] \`isinstance(variable, int)\`
- [ ] \`isint(variable)\`


# Frage 11
Was ist das Ergebnis des Ausdrucks \`0b101010\`?
- [ ] 101010
- [ ] 12
- [x] 42
- [ ] Ein Syntaxfehler

# Frage 12
Welche Aussage zum Wertebereich von Integer in Python ist korrekt?
- [ ] Integer sind auf 32 Bit (von -2^31 bis 2^31-1) begrenzt
- [ ] Integer sind auf 64 Bit (von -2^63 bis 2^63-1) begrenzt
- [x] Integer haben einen unbegrenzten Wertebereich
- [ ] Integer können nur positive Werte speichern

# Frage 13
Was ist der Wert von \`1_000_000\` in Python?
- [x] 1000000
- [ ] 1_000_000
- [ ] Ein Syntaxfehler
- [ ] 100000

# Frage 14
Was ist das Ergebnis des Ausdrucks \`0.1 + 0.2 == 0.3\` in Python?
- [ ] True
- [x] False
- [ ] Ein Syntaxfehler
- [ ] Hängt von der Python-Version ab

# Frage 15
Welcher Code erzeugt den Wert "unendlich" in Python?
- [ ] infinity()
- [ ] Integer.MAX_VALUE
- [x] float('inf')
- [ ] math.infinity

# Frage 16
Wie greift man auf das erste Zeichen eines Strings \`text\` zu?
- [ ] text(0)
- [x] text[0]
- [ ] text.first()
- [ ] text.charAt(0)

# Frage 17
Was gibt der folgende Code aus?

\`\`\`python
print("Python"[::-1])
\`\`\`
- [ ] Python
- [ ] P
- [ ] nohtyP
- [x] nohtyP

# Frage 18
Welche Methode verwendet man, um einen String in Kleinbuchstaben umzuwandeln?
- [ ] toLower()
- [ ] lowercase()
- [x] lower()
- [ ] small()

# Frage 19
Welches ist die empfohlene Methode zur String-Formatierung in modernem Python?
- [ ] %-Formatierung
- [ ] format()-Methode
- [x] f-Strings
- [ ] template.substitute()

# Frage 20
Welches Ergebnis liefert \`len("Python")\`?
- [ ] 5
- [x] 6
- [ ] 7
- [ ] Ein Fehler, da len() nicht für Strings funktioniert

# Frage 21
Welche Aussage zu mehrzeiligen Strings in Python ist korrekt?
- [ ] Mehrzeilige Strings können nur mit dem Escape-Zeichen \n erstellt werden
- [ ] Mehrzeilige Strings können nur mit der Konkatenation von Strings erstellt werden
- [x] Mehrzeilige Strings können mit dreifachen Anführungszeichen (''' oder """) erstellt werden
- [ ] Python unterstützt keine mehrzeiligen Strings

# Frage 22
Was ist das Ergebnis von \`"abc" * 3\`?
- [x] "abcabcabc"
- [ ] "abc3"
- [ ] Ein TypeError
- [ ] 9

# Frage 23
Welche Methode wird verwendet, um einen String in eine Liste von Teilstrings zu zerlegen?
- [ ] divide()
- [ ] partition()
- [x] split()
- [ ] tokenize()

# Frage 24
Was ist der Wert von \`5 // 2\` in Python?
- [ ] 2.5
- [x] 2
- [ ] 3
- [ ] 2.0

# Frage 25
Welcher Operator wird für die Potenzierung in Python verwendet?
- [ ] ^
- [ ] *^
- [ ] pow()
- [x] **

# Frage 26
Was ist das Ergebnis von \`2 + 3 * 4\`?
- [ ] 20
- [x] 14
- [ ] 10
- [ ] 24

# Frage 27
Welcher Ausdruck ist äquivalent zu \`x += 5\`?
- [x] x = x + 5
- [ ] x = x * 5
- [ ] x = 5
- [ ] x = 5 + x

# Frage 28
Was ist der Wert von \`10 % 3\`?
- [ ] 3
- [ ] 3.33
- [x] 1
- [ ] 0

# Frage 29
Wie lautet die korrekte Operatorrangfolge in Python (von höchster zu niedrigster Priorität)?
- [ ] Zuweisungen, arithmetische Operationen, Klammern
- [ ] Klammern, Zuweisungen, arithmetische Operationen
- [x] Klammern, Potenzierung, Multiplikation/Division, Addition/Subtraktion, Zuweisungen
- [ ] Addition/Subtraktion, Multiplikation/Division, Potenzierung, Klammern

# Frage 30
Was ist das Ergebnis von \`True + True\` in Python?
- [ ] True
- [x] 2
- [ ] 1
- [ ] Ein TypeError


# Frage 31
Was ist das Ergebnis von \`5 > 3 and 10 < 20\`?
- [x] True
- [ ] False
- [ ] None
- [ ] Ein Syntaxfehler

# Frage 32
Was ist das Ergebnis von \`not (5 > 7)\`?
- [x] True
- [ ] False
- [ ] None
- [ ] Ein Syntaxfehler

# Frage 33
Was ist das Ergebnis von \`0 < 5 < 10\` in Python?
- [x] True
- [ ] False
- [ ] Ein Syntaxfehler
- [ ] Hängt von der Python-Version ab

# Frage 34
Welcher logische Operator wird für die ODER-Verknüpfung verwendet?
- [ ] ||
- [x] or
- [ ] OR
- [ ] |

# Frage 35
Was bedeutet der Ausdruck "Kurzschlussauswertung" bei logischen Operatoren?
- [ ] Die Auswertung erfolgt besonders schnell
- [ ] Logische Operatoren haben eine höhere Priorität als andere Operatoren
- [x] Der zweite Operand wird nur ausgewertet, wenn der erste nicht ausreicht, um das Ergebnis zu bestimmen
- [ ] Die Auswertung erfolgt von rechts nach links

# Frage 36
Was ist das Ergebnis von \`True or print("Hallo")\`?
- [x] True
- [ ] Hallo
- [ ] True und Hallo wird ausgegeben
- [ ] Ein Syntaxfehler

# Frage 37
Welche Operatorenkombination kann verwendet werden, um zu prüfen, ob x zwischen 10 und 20 liegt (einschließlich)?
- [ ] 10 < x < 20
- [x] 10 <= x <= 20
- [ ] x >= 10 and x <= 20
- [ ] Sowohl 10 <= x <= 20 als auch x >= 10 and x <= 20 sind korrekt


# Frage 38
Was ist das Ergebnis von \`int(3.99)\` in Python?
- [x] 3
- [ ] 4
- [ ] 3.0
- [ ] Ein ValueError

# Frage 39
Welche der folgenden Anweisungen führt zu einem ValueError?
- [ ] \`int("42")\`
- [ ] \`float("3.14")\`
- [x] \`int("3.14")\`
- [ ] \`bool("False")\`

# Frage 40
Was ist das Ergebnis von \`set([1, 2, 2, 3, 3, 3])\`?
- [ ] [1, 2, 2, 3, 3, 3]
- [ ] [1, 2, 3]
- [x] {1, 2, 3}
- [ ] Ein TypeError

# Frage 41
Welche Funktion gibt den Datentyp eines Objekts zurück?
- [x] type()
- [ ] typeof()
- [ ] gettype()
- [ ] datatype()

# Frage 42
Was ist das Ergebnis von \`type(5)\`?
- [ ] "int"
- [ ] int
- [x] <class 'int'>
- [ ] integer

# Frage 43
Was gibt die Methode \`isdigit()\` bei einem String zurück?
- [ ] Die Anzahl der Ziffern im String
- [x] True, wenn der String nur aus Ziffern besteht
- [ ] Den ersten numerischen Wert im String
- [ ] Eine Liste aller Ziffern im String


# Frage 44
Welche Eigenschaft haben alle Strings in Python?
- [ ] Sie können nach der Erstellung verändert werden
- [x] Sie sind unveränderlich (immutable)
- [ ] Sie haben eine maximale Länge von 255 Zeichen
- [ ] Sie können nur ASCII-Zeichen enthalten

# Frage 45
Was ist der Unterschied zwischen \`==\` und \`is\` in Python?
- [ ] Es gibt keinen Unterschied, beide prüfen auf Gleichheit
- [ ] `==` prüft auf Gleichheit, \`is\` ist kein gültiger Python-Operator
- [x] `==` prüft auf Wertgleichheit, \`is\` prüft auf Identität (gleiches Objekt)
- [ ] `==` funktioniert nur für numerische Typen, \`is\` funktioniert für alle Typen

# Frage 46
Welches ist ein gültiger Weg, einen Raw-String in Python zu definieren?
- [x] r"C:\Users\Name"
- [ ] raw"C:\Users\Name"
- [ ] "C:\\Users\\Name"
- [ ] raw("C:\Users\Name")

# Frage 47
Was ist das Ergebnis der Ausführung des folgenden Codes?

\`\`\`python
a = "Python"
a[0] = "J"
print(a)
\`\`\`
- [ ] "Jython"
- [ ] "Python"
- [x] Ein TypeError, da Strings unveränderlich sind
- [ ] Ein IndexError

# Frage 48
Welche Aussage zu booleschen Werten in Python ist korrekt?
- [ ] Python hat keine speziellen booleschen Datentypen
- [ ] Boolesche Werte werden durch 0 und 1 repräsentiert
- [x] True und False sind spezielle boolesche Werte mit Großbuchstaben
- [ ] True und False sind normale Strings

# Frage 49
Was gibt die folgende Code-Zeile aus?

\`\`\`python
print("Python"[1:4])
\`\`\`
- [ ] "Pyt"
- [x] "yth"
- [ ] "ytho"
- [ ] "ython"

# Frage 50
Wie kann man in Python prüfen, ob ein String nur aus Buchstaben besteht?
- [ ] \`string.only_letters()\`
- [ ] \`letters_only(string)\`
- [x] \`string.isalpha()\`
- [ ] \`string.alpha()\`
