```
export PS1="\[\e[0;32m\]\u@\h\[\e[0m\] \w \$ "
export SUDO_PS1="\[\e[0;32m\]\u@\h\[\e[0m\] \w \$ "
export AWS_REGION=ap-southeast-2
export AWS_DEFAULT_REGION=$AWS_REGION

alias gis="git status"
alias gicm="git commit -m"
alias gid="git diff"
alias glg="git log --graph --pretty=format:'%Cred%h%Creset %C(cyan)%cd%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit --date=short"
alias gie="git credential-osxkeychain erase"

alias updatedb="sudo /usr/libexec/locate.updatedb"
```
