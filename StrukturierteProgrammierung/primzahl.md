# Primzahl

```
isPrime(IN Integer number, OUT Boolean result)
  if (number < 4) then
    result = true
  else 
    Integer divisor := 2
    result = true
    while (divisor < sqrt(number)) do
      if (number mod divisor == 0) then
        result = false
        break
      end if
      divisor = divisor + 1
    end while
  end if
end
```

```
isPrime(IN Integer number, OUT result)
  Integer i := 2
  result = false

  while((i * i < number) and ((number % i ) != 0)) do
    i = i + 1
  end while

  if ((number % i) == 0) then
    result = true
  end if
end isPrime
```

|Schritt|number|i|result|
|---|---|---|---|
|1|7|||
|2|7|2|false|
|3|7|3|false|
|4|7|4|fasle|
|5|7|5|false|
|6|7|6|false|
|7|7|7|false|
|8|7|7|true|
