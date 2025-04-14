# Frage 1
Wie wird eine Funktion in Python definiert?
- [ ] `function my_function():`
- [x] `def my_function():`
- [ ] `new function my_function():`
- [ ] `create my_function():`

# Frage 2
Was ist ein "Docstring" in Python?
- [ ] Ein Kommentar, der mit `//` beginnt
- [ ] Eine spezielle Importanweisung für Dokumentation
- [x] Ein Dokumentationsstring am Anfang einer Funktion, der mit dreifachen Anführungszeichen umschlossen ist
- [ ] Eine externe Dokumentationsdatei

# Frage 3
Was ist der Unterschied zwischen einem Parameter und einem Argument in Python?
- [ ] Es gibt keinen Unterschied, beide Begriffe beschreiben dasselbe
- [x] Parameter sind Variablen in der Funktionsdefinition, Argumente sind die Werte, die an die Funktion übergeben werden
- [ ] Parameter sind die Werte, die an die Funktion übergeben werden, Argumente sind Variablen in der Funktionsdefinition
- [ ] Parameter sind für einfache Datentypen, Argumente für komplexe Datentypen

# Frage 4
Was ist die Ausgabe des folgenden Codes?
```python
def greet(name, greeting="Hallo"):
    return f"{greeting}, {name}!"

print(greet("Max"))
```
- [ ] Max, Hallo!
- [x] Hallo, Max!
- [ ] greeting, name!
- [ ] Ein Fehler wird ausgelöst

# Frage 5
Welche Aussage zu Rückgabewerten in Python-Funktionen ist korrekt?
- [ ] Jede Funktion muss genau einen Wert zurückgeben
- [ ] Eine Funktion kann maximal drei Werte zurückgeben
- [x] Wenn keine `return`-Anweisung vorhanden ist, gibt die Funktion `None` zurück
- [ ] Die `return`-Anweisung kann nur am Ende einer Funktion stehen

# Frage 6
Was ist der Rückgabewert der folgenden Funktion, wenn sie mit `my_function(5)` aufgerufen wird?
```python
def my_function(x):
    if x > 10:
        return "A"
    elif x > 5:
        return "B"
    else:
        return "C"
```
- [ ] "A"
- [ ] "B"
- [x] "C"
- [ ] None

# Frage 7
Wie kann man mehrere Werte aus einer Funktion zurückgeben?
- [ ] Mit mehreren `return`-Anweisungen nacheinander
- [x] Durch Komma-getrennte Werte in einer `return`-Anweisung, die ein Tupel zurückgeben
- [ ] Durch Verwendung des `multiple`-Schlüsselworts
- [ ] Durch Verwendung einer globalen Liste

# Frage 8
Was ist die Ausgabe des folgenden Codes?
```python
def get_values():
    return 1, 2, 3

a, b, c = get_values()
print(b)
```
- [ ] 1
- [x] 2
- [ ] 3
- [ ] Ein Fehler wird ausgelöst

# Frage 9
Was sind Schlüsselwortargumente (Keyword Arguments) in Python?
- [ ] Argumente, die nur bestimmte Schlüsselwörter als Werte akzeptieren
- [x] Argumente, die beim Funktionsaufruf mit dem Parameternamen übergeben werden
- [ ] Argumente, die als Wörterbücher (dictionaries) übergeben werden
- [ ] Argumente, die für die Funktion erforderlich sind

# Frage 10
Welcher Funktionsaufruf ist gültig, wenn die Funktion wie folgt definiert ist?
```python
def calculate(a, b, operation="add"):
    # Funktionsinhalt hier
```
- [ ] `calculate()`
- [ ] `calculate(operation="multiply")`
- [x] `calculate(5, 3, operation="multiply")`
- [ ] `calculate(a=5, 3, operation="multiply")`

# Frage 11
Was wird in der folgenden Funktionsdefinition als Standardparameter bezeichnet?
```python
def greet(name, message="Hallo", language="de"):
    # Funktionsinhalt hier
```
- [ ] `name`
- [ ] `message` und `name`
- [x] `message` und `language`
- [ ] Alle drei Parameter sind Standardparameter

# Frage 12
Was passiert, wenn ein Standardparameter als veränderliches Objekt (z.B. eine Liste) definiert wird?
- [ ] Die Funktion generiert einen Fehler, da Standardparameter immer unveränderlich sein müssen
- [x] Das Objekt wird beim ersten Aufruf der Funktion erstellt und bei nachfolgenden Aufrufen wiederverwendet
- [ ] Bei jedem Funktionsaufruf wird ein neues Objekt erstellt
- [ ] Diese Syntax ist in Python nicht erlaubt

