prefix
---
when inside tmux, use *prefix* before each command.  
prefix: `crtl+b`  

session
---
list: `tmux ls` or `prefix+s`  
create: `tmux new -s SESSION_NAME`  
attach: `tmux a -t SESSION_NAME`  
rename: `prefix $`  
detach (quit): `prefix+d`  
kill: `tmux kill-session -t SESSION_NAME`  

tabs
---
new tab: `prefix+c`  
next tab: `prefix+n`  
previous tab: `prefix+p`  
goto to tab 5: `prefix+5`  
rename tab: `prefix+,`  
kill: `prefix+&`  

panes
---
split verticaly: `prefix+%`, horizontaly: `prefix+"`  
move to next pane: `prefix+o`  
swap panes: `prefix+crtl+o`  
equaly balance panes horizontaly: `prefix+alt+1`, verticaly: `prefix+alt+2`  
kill pane: `prefix+x`

misc
---
copy-mode: `prefix+[`, exit copy-mode: `q`  
