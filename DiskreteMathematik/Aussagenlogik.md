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
p ^ q Peter und Judith gehen ins Kino  
  (Peter geht ins Kino und Judith geht ins Kino)


| p | q | p v q |
|---|---|---|
| 1 | 1 | 1 |
| 1 | 0 | 1 |
| 0 | 1 | 1 |
| 0 | 0 | 0 |

### Oder (_v_)

p... Peter geht ins Kino  
q... Judith geht ins Kino  
p ^ q Peter und Judith gehen ins Kino  
  (Peter geht ins Kino und Judith geht ins Kino)


| p | q | p _v_ q |
|---|---|---|
| 1 | 1 | 1 |
| 1 | 0 | 1 |
| 0 | 1 | 1 |
| 0 | 0 | 0 |
