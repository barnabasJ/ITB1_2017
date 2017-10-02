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

## Bits

0 oder 1, koennen aber unterschiedlich interpretiert werden.
* ja/nein
* wahr/falsch
* rechts/links
* Spannung/keine Spannung

Technisch einfach realisierbar.  
Zuverlaessig => nicht anfaellig fuer schwankungen.  
Flexible bezueglich verschiedener Arten von Daten.  

Bitfolgen -> einfache Folgen von einzelnen Bits
* zwei Bits 2^2 = 2\*2 = 4 Werte
* drei Bists 2^3 = 8 Werte
* n Bits 2^n WErte

*8 Bits => 1 Byte*

b.. Bit  
B.. Byte  

kB 2^10 Bytes
MB 2^20 Bytes
GB 2^30 Bytes
TB 2^40 Bytes

kb/s... kilobits per Sekunde => Uebertragungsgeschwindigkeit
kB...   kiloByte => Speicherkapazitaet

## Wort
32 Bit 4 Bytes/Wort
64 Bit 4 Bytes/Wort

| Byte 3 | Byte 2 | Byte 1 | Byte 0 |
Msb                                 Lsb

Msb... Most significant Byte  
Lsb... Least significant Byte  

---

## Anordnung

Big endian => Bytes von links nach rechts (SPARC, IBM Mainframe)
Little endian => Bytes rechts nach links (Intel, Vax, Alpha)


|    |    Big endian     |
|----|----|----|----|----|
| 0  | 0  | 1  | 2  | 3  |
| 4  | 4  | 5  | 6  | 7  |
| 8  | 8  | 9  | 10 | 11 |
| 12 | 12 | 13 | 14 | 15 |

|    |   Little endian   |
|----|----|----|----|----|
| 0  | 0  | 1  | 2  | 3  |
| 4  | 4  | 5  | 6  | 7  |
| 8  | 8  | 9  | 10 | 11 |
| 12 | 12 | 13 | 14 | 15 |

## Signal => Nachricht

* kontinuierliche Funktion (Analog Wert)
* diskrete Funktion (Integriert)
* digitale Funktion (Gerundet)

