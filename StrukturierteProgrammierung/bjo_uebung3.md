# Aufgabe 1 (Palindrom)

*Loesungsidee*: Ich vergleiche denn ersten und letzten Buchstaben und arbeite
mich von dort in die Mitte

```
isPalindrom(IN String str, OUT Boolean palindrom)
  Integer i := 0
  palindrom := true

  while((i < (str.length/2)) and (palindrom)) do   
    if(str[i] != str[str.length - (i + 1)) then
      palindrom := false
    end if
      i := i + 1
  end while
end isPalindrom
```
![Palindrom Flussdiagramm](./palindromFD.svg)
![Palindrom Struktogramm](./palindromSG.svg)

str := "ROTOR"

|Zeile|str[i]|str[str.length - (i+1)]|i|palindrom|
|---|---|---|---|---|
|2,3|||0|true|
|6|R|R|0|true|
|9|R|R|1|true|
|6|O|O|1|true|
|9|O|O|2|true|

str := "REITTIER"

|Zeile|str[i]|str[str.length - (i+1)]|i|palindrom|
|---|---|---|---|---|
|2,3|||0|true|
|6|R|R|0|true|
|9|R|R|1|true|
|6|E|E|1|true|
|9|E|E|2|true|
|6|I|I|2|true|
|9|I|I|3|true|
|6|T|T|3|true|
|9|T|T|4|true|

str := "BARNABAS"

|Zeile|str[i]|str[str.length - (i+1)]|i|palindrom|
|---|---|---|---|---|
|2,3|||0|true|
|6|B|S|0|true|
|7|B|S|0|false|
|9|B|S|1|false|
