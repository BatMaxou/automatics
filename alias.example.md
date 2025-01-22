# Alias example

## LAUNCH
alias memo="vi *$CLONE_PATH*/automatics/memo/auto_run.txt"

alias auto-up="bash *$CLONE_PATH*/automatics/bash/auto_up $1"
alias auto-run="bash *$CLONE_PATH*/automatics/bash/auto_run $1 $2"
alias increase-watch="bash *$CLONE_PATH*/automatics/bash/increase_watch"
alias launch-project="cd *dir_which_contains_project* && auto-up project-docker && increase-watch && auto-run project-node && cd ~/"

## STOP
alias auto-stop="bash *$CLONE_PATH*/automatics/bash/auto_stop $1"
alias auto-kill="bash *$CLONE_PATH*/automatics/bash/auto_kill $1"
alias stop-project="cd *dir_which_contains_project* && auto-stop project-back && auto-kill project-node && cd ~/"
