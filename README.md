# BashAlias
### Time saving bash aliases. 

### Add to your ~/.bashrc file.
## if [ -e $HOME/.bash_aliases ]; then
##     source $HOME/.bash_aliases
## fi

### Add to your custom alias file. ex. ~/.my_bash_aliases
# List and Sort
alias lt='ls --human-readable --size -1 -S --classify'
# Use Trash can instead of rm command
alias tcn='mv --force -t ~/.local/share/Trash '
# Change Dir Typos
alias cd..='cd ..'
alias ..='cd ..'
# List Dir Typos
alias dir='ls'
alias sl='ls'
# List Hidden Shortcut
alias ll='ls -lhA'
# List Large Directory
alias lsl='ls -lhFA | less'
# Get Public IP
alias myip='curl http://ipecho.net/plain; echo'
### Grep IP
alias grepip='grep -oE "\b([0-9]{1,3}\.){3}[0-9]{1,3}\b"'
