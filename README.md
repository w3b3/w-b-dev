# New Machine Setup

Do have backup for:

- SSH keys
- GPG
- 2-step codes for some services

---

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

---

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
