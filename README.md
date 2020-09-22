<div align="center">

## Add Quotes


</div>

### Description

This Function Adds quotes to a filename... especially useful when sending

an arguement to a program (ie a filename) and it has spaces in it (with spaces

if shows up as multiple arguements.
 
### More Info
 
str is the String to add quotes to.

No real "user notes" here...except it was a pain to think this one up =)

The Fixed String


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Digital](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/digital.md)
**Level**          |Beginner
**User Rating**    |4.2 (67 globes from 16 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[String Manipulation](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/string-manipulation__1-5.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/digital-add-quotes__1-1574/archive/master.zip)

### API Declarations

None


### Source Code

```
Public Function addQuotes(ByVal str As String) As String
    addQuotes = Chr(34) & str & Chr(34)
End Function
```

