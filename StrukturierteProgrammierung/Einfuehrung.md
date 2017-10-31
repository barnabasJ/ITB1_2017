# Strukturierte Programmierung

## Softwareentwicklung 

### Ablauf
*Problem* 
-> Analyse -> Spezifikation -> Design -> Algorithmus -> Programmierung -> Programm

## Spezifikation

* Sollte detaliert sein
  * Bei zu vielen Details wird das Problem zu komplex
  * Je komplexer ein Problem desto mehr Fehler macht man
  * Detailreich ist sehr wartungsintensiv
* Sollte Testbar sein
* Nur so viel, dass der Kunde zufrieden ist, weiteres kommt in der naechsten
  Version
* Vollstaendig
  * Nur was notwendig ist
  * Nur was der Kunde will
* Eindeutig
  * Begriffsabsteckung muss eindeutig sein
  * Sprache eindeutig
  * Wenig Interpretationsraum
  * Bei Fragen praezise und die Antwort zuerst selbst ueberlegen
    * Positive Steuerung auf die "richtige" Antwort
    * Annahmen Treffen mit logischen Schlussfolgerungen

## Programmiersprachen

* Maschinensprachen (Assembler)
  * schwer lesbar
  * richtet sich an den Prozessor
* Hochsprachen
  * gut lesbar
  * richtet sich an den Menschen

Arten von Programmiersprachen

* Objektorientier OOP (Java) 
* Prozedural (C)
* Funktional
* Logisch
* Deklarativ (SQL)

## Algorithmus

*Ein Algorithmus is eine Beschreibung eines Loesungsverfahren*  
Eine Verarbeitunsvorschrift mit definierten Eingangs- und Ausgangsgroessen


Eigenschaften:
* Schrittweise
  * Eines nach dem anderen
  * "Was kommt als naechstes" muss klar sein und keine Entscheidungsspielraeume
    lassen
  * !!Der Prozessor diskutiert nicht!!
* Eindeutig
  * Jede Anweisung/jeder Schritt muss eindeutig sein
  * Was erlaubt ist und was nicht, kommt in die Spezifikation
  * Muss genau definiert sein, wofuer der Algorithmus gebaut und bestimmt ist
    und wofuer nicht (Komplexitaet vermeiden)
* Ausfuehrbarkeit
   Jede Aktion muss fuer den Prozessor moeglich sein
  * Dafuer muss man wissen, was der Prozessor kann
  * Die Frage was der Prozessor versteht muss vorher geklaert werden
* Endlich
  * Zeitlich: ist der Algorithmus irgendwann fertig?  
    Betriebsystem fuehrt endlos Algorithmen aus, so lange, bis man ihn abbricht.  
    Die zeitliche endlichkeit ist Dynamisch
  * Statische Endlichkeit; man kann in endlich vielen Schritten das Problem
    beschreiben. Wenn man zu viele Schritte hat, hat man zu wenig
    analysiert/strukturiert.
