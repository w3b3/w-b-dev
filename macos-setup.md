## New Mac Setup

### Terminal

- `zsh` comes by default nowadays (Catalina I would say)
- get [homebrew](https://brew.sh/)
    - `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
- [ohmyzsh](https://ohmyz.sh/)
  - `sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
- iterm2
  - `brew install --cask iterm2`
- powerlevel10k
  - `brew install romkatv/powerlevel10k/powerlevel10k`
  - `p10k configure` to get fonts [powerlevel10k](https://github.com/romkatv/powerlevel10k#meslo-nerd-font-patched-for-powerlevel10k)
  - ~~ZSH_THEME="powerlevel10k/powerlevel10k"~~

#### Custom entries in `.zshrc`
```
plugins=( git zsh-syntax-highlighting zsh-autosuggestions)
eval "$(ssh-agent -s)"
ZSH_THEME="powerlevel10k/powerlevel10k"
```

  Project specific
  - source ~/code/astra-ui/app/bashrc

#### *Don't forget NVM* `brew install nvm`
```
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"
```

##### Generic aliases
```
alias latest="gf && gl"
alias master="gcm && glo"
alias ngrok="~/Downloads/ngrok http 3000"
```

#### Custom, project-specific aliases
**TODO: improve this!**
```    
alias ui="gcm && latest && rmall && npmall && sourceastraui && runbe; runfe"
alias runfe="cd /Users/.../app/ && pwd"
alias runbe="cd /Users/.../graphql/ && back-end; graphql-remote"
alias sourceastraui="source /Users/.../app/bashrc; source /Users/.../graphql/bashrc"
alias npmall="cd /Users/.../app/ && npm i; cd /Users/.../graphql/ && npm i"
alias rmall="rm -rf /Users/.../app/node_modules; rm -rf /Users/.../graphql/node_modules"
``` 
