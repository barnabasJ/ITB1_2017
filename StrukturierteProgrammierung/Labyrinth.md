## Labyrinth

```
 #########
x  #     #
 #       #
 # #      o
 #########
```

x... Maus  
\#... Wand  
o... Ausgang  

## Maus

**Faehigkeiten**:
* move
* turn_left
* turn_right
* is_wall_infront
* is_maze_left

## Algorithmus

```
FindWay do
  -- enter maze
  move
  while not is_maze_left do
    -- mache einen Schritt
    turn_right
    while is_wall_infront do
      turn_left
    end while
    move
  end while
end
```
