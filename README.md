# Dconf tui editor

A simple tui dconf editor for your terminal written in bash.
It uses `fzf` and `dconf` to edit your dconf settings. It lets you confirm all actions to prevent accidental breakage, has multiple features (browsing, changing values, resetting values, watching), and is very simple to use.

I think it's pretty stable to use, but if you find any bugs, please report them.
The dependencies are `fzf`, `dconf`, `tput`, and `bash` (hah, unexpected for a bash script...).

# How to install
1. Please install all dependencies (`fzf`, `dconf`, `tput`, and `bash`)
2. Place the script somewhere
3. execute it (you can use a `./` syntax, just make sure it is executable.)
