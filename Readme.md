# Git aliases

## Type on terminal

```json
bash install.sh
```


```bash

# filename: .bash_aliases
# Edit it : gedit ~/.bash_aliases
# filename: .zsh_aliases
# Edit it : gedit ~/.zsh_aliases

# GIT
alias gs='git status'
alias gss='git status'
alias ga='git add .'
alias gcm='git commit -m'
alias gc='git checkout'
alias gcb='git checkout -b'
alias gl='git log --pretty=oneline'
alias gfp='git fetch && git pull origin'
alias gp='git push --set-upstream origin'

# NPM
alias n="npm"
alias nr="npm run"
alias ns="npm start"
alias ns:d="npm run start:dev"
alias nd="npm run dev"
alias nb="npm run build"
alias nw="npm run watch"
alias nwp="npm run watch-poll"
alias ni="npm install"
alias nid="npm install -D"
alias nig="npm install -g"
alias sni="sudo npm install"
alias sni="sudo npm install"
alias snid="sudo npm install -D"
alias snig="sudo npm install -g"

# YARN
alias y="yarn"
alias ys="yarn start"
alias ys:d="yarn run start:dev"
alias yr="yarn run"
alias yd="yarn run dev"
alias yb="yarn run build"
alias ya="yarn add"
alias yad="yarn add -D"
alias yag="yarn add global"
alias sya="sudo yarn add"
alias sya="sudo yarn add"
alias syad="sudo yarn add -D"
alias syag="sudo yarn add global"

# APT
alias s='sudo'
alias au='sudo apt update'
alias ai='sudo apt install'
alias sau='sudo apt update'
alias sai='sudo apt install'

#heroku 
alias h="heroku"
alias hl="heroku login"

# firebase
alias fl="firebase login"
alias fi="firebase init"
alias fd="firebase deploy"


# Laravel
alias p="php"
alias pa="php artisan"
alias pas="php artisan serve"
alias pam="php artisan migrate"
alias pads="php artisan db:seed"


# Makefile
alias m="make"
alias mb="make build"
alias ml="make logs"
alias ms="make start"
alias mst="make stop"
alias kn="sudo killall node"
alias kd="docker kill $(docker ps -q)"

# Composer
alias coi="composer update --ignore-platform-reqs"

```
