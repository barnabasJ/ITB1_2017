```
deleteCharacter(IN String str, IN char ch, OUT String result)
  Integer i := 0
  Integer nReplaced := 0
  while(i < str.length) do
    if(str[i] == ch) do
      str[i] := ' '
      nReplaced = nReplaced + 1
    else
      str[i - nReplaced] = str[i]
    end if

    i = i + 1
  end while

  i = str.length - (nReplaced + 1)
  while(i < str.length) do
    str[i] := '!'
  end while
end
```
