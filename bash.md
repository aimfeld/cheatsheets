# Bash Cheatsheet

## Shortcuts

Search recent commands (reverse search):

`Ctrl+R`

## Disk usage

List directory sizes in current folder:

`du -sh *` or sorted: `du -sh * | sort -rh` 

Find largest folders in whole system (Disk Usage Analyzer app may be better):

`sudo du -a / | sort -n -r | head -n 50`
