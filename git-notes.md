## Git related actions

Some tricks to configure GIT
https://stackoverflow.com/questions/2389361/undo-a-git-merge-that-hasnt-been-pushed-yet?rq=1

- `git config --global core.editor "vi"`
- `git config --global url.ssh://git@github.com/.insteadOf https://github.com/`
- `git config --global pull.rebase true`
- `git config --global help.autocorrect 1`
- `git config --global rebase.autoStash true`

## Since using ZSH and OhMyZsh, most of these are shortcuts

But just in case, here are they listed:

- `git checkout -` to switch between branches quickly
- `git revert HEAD` **double check this one**
- `git branch -m old new` renaming branches
- `git commit --amend -m ”YOUR-NEW-COMMIT-MESSAGE”` amend
- `git reset` unstage all
- `git reset --soft HEAD~1` undo most recent commit
