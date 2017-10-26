```
countChars(IN String string, OUT Integer count)
  Int i := 0
  Int strLength := string.length
  count := 0

  while (i < stringLength) do
    if (string[i] == 'a' or string[i] == 'A') then
      count++
    end if
    i++
  end while
end
```
