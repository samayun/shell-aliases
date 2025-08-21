# Git aliases

## Type on terminal

```json
git clone git@github.com:samayun/shell-aliases.git

cd shell-aliases

bash install.sh
```


```bash

# filename: .bash_aliases
# Edit it : gedit ~/.bash_aliases
# filename: .zsh_aliases
# Edit it : gedit ~/.zsh_aliases

alias c='clear'
alias po='poweroff'

# Makefile
alias m='sudo make'
alias mb='sudo make build'
alias mbl='sudo make build && sudo make logs'
alias md='sudo make destroy'
alias ml='sudo make logs'
alias ms='sudo make start'
alias mst='sudo make stop'
alias kn='sudo killall node'
alias kd='sudo docker kill $(docker ps -q)'



# DOCKER
alias dc='sudo docker container ls'
alias dca='sudo docker container ls -a'
alias drm='sudo docker rm -f'

# GIT
alias gs='git status'
alias gss='git status'
alias gb='git branch'
alias ga='git add .'
alias gcm='git commit -m'
alias gc='git checkout'
alias gcb='git checkout -b'
alias gl='git log --pretty=oneline'
alias gfp='git fetch && git pull origin'
alias gp='git push --set-upstream origin'
alias gpl='git pull'


# NPM
alias n="npm"
alias nr="npm run"
alias ns="npm start"
alias ns:d="npm run start:dev"
alias nd="npm run dev"
alias nb="npm run build"
alias ni="npm install"
alias nid="npm install -D"
alias nig="npm install -g"
alias sni="sudo npm install"
alias sni="sudo npm install"
alias snid="sudo npm install -D"
alias snig="sudo npm install -g"

# PNPM
alias pn="pnpm"
alias pnr="pnpm run"
alias pns="pnpm start"
alias pns:d="pnpm run start:dev"
alias pnd="pnpm run dev"
alias pnb="pnpm run build"
alias pni="pnpm install"
alias pnid="pnpm install -D"
alias pnig="pnpm install -g"
alias spni="sudo pnpm install"
alias spni="sudo pnpm install"
alias spnid="sudo pnpm install -D"
alias spnig="sudo pnpm install -g"

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


alias as="xdotool mousemove 100 300"
alias s30="xdotool click --repeat 240 --delay 10000 4"
alias sh="xdotool click --repeat 2880 --delay 10000 4"



# Composer
alias coi="composer update --ignore-platform-reqs"

```
