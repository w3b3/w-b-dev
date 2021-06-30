# SOME THINGS TO REMEMBER:

- [x] MOVE OS-SPECIFIC INSTRUCTIONS TO INDIVIDUAL GISTS
- [ ] Figure out a way to consistently backup (and restore once things go south), the notebook ubuntu drive
- [ ] Create script to automate environment generation, such as:  
    - [ ] `.zshrc` for custom theme, functions and etc
    - [ ] `.profile`
    - [ ] `.vimrc` to tweak vi
    - [ ] `~/.ssh/` folder with my keys (DOUBLE CHECK IF GPG KEYS ARE HERE)
    - [ ] `.eslintrc` and `.prettierrc` with my base defaults
    - [ ] `.gitconfig` to save me time with personal git preferences
    - [ ] vscode snippets
    - [ ] webstorm snippets
    - [ ] insomnia api collections (already sync'ed [here](https://github.com/w-b-dev/insomnia))

--------

## Ubuntu Setup

- git, curl, node (and node permissions fix), vscode, webstorm, insomnia
- obs, droidcam, gimp, zoom, libreoffice
- kubectl, microk8s, docker
- lutris, wine

## GIT notes

All is [here](https://github.com/w-b-dev/w-b-dev/blob/master/git-notes.md)

--------
## [Mac OS](https://github.com/w-b-dev/w-b-dev/blob/master/macos-setup.md)
## [Windows](https://github.com/w-b-dev/w-b-dev/blob/master/windows-wsl-setup.md)
--------

### Move these shortcuts somewhere else

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
