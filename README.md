alias +mfwd "-back;+forward;alias checkfwd +forward"

alias +mback "-forward;+back;alias checkback +back"

alias +mleft "-moveright;+moveleft;alias checkleft +moveleft"

alias +mright "-moveleft;+moveright;alias checkright +moveright"

alias -mfwd "-forward;checkback;alias checkfwd none"

alias -mback "-back;checkfwd;alias checkback none"

alias -mleft "-moveleft;checkright;alias checkleft none"

alias -mright "-moveright;checkleft;alias checkright none"

alias checkfwd none

alias checkback none

alias checkleft none

alias checkright none

alias none ""

bind "w" "+mfwd" //default "+forward"

bind "a" "+mleft" //default "+moveleft"

bind "s" "+mback" //default "+back"

bind "d" "+mright" //default "+moveright"
