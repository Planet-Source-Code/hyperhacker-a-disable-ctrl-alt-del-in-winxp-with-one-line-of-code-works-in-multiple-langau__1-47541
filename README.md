<div align="center">

## a \-\-\> Disable Ctrl\+Alt\+Del in WinXP with ONE LINE OF CODE\! WORKS IN MULTIPLE LANGAUGES\!\<\-\-


</div>

### Description

Super-simple way to disable Ctrl+Al+Del (but not Alt+Tab) in Windows XP and probably NT/2K as well. Anyone can do it, and it works in any language that lets you launch another app! How cool is that?
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[HyperHacker](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/hyperhacker.md)
**Level**          |Beginner
**User Rating**    |3.2 (35 globes from 11 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/hyperhacker-a-disable-ctrl-alt-del-in-winxp-with-one-line-of-code-works-in-multiple-langau__1-47541/archive/master.zip)





### Source Code

While there is a good submission relating to making your app Task Manager-Proof, I haven't seen one that tells how to actually disable Ctrl+Alt+Del. In about 5 minutes I came up with a way to do it, with only one line of code, in just about any programming language! O_O<br>
<br>
What you wanna do is launch taskmgr.exe, then hide it. For an always-on-top fullscreen form (IE a lockout screen) that should take about one line of code. In VB for example, <i>shell "taskmgr.exe"</i> followed by the code which makes your window always on top (which doesn't count since you were doing that anyway).<br>
<br>
So why does just launching the Task Manager disable the 3 magic buttons? Doesn't it defeat the purpose? No. Observe: When the Task Manager is open already and you hit Ctrl+Alt+Del again, it merely brings focus to the Task Manager. But when another window of yours is on top, it keeps focus (so long as you launched Task Manager before making your program Always On Top) and the user can't access the Task Manager!
<br>
<br>
<b>NOTE:</b> Don't do this on Win9x/WinME. In them, when the Task Manager is open and you hit Ctrl+Alt+Del, your computer reboots. ^_^ It's not hard to disable in those anyway.