# Frage 13
Was ist der Gültigkeitsbereich (Scope) einer Variablen, die innerhalb einer Funktion definiert ist?
- [x] Lokal zur Funktion, außerhalb nicht zugänglich
- [ ] Global für das gesamte Programm
- [ ] Abhängig vom Variablentyp
- [ ] Abhängig vom Variablennamen

# Frage 14
Was macht das `global`-Schlüsselwort in Python?
- [ ] Es definiert eine Variable, die in allen Modulen verfügbar ist
- [x] Es ermöglicht das Ändern einer globalen Variable innerhalb einer Funktion
- [ ] Es importiert eine globale Variable aus einem anderen Modul
- [ ] Es macht alle Variablen in einer Funktion global

# Frage 15
Was ist die Ausgabe des folgenden Codes?
```python
x = 10

def test_function():
    x = 20
    print(x)

test_function()
print(x)
```
- [ ] 10, 10
- [ ] 20, 20
- [x] 20, 10
- [ ] Ein Fehler wird ausgelöst

# Frage 16
Was macht das `nonlocal`-Schlüsselwort in Python?
- [ ] Es definiert eine Variable, die in allen Funktionen verfügbar ist
- [ ] Es importiert eine Variable aus einem anderen Modul
- [x] Es ermöglicht das Ändern einer Variable aus dem umschließenden (nicht globalen) Gültigkeitsbereich
- [ ] Es verhindert, dass eine Variable außerhalb der Funktion sichtbar ist

# Frage 17
Was ist eine Lambda-Funktion in Python?
- [ ] Eine Funktion, die mehrere Rückgabewerte hat
- [x] Eine anonyme Funktion, die in einem Ausdruck definiert wird
- [ ] Eine Funktion, die automatisch ausgeführt wird
- [ ] Eine integrierte Python-Funktion für mathematische Operationen

# Frage 18
Welche der folgenden Aussagen ist richtig für Lambda-Funktionen in Python?
- [ ] Lambda-Funktionen können mehrere Anweisungen enthalten
- [ ] Lambda-Funktionen können nur einen Parameter haben
- [x] Lambda-Funktionen bestehen aus einem einzigen Ausdruck
- [ ] Lambda-Funktionen können keine Parameter haben

# Frage 19
Was ist die korrekte Syntax für eine Lambda-Funktion, die das Quadrat einer Zahl berechnet?
- [x] `lambda x: x**2`
- [ ] `lambda x => x**2`
- [ ] `lambda(x) { return x**2; }`
- [ ] `lambda = x**2`

# Frage 20
Wie importiert man ein Modul in Python?
- [ ] `include module`
- [ ] `require module`
- [x] `import module`
- [ ] `using module`

# Frage 21
Was bewirkt die folgende Import-Anweisung?
```python
from math import sin, cos
```
- [ ] Importiert das gesamte math-Modul
- [x] Importiert nur die Funktionen sin und cos aus dem math-Modul
- [ ] Erstellt Aliase für das math-Modul
- [ ] Importiert alle Funktionen außer sin und cos aus dem math-Modul

# Frage 22
Wie importiert man ein Modul mit einem Alias?
- [ ] `import module as alias`
- [x] `import module as alias`
- [ ] `import module with alias`
- [ ] `from module import alias`

# Frage 23
Was ist der Vorteil der Verwendung von `import module` gegenüber `from module import *`?
- [ ] Die erste Variante ist schneller
- [ ] Die erste Variante importiert weniger Code
- [x] Die erste Variante vermeidet Namenskonflikte im aktuellen Namensraum
- [ ] Es gibt keinen Unterschied zwischen den beiden Varianten

# Frage 24
Welche Funktion zeigt alle verfügbaren Namen in einem Modul an?
- [ ] `list(module)`
- [ ] `help(module)`
- [x] `dir(module)`
- [ ] `names(module)`

# Frage 25
Was ist der Zweck des `if __name__ == "__main__":`-Blocks in Python?
- [ ] Er definiert den Hauptteil des Programms, der immer ausgeführt wird
- [x] Er ermöglicht, dass Code nur ausgeführt wird, wenn die Datei direkt ausgeführt wird, nicht wenn sie als Modul importiert wird
- [ ] Er überprüft, ob das Programm mit Administratorrechten ausgeführt wird
- [ ] Er kennzeichnet den Anfang der Hauptfunktion

# Frage 26
Was ist die grundlegende Struktur für die Ausnahmebehandlung in Python?
- [ ] `catch-try-finally`
- [x] `try-except-else-finally`
- [ ] `try-catch-finally`
- [ ] `attempt-except-otherwise`

