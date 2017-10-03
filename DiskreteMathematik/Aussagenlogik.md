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

### Und (&#+2227)

p... Peter geht ins Kino  
q... Judith geht ins Kino  
p &#U+2227 q Peter und Judith gehen ins Kino  
  (Peter geht ins Kino und Judith geht ins Kino)


| p | q | p &#U+2227 q |
|---|---|---|
| 1 | 1 | 1 |
| 1 | 0 | 0 |
| 0 | 1 | 0 |
| 0 | 0 | 0 |

### Oder (&#U+2228)

p... Peter geht ins Kino  
q... Judith geht ins Kino  
p &#U+2228 q Peter oder Judith gehen ins Kino  
  (Peter geht ins Kino oder Judith geht ins Kino)


| p | q | p  &#U+2228 q |
|---|---|---|
| 1 | 1 | 1 |
| 1 | 0 | 1 |
| 0 | 1 | 1 |
| 0 | 0 | 0 |

### Auschliessendes Oder (&#U+22BB)

p... Peter geht ins Kino  
q... Judith geht ins Kino  
p &#U+22BB q Peter und Judith gehen ins Kino  
  (Peter geht ins Kino und Judith geht ins Kino)


| p | q | p  &#U+22BB q |
|---|---|---|
| 1 | 1 | 0 |
| 1 | 0 | 1 |
| 0 | 1 | 1 |
| 0 | 0 | 0 |
