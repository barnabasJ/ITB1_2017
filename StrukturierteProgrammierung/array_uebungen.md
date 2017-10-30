```
searchValue(IN Integer[] values, IN Integer value, OUT index)
  Integer i := 0
  while (i < values.length and values[i] != value) do
    i = i + 1
  end while

  if (i >= values.length) then
    index := -1
  else
    index := i
  end if
end searchValue

/**************** 
  index zurueck liefern anstelle der zahl 
  um das problem mit leeren arrays zu
  umgehen
****************/
max(IN Integer[] values, OUT Integer maxValue)
  if(values.length >= 1) then
    Integer i := 1
    maxValue := values[0]

    while(i < values.length) do
      if(maxValue < values[i]) then
        maxValue := values[i]
      end if
      i := i + 1
    end while
  else
    maxValue := 0 
  end if
end max

max(IN Integer[] values, OUT Integer index)
  if(values.length >= 1) then
    Integer i := 1
    index := 0

    while(i < values.length) do
      if(value[index] < values[i]) then
        index := i 
      end if
      i := i + 1
    end while
  else
    index := -1 
  end if
end max
```