# Frage 27
Was wird im `except`-Block einer try-except-Struktur definiert?
- [ ] Der Code, der ausgeführt werden soll, nachdem eine Ausnahme behandelt wurde
- [x] Der Code, der ausgeführt werden soll, wenn eine bestimmte Ausnahme auftritt
- [ ] Der Code, der unter keinen Umständen eine Ausnahme auslösen darf
- [ ] Der Code, der ausgeführt werden soll, wenn keine Ausnahme auftritt

# Frage 28
Was ist die Ausgabe des folgenden Codes?
```python
try:
    print("A")
    1/0
    print("B")
except ZeroDivisionError:
    print("C")
finally:
    print("D")
```
- [ ] A B D
- [x] A C D
- [ ] A D
- [ ] C D

# Frage 29
Was ist der Zweck des `finally`-Blocks in einer try-except-Struktur?
- [ ] Er wird nur ausgeführt, wenn keine Ausnahme auftritt
- [ ] Er definiert die Standardaktion, wenn keine `except`-Klausel die Ausnahme abfängt
- [x] Er wird immer ausgeführt, unabhängig davon, ob eine Ausnahme auftritt oder nicht
- [ ] Er enthält Code, der vor dem `try`-Block ausgeführt wird

# Frage 30
Was ist der Zweck des `else`-Blocks in einer try-except-Struktur?
- [ ] Er wird immer ausgeführt, unabhängig davon, ob eine Ausnahme auftritt oder nicht
- [x] Er wird nur ausgeführt, wenn keine Ausnahme im `try`-Block auftritt
- [ ] Er wird nur ausgeführt, wenn eine Ausnahme im `try`-Block auftritt
- [ ] Er enthält alternative Code-Pfade für verschiedene Ausnahmetypen

# Frage 31
Welche der folgenden ist KEINE eingebaute Ausnahme in Python?
- [ ] `ValueError`
- [ ] `TypeError`
- [ ] `IndexError`
- [x] `ErrorException`

# Frage 32
Wie definiert man eine benutzerdefinierte Ausnahme in Python?
- [ ] Durch Dekorieren einer Funktion mit `@exception`
- [x] Durch Erstellen einer Klasse, die von `Exception` erbt
- [ ] Durch Verwenden des `raise`-Schlüsselworts mit einem benutzerdefinierten String
- [ ] Durch Importieren des `custom_exceptions`-Moduls

# Frage 33
Was ist die korrekte Syntax, um eine Ausnahme in Python auszulösen?
- [ ] `throw Exception("Fehlermeldung")`
- [ ] `except Exception("Fehlermeldung")`
- [x] `raise Exception("Fehlermeldung")`
- [ ] `error Exception("Fehlermeldung")`

# Frage 34
Wie fängt man mehrere Ausnahmetypen in einem einzigen `except`-Block ab?
- [ ] `except ValueError, TypeError:`
- [x] `except (ValueError, TypeError):`
- [ ] `except [ValueError, TypeError]:`
- [ ] `except ValueError and TypeError:`

# Frage 35
Was ist die Ausgabe des folgenden Codes?
```python
try:
    x = int("abc")
except ValueError as e:
    print("A:", e)
except TypeError:
    print("B")
except:
    print("C")
```
- [x] A: invalid literal for int() with base 10: 'abc'
- [ ] B
- [ ] C
- [ ] Ein Fehler wird ausgelöst

# Frage 36
Wofür wird das Schlüsselwort `as` in einem `except`-Block verwendet?
- [ ] Um einen alternativen Ausnahmebehandlungscode zu definieren
- [x] Um die gefangene Ausnahme einer Variablen zuzuweisen
- [ ] Um einen Alias für den Ausnahmetyp zu definieren
- [ ] Um das Ausnahmebehandlungsverhalten zu ändern

# Frage 37
Was ist die Hierarchie der Ausnahmen in Python?
- [ ] Alle Ausnahmen sind eigenständig und haben keine Hierarchie
- [x] Alle Ausnahmen erben von der Basisklasse `BaseException`
- [ ] Alle Ausnahmen erben von der Basisklasse `Error`
- [ ] Die Hierarchie hängt vom Typ des Fehlers ab

# Frage 38
Welcher der folgenden Codeblöcke zeigt die korrekte Verwendung von `try`, `except` und `finally`?
- [ ] ```python
try:
    # Code
catch Exception:
    # Ausnahmebehandlung
endtry
```
- [ ] ```python
try {
    # Code
} except (Exception) {
    # Ausnahmebehandlung
}
```
- [x] ```python
try:
    # Code
except Exception:
    # Ausnahmebehandlung
finally:
    # Wird immer ausgeführt
```
- [ ] ```python
try
    # Code
except
    # Ausnahmebehandlung
end
```

