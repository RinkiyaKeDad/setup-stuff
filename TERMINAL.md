# Terminal Config


## Steps
1. Get [Homebrew](https://brew.sh/).
2. Get iTerm2: `brew install --cask iterm2`
3. Get [oh my zsh](https://ohmyz.sh/).
4. Get [powerlevel10k](https://github.com/romkatv/powerlevel10k) using the install via oh my zsh option. (Custom oh my zsh theme)

### Custom plugins for oh my zsh

1. Get [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md#with-a-plugin-manager) using the install via oh my zsh option.
2. Get [zsh-auto-suggestions](https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md#oh-my-zsh). Then to fix the partial suggestion accepting feature follow [this](https://stackoverflow.com/a/31328973) for iTerm2.
3. [Guide](https://github.com/ohmyzsh/ohmyzsh/wiki/Plugins) for adding plugins to oh my zsh.

Current plugins:
```
plugins=(git golang zsh-autosuggestions kubectl zsh-syntax-highlighting)
```

> Remember to keep `zsh-syntax-highlighting` at the end.

### Preferences
1. Color theme for everywhere: [Night Owl](https://github.com/sdras/night-owl-vscode-theme)


## Add these to VS Code terminal
1. Add these in the `settings.json`:
```
"terminal.external.osxExec": "iTerm.app",
"terminal.integrated.shell.osx": "/bin/zsh",
"terminal.integrated.fontFamily": "MesloLGS NF"
```

## References
1. https://commandlinepoweruser.com
2. https://stackoverflow.com/questions/29957456/change-default-terminal-app-in-visual-studio-code-on-mac
3. https://blog.logrocket.com/set-up-macbook-for-web-development-in-20-minutes/
4. https://medium.com/ayuth/iterm2-zsh-oh-my-zsh-the-most-power-full-of-terminal-on-macos-bdb2823fb04c
5. https://safjan.com/top-popular-zsh-plugins-on-github/