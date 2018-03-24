# SMB3-LordTom-TotalControl-PreTAS-SaveStates
Ripped SaveStates of Lord Tom's Total Control TAS Exploit which showcase SMB3 Exploit to inject arbitrary code and create payloads using controller inputs (P1&amp;&amp;P2). For more info and copyright, see; http://tasvideos.org/4961S.html . This is not my work, I did nothing to accomplish these exploits and controls, nor did I have anything remotely to do with the project. I merely ripped the video, ended the TAS after the payload and before the showcase as seen in his video, save the state to a file to play around with and decided to share it on the internet.

SMB3 Total Control Save State Frame #
SUDO Color-a-dinosaur
13073

WarpTo 2-4 --SuperMetroid
Controls P1; Select = Powerboost; Need to have P-Max to use. Run walk as usual
Frame #0015616              SaveState = "SMB3-TotalControlTomLordStage2.fc0.fcs"
(WARNING; DON'T PRESS START+SELECT ON P2 AT THE SAME TIME)

WarpTo 1-4 --ShellShield
Controls P1; Walk as usual, jump and run. P2; Select = Activate Orbital ShellShield; Start = 7 suit swap selected by in-game timer
(0-7 = 8 bytes cycle)
(WARNING; DON'T PRESS START+SELECT ON P2 AT THE SAME TIME)
Frame #0018379              SaveState = SMB3-TotalControlTomLordStage3.fc0.fcs

WarpTo 8-Tank1 --PwnScroll --Disabled
#0024823

Warpto Bowser --SurpriseMe
#0026919

My Control scheme:
P1 {
    WASD = UP LEFT DOWN RIGHT
    ZXNM = Select Start B A
}
P2 {
    ↑←↓→ = UP LEFT DOWN RIGHT
    RTFG = SELECT START B A
}
