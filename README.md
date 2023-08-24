#IfWinActive, Counter-Strike: Global Offensive

$Space::
While GetKeyState("Space", "P")
{
    Send, {a down}
    Sleep, 50
    Send, {a up}
    Send, {d down}
    Sleep, 50
    Send, {d up}
}
return

#IfWinActive
