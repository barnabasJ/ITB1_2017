# Informationsdarstellung

## Zahlendarstellung:
  * Binaerzahlen
  * Hexadezimalzahlen
  * Oktalzahlen
  * Negative Binaerzahlen
  * Gleikommazahlen

## Zeichenkodierung:
  * Standard
  * Fehlererkennede (laesst einen Fehler erkennen)
  * Fehlerkorriegierende (laesst einen Fehler erkennen und zeigt auf wo er sich
    befindet)

## Datenkommpression:
  * Huffman Code
  * LZW

## Nachricht:

Eine Zeichenfolge die ueber einen Kanal uebertragen wird.

Sender(Quelle) -> Codierer -> Kanal -> Decodierer -> Empfaenger(Senke)

## Alphabet (Menge von Zeichen):
  * {1,2,3,...,9}  endliche Menge der Zahlen von 0 bis 9
  * {a,b,c,d,.,z}  endliche Mengen der Kleinbuchstaben von a bis z
  * {1,2,3,....}   unendliche Menge der natuerlichen Zahlen

Eine Nachricht wird aus Zeichen eines Alphabetes gebildet. Sie muss nicht enlich
aber zaehlbar sein.

*Nachrichtenraum*: Menge der Nachrichten die mit den Zeichen eines Alphabets (A)
gebildet werden kann A\* ueber A.

## Information

Information ist eine interpraetierte Nachricht. Sie kann auf verschiedene
Weisen interpretiert werden und ist daher subjektiv.

*Daher Information ist Kontext abhaengig. Nachricht ist eindeutig*

## Uebertragung
  * akustisch
  * elektrisch
  * ...

---

## Codierung

Die Codierung ist eine Represaentation von Information.  
Sie bestimmt: 
  * Effizenz (Speicher, Zeit)
  * Zuverlaessigkeit (Rauschen, Fehlertoleranz)
  * Sicherheit (Verschluesselung)


*Die Menge der zulaessigen Zeichen ergibt das Alphabet eines Codes*

Der Code bildet Zeichen eines Zeichenformats auf die Zeichen eines zweiten
Zeichenformats ab (Uebersetzung).

Die Kombination mehrerer Zeichen nennt man ein *Wort*  
Oft werden Codes mit konstanter Wortlaenge verwendet => Alle Codewoerter sind gleich lang.
Die Anzahl der moeglichen Codewoerter kann mit der Formel N=a^n  
N.. Anzahl der moeglichen Codewoerter  
a.. Anzahl der Zeichen  
n.. Wortlaenge  
