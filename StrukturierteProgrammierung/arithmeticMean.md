```
arithmeticMean(IN Integer[] values[], OUT Real mean)
  mean := 0.0
  if(values.length > 0) then
    Integer i := 0
    while(i < values.length) do
      mean = mean + values[i]
      i = i + 1
    end while
    mean = mean / values.length
  end if
end
```

values = {1,2,3,4,5}

|Zeile|values[i]|mean|i|
|---|---|---|---|
|2||0.0||
|4||0.0|0|
|6,7|1|1.0|1|
|6,7|2|3.0|2|
|6,7|3|6.0|3|
|6,7|4|10.0|4|
|6,7|5|15.0|5|
|9||3.0|5|
