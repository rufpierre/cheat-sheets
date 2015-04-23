prefix
---
when inside tmux, use *prefix* before each command.  
prefix: `crtl+b`  

session
---
list: `prefix+s` or `tmux ls`  
attach: `tmux a -t SESSION_NAME`  
rename: `prefix $`  
detach (quit): `prefix+d`  
kill: `tmux kill-session -t SESSION_NAME`  

tabs
---
new tab: `prefix+c`  
next tab: `prefix+n`  
previous tab: `prefix+p`  
rename tab: `prefix+,`  
kill: `prefix+&`  

misc
---
copy-mode: `prefix+[`, exit copy-mode: `q`  
