# Summary:

- [New machine setup](#a)
- [Backups](#b)
- [Snippets for VS Code](#c)
- [TODO](#d)

<!-- REFERENCE #A -->

<a name="a"></a>

---

# New Machine Setup

## Inside the Windows Host

- Getting Windows updated to latest
- Upgrade Windows version to Professional
- Enable WSL 2, and set it as default
- Install Debian distro (convert to WSL 2 if needed)
- Install Windows Terminal from the store
- Install Docker
- Install VS Code
- Configure terminal to be zsh
- Sync VS Code extensions

## Inside the VM

- Update distro `sudo apt get update`
- Install Git `sudo apt install git`
- Restore all .ssh entries from backup and fix folder permissions
- Install curl `sudo apt install curl`
- Install NVM https://github.com/nvm-sh/nvm
- Install latest Node `nvm install 14`
- Install yarn without node https://classic.yarnpkg.com/en/docs/install/#debian-stable
- Install ZSH https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH
- Install Oh My Zsh https://github.com/ohmyzsh/ohmyzsh
- Sync VS Code extensions (from host to gues:::debian)
  - restore Quokka license
  - create a .eslintrc on ~/
  - create a .prettierrc on ~/

<!-- REFERENCE #B -->

<a name="b"></a>

---

# Backups:

- SSH keys
- GPG (_how to backup this one?_)
- 2-step codes for some services
  - GitHub
  - Lastpass
  - Microsoft
  - Google

<!-- REFERENCE #C -->

<a name="c"></a>

---

# Snippets

_JavaScript_

- cl "CONSOLE.LOG"
- mq "BASE MEDIA QUERY"
- js-s "USE STRICT"
- jsdoc "ADD BASIC JSDOC TEMPLATE"
- jsa "ADD ARROW FUNCTION"
- fetch and process promise, (if async, inside try catch?)

_Typescript_

- ??? add interface
- ??? Partial or some other notes/documentation

_React_

- ??? useEffect unsubscribe
- ??? react memo
- ??? notes/documentaion

_Jest_

- desc SETUP INITIAL DESCRIBE BLOCK
- it??? ADD ASSERTION TEMPLATE
- ??? mock functions
- notes/docs

_Redux_

- ??? ADD BOILERPLATE FOR BASIC REDUX(DUCKS)
- ??? Setup Thunks
- ??? Setup Redux-saga
- Notes

_Node_

- ??? Express base
- ??? HTTP requests and streams 101
- ??? Notes on documentation

<!-- REFERENCE #D -->

<a name="d"></a>

---

# TODO

- Create script to automate environment generation (linux only)
