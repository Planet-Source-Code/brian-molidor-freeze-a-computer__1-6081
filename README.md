<div align="center">

## Freeze a computer\!


</div>

### Description

Ever want to freeze a computer? Well, here is some code to do it. It manipulates the API 'setparent'
 
### More Info
 
Well, Duh. your computer will freeze


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Brian Molidor](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/brian-molidor.md)
**Level**          |Intermediate
**User Rating**    |4.3 (39 globes from 9 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Complete Applications](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/complete-applications__1-27.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/brian-molidor-freeze-a-computer__1-6081/archive/master.zip)





### Source Code

```
Public Declare Function SetParent Lib "user32" Alias "SetParent" (ByVal hWndChild As Long, ByVal hWndNewParent As Long) As Long
function freeze_computer(frm as form)
 call SetParent(frm.hwnd, frm.hwnd)
end function
```

