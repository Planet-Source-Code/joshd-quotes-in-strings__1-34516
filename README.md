<div align="center">

## Quotes in Strings


</div>

### Description

If you ever wanted to have a string with quotes inside this is a handy tip.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[JoshD](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/joshd.md)
**Level**          |Beginner
**User Rating**    |3.5 (14 globes from 4 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[String Manipulation](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/string-manipulation__1-5.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/joshd-quotes-in-strings__1-34516/archive/master.zip)





### Source Code

To use quotes within strings. ie.<BR>
<b>Call me "Bob" OK</b><br>
<br>
This is hard to define within vb as quotes define the start and end of a string so:<br>
<b>talk = "Call me "Bob" OK"</b><br>
<br>
wont work. You can get around this by usings its ascii value (Chr(34) is equivalent to a quote) however there is an easier way, using double and triple quote marks.<br>
<br>
A double quote within a text string will add a quote into the text so<br>
<b>MsgBox "Hello ""Bob""!"</b><br>
<br>
Will display<br>
<b>Hello "Bob"!</b><br>
<br>
This also works at the start of a string so<br>
<b>MsgBox """Bob"""</b><br>
<br>
Will display<br>
<b>"Bob"</b><br><br><br>
This is a simple tip but will save you alot of effort.