# Frage 39
Was passiert, wenn in einem `finally`-Block eine Ausnahme auftritt?
- [ ] Die Ausnahme wird ignoriert
- [ ] Die Ausnahme wird automatisch behandelt
- [x] Die Ausnahme überschreibt jede frühere Ausnahme im `try`-Block
- [ ] Der `finally`-Block wird nicht vollständig ausgeführt

# Frage 40
Welche Anweisung ist korrekt über die Ausnahme `KeyboardInterrupt`?
- [ ] Sie wird ausgelöst, wenn eine ungültige Tastenkombination gedrückt wird
- [x] Sie wird ausgelöst, wenn der Benutzer das Programm mit Strg+C unterbricht
- [ ] Sie wird ausgelöst, wenn eine Taste gedrückt wird, während das Programm auf Eingabe wartet
- [ ] Sie ist keine Standard-Python-Ausnahme

# Frage 41
Was ist eine Funktion höherer Ordnung in Python?
- [ ] Eine Funktion mit mehr als drei Parametern
- [x] Eine Funktion, die andere Funktionen als Argumente annimmt oder zurückgibt
- [ ] Eine Funktion, die in einer Klasse definiert ist
- [ ] Eine Funktion, die rekursiv ist

# Frage 42
Wie kann man herausfinden, welche Methoden und Attribute ein importiertes Modul hat?
- [ ] `help(module)`
- [x] `dir(module)`
- [ ] `module.methods()`
- [ ] `list(module)`

# Frage 43
Was ist ein Python-Paket?
- [ ] Eine Sammlung von Python-Dateien in einem Verzeichnis
- [ ] Ein komprimiertes Archiv von Python-Modulen
- [x] Ein Verzeichnis, das Python-Module enthält und eine spezielle `__init__.py`-Datei
- [ ] Ein Modul, das mehrere Klassen enthält

# Frage 44
Welches der folgenden Statements ist KEINE gültige Variation der import-Anweisung in Python?
- [ ] `import module`
- [ ] `from module import function`
- [ ] `from module import *`
- [x] `import module.function`

# Frage 45
Was ist die Ausgabe des folgenden Codes?
```python
def outer():
    x = 1
    def inner():
        nonlocal x
        x = 2
        print("Inner:", x)
    inner()
    print("Outer:", x)

outer()
```
- [ ] Inner: 1, Outer: 1
- [ ] Inner: 2, Outer: 1
- [x] Inner: 2, Outer: 2
- [ ] Ein Fehler wird ausgelöst

# Frage 46
Welche der folgenden Aussagen zu Funktionen in Python ist NICHT korrekt?
- [ ] Funktionen können andere Funktionen zurückgeben
- [ ] Funktionen können innerhalb von anderen Funktionen definiert werden
- [ ] Funktionen können als Argumente an andere Funktionen übergeben werden
- [x] Funktionen müssen mindestens einen Parameter haben

# Frage 47
Welches ist ein gültiger Weg, eine Funktion in Python zu einer Variablen zuzuweisen?
- [x] `func_var = my_function`
- [ ] `func_var = function(my_function)`
- [ ] `func_var = @my_function`
- [ ] `func_var = def my_function()`

# Frage 48
Was ist der Unterschied zwischen einem Modul und einem Paket in Python?
- [ ] Es gibt keinen Unterschied, beide Begriffe beschreiben dasselbe
- [x] Ein Modul ist eine einzelne Python-Datei, ein Paket ist ein Verzeichnis mit Python-Dateien und einer __init__.py-Datei
- [ ] Ein Modul enthält nur Funktionen, ein Paket enthält Klassen und Objekte
- [ ] Module sind Teil der Standardbibliothek, Pakete müssen separat installiert werden

# Frage 49
Was ist der Rückgabewert der folgenden Funktion, wenn sie mit `factorial(4)` aufgerufen wird?
```python
def factorial(n):
    if n == 0 or n == 1:
        return 1
    else:
        return n * factorial(n-1)
```
- [ ] 4
- [ ] 12
- [x] 24
- [ ] Ein Fehler wird ausgelöst

# Frage 50
Was ist die Ausgabe des folgenden Codes?
```python
def counter():
    count = 0
    def increment():
        nonlocal count
        count += 1
        return count
    return increment

my_counter = counter()
print(my_counter())
print(my_counter())
```
- [ ] 0, 0
- [ ] 0, 1
- [x] 1, 2
- [ ] Ein Fehler wird ausgelöst
