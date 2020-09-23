<div align="center">

## Easy £lî&\#8224;ë Text\!


</div>

### Description

I've had a lot of people ask me how to create "Elite" text or "Funky" looking text, so here it is. The coding is extremely simple and it's commented. No votes unless this really helps you or something!
 
### More Info
 
Do this:

1) Start up a new project in VB.

2) Add a command button and a Text Box.

3) Thats all! Insert the below code into the command buttons "Click" event.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[SeeD](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/seed.md)
**Level**          |Beginner
**User Rating**    |3.5 (28 globes from 8 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0, VB Script, ASP \(Active Server Pages\) 
**Category**       |[String Manipulation](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/string-manipulation__1-5.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/seed-easy-l-8224-text__1-9803/archive/master.zip)





### Source Code

```
Private Sub Command1_Click()
Text1.Tag = "" 'clears tag each click
For i = 1 To Len(Text1)
strnew = Mid(Text1, i, 1)
 If strnew = "a" Then strnew = "ã" 'converts each letter
 If strnew = "A" Then strnew = "Ä" 'you can edit these
 If strnew = "b" Then strnew = "b"
 If strnew = "B" Then strnew = "ß"
 If strnew = "c" Then strnew = "ç"
 If strnew = "C" Then strnew = "Ç"
 If strnew = "d" Then strnew = "ð"
 If strnew = "D" Then strnew = "Ð"
 If strnew = "e" Then strnew = "ë"
 If strnew = "E" Then strnew = "£"
 If strnew = "f" Then strnew = "&#402;"
 If strnew = "F" Then strnew = "F"
 If strnew = "g" Then strnew = "g"
 If strnew = "G" Then strnew = "G"
 If strnew = "h" Then strnew = "h"
 If strnew = "H" Then strnew = "H"
 If strnew = "i" Then strnew = "ï"
 If strnew = "I" Then strnew = "Î"
 If strnew = "j" Then strnew = "J"
 If strnew = "J" Then strnew = "¿"
 If strnew = "k" Then strnew = "l&#8249;"
 If strnew = "K" Then strnew = "\<"
 If strnew = "l" Then strnew = "|"
 If strnew = "L" Then strnew = "(_"
 If strnew = "m" Then strnew = "m"
 If strnew = "M" Then strnew = "/V\"
 If strnew = "n" Then strnew = "ñ"
 If strnew = "N" Then strnew = "Ñ"
 If strnew = "o" Then strnew = "ø"
 If strnew = "O" Then strnew = "Õ"
 If strnew = "p" Then strnew = "Þ"
 If strnew = "P" Then strnew = "þ"
 If strnew = "q" Then strnew = "q"
 If strnew = "Q" Then strnew = "Ø"
 If strnew = "r" Then strnew = "R"
 If strnew = "R" Then strnew = "r"
 If strnew = "s" Then strnew = "&#353;"
 If strnew = "S" Then strnew = "&#352;"
 If strnew = "t" Then strnew = "&#8224;"
 If strnew = "T" Then strnew = "t"
 If strnew = "u" Then strnew = "ú"
 If strnew = "U" Then strnew = "Ü"
 If strnew = "v" Then strnew = "V"
 If strnew = "V" Then strnew = "\/"
 If strnew = "w" Then strnew = "vv"
 If strnew = "W" Then strnew = "VV "
 If strnew = "x" Then strnew = "X"
 If strnew = "X" Then strnew = "><"
 If strnew = "y" Then strnew = "ÿ"
 If strnew = "Y" Then strnew = "¥"
 If strnew = "z" Then strnew = "Z"
 If strnew = "Z" Then strnew = "z"
'add new character one at a time:
Text1.Tag = Text1.Tag + strnew
Next i
Text1.Text = Text1.Tag
End Sub
```

