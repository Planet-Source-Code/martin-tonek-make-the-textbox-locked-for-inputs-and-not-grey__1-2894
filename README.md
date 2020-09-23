<div align="center">

## \!Make the textbox Locked for inputs and NOT grey\!


</div>

### Description

Let you lock your textbox for inputs and it will NOT be grey, but will be able to highlightning and scrolling. One line code is all you need!
 
### More Info
 
add a textbox named Text1.

Thats IT!!

None, More simple then this it will never be!

well if you cant see all text.. just change multiline to true in textbox

properties. But that you already now!! ;-)

More sources avalible on http://hem.passagen.se/tonek/vb

A textbox that you can highlight and scroll but not change


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Martin Tonek](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/martin-tonek.md)
**Level**          |Unknown
**User Rating**    |2.1 (123 globes from 60 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Custom Controls/ Forms/  Menus](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/custom-controls-forms-menus__1-4.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/martin-tonek-make-the-textbox-locked-for-inputs-and-not-grey__1-2894/archive/master.zip)





### Source Code

```
'// Please visit my homepage http://hem.passagen.se/tonek/vb
'// and check out other sources i made..
'//     Martin Tonek <tonek@hem.passagen.se>
Private Sub Form_Load()
'// This will lock the control so you cant make any changes
'// in runmode , false open it up.. default is false
Text1.Locked = True
Text1.Text = "you can scroll and highlight the text in the control" & _
" but you can't edit it. The program can still modify the text by " & _
"changing the Text property"
End Sub
'// I find it in the helpfile...so now you now how. Also want to add that
'// all people using the keyascii code.. this one is better...
'// neet little code free to use
'// Wonder why people is so upset. I just tell this one..
'// so a lot of people that do not use it when it is avalible may use it.
```

