# Aussagenlogik

## Definition:

Unter einer Aussage (Satz) versteht man einen gewoehnlichen Satz unserer Sprache
von dem man eindeutig sagen kann ob er wahr oder falsch ist.

| Satz | Aussage | wahr/falsch|
|---|---|---|
|Wien ist die Hauptstadt Oesterreichs| ja | wahr |
| Ein Dreieck hat 4 Ecken | ja | falsch |
| Guten Tag! | nein | x |
| Dieser Satz ist falsch | nein | Widerspruch |
| Es regnet | ja | falsch |

## Verknuepfungen 

### Und (^)

p... Peter geht ins Kino  
q... Judith geht ins Kino  
p ^ q Peter und Judith gehen ins Kino  
  (Peter geht ins Kino und Judith geht ins Kino)


| p | q | p ^ q |
|---|---|---|
| 1 | 1 | 1 |
| 1 | 0 | 0 |
| 0 | 1 | 0 |
| 0 | 0 | 0 |

### Oder (v)

p... Peter geht ins Kino  
q... Judith geht ins Kino  
p oder q Peter und Judith gehen ins Kino  
  (Peter geht ins Kino und Judith geht ins Kino)


| p | q | p v q |
|---|---|---|
| 1 | 1 | 1 |
| 1 | 0 | 1 |
| 0 | 1 | 1 |
| 0 | 0 | 0 |

### Auschliessendes Oder (xor)

p... Peter geht ins Kino  
q... Judith geht ins Kino  
p xor q Peter oder Judith gehen ins Kino aber nicht beide


| p | q | p xor q |
|---|---|---|
| 1 | 1 | 0 |
| 1 | 0 | 1 |
| 0 | 1 | 1 |
| 0 | 0 | 0 |

### "wenn, dann" (->)

p...  Ich bestehe die Pruefung  
q...  ich gehe Feiern  
p -> q Wenn ich die Pruefung bestehe gehe ich Feiern

| p | q | p -> q |
|---|---|---|
| 1 | 1 | 1 |
| 1 | 0 | 0 |
| 0 | 1 | 1 |
| 0 | 0 | 1 |


### "Genau dann wenn" (<->)

p...  Ich bekomme das Geld  
q...  Ich kaufe ein neues Auto  
p <-> q Genau dann wenn ich ein das Geld bekomme werde ich ein neues Auto kaufen


| p | q | p <-> q |
|---|---|---|
| 1 | 1 | 1 |
| 1 | 0 | 0 |
| 0 | 1 | 0 |
| 0 | 0 | 1 |

### "Hoechstens eine von beiden" (nand)

p...  Die Fussgaengerampel ist gruen  
q...  Die Fussgaengerampel ist rot  
p nand q Die Fussgaengerampel ist hoechstens rot oder hoechstens gruen aber nicht beides.

| p | q | p nand q |
|---|---|---|
| 1 | 1 | 0 |
| 1 | 0 | 1 |
| 0 | 1 | 1 |
| 0 | 0 | 1 |

### "keines von beiden" (nor)

p... Es ist kalt  
q... Es schneit  
p nor q Es ist nicht kalt und es schneit nicht

| p | q | p nor q |
|---|---|---|
| 1 | 1 | 0 |
| 1 | 0 | 0 |
| 0 | 1 | 0 |
| 0 | 0 | 1 |
