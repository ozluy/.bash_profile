### simple shortcuts 
*.bashrc* imports settings from *.bash_profile*, its useful for Visual Studio Code users

#### Color LS
```
colorflag="-G"
alias ls="command ls -a ${colorflag}"
```
####history
```
alias r='reset'
alias clean='reset'
```
#### Git
#### You must install Git first
```
alias gs='git status'
alias ga='git add'
alias gaa='git add *'
alias gc='git commit -m' # requires you to type a commit message
alias gp='git push'
alias gm='git merge' #requires a brach name
alias gr='git reset HEAD'
alias where='echo type "pwd" next time && pwd'
```

# Content
```
alias terminal-reset='reset'
alias terminal-clean='history -c'
alias where='echo type "pwd" next time && pwd'
alias simple-server='python -m SimpleHTTPServer'
alias dr-dev='export ASPNETCORE_ENVIRONMENT=Development && dotnet run'
alias dr-prod='export ASPNETCORE_ENVIRONMENT=Production && dotnet run'

#.Net Core
alias ds='dotnet restore'
alias dr='dotnet run'
```
