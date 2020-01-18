# PASSFZF

Copied mostly from [passmenu](https://git.zx2c4.com/password-store/tree/contrib/dmenu/passmenu).

Instead of using dmenu, opens a terminal and grabs the password via fzf.

Calls the copy command via a tmux pane so that the clipboarded password does not disappear when the terminal closes.
