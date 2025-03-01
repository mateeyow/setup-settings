# Some of my personal installations

## ZSH

- https://github.com/sindresorhus/fkill-cli
- https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md
- https://github.com/zsh-users/zsh-autosuggestions
- https://github.com/wting/autojump

### Plugins

```
plugins=(
          git
          zsh-syntax-highlighting
          zsh-autosuggestions
          node
          docker
          autojump
 )
```

## TMUX

- https://mutelight.org/practical-tmux

## Iterm2 Settings

Preferences > Keys > Hotkey > Create a Dedicated Hotkey Window

Enable:
- Pin hotkey window
- Floating window

### Profile

General:
- Working Directory: Advanced Configuration - Working Directory for Split Panes: Reuse previous session's directory

Window:
- Screen: Screen with cursor

Terminal:
- Unlimited scrollback

Keys:
- Tick Esc+ on **Left Option Key**:
- Add hotkey for **Send escape sequence**: Send (option backward) keys b/f (backward or forward)
<img width="505" alt="Screenshot 2022-03-04 at 14 53 13" src="https://user-images.githubusercontent.com/6420838/156714343-170f4b70-f7a3-4ec9-8649-f559a9ac17a5.png">


### Appearance

General:
- Exclude from Dock... + ...but only if....

<img width="587" alt="image" src="https://user-images.githubusercontent.com/6420838/114260190-d5f43f00-9a05-11eb-954b-6618bbb36625.png">


## Multiple User Git

https://superuser.com/a/1664624

This setup will set the `.gitconfig` depending on where you will be running the `git` command

ALSO:
- https://stevenharman.net/configure-ssh-keys-for-multiple-github-accounts
- https://www.benji.dog/articles/git-config/

## Go private module

To allow go to download private packages, you need to create `.netrc` file under `$HOME/.netrc`
