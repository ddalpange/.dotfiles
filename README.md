
```
rm ~/.zshrc
rm ~/.bashrc
rm ~/.gitconfig
rm ~/.fzf.zsh
rm ~/.fzf.bash
rm ~/.p10k.zsh
rm ~/.gitconfig
rm ~/Library/Application\ Support/Cursor/User/settings.json
rm ~/Library/Application\ Support/Cursor/User/keybindings.json
rm ~/.cursor/extensions/extensions.json

ln -s ~/.dotfiles/.zshrc ~/.zshrc
ln -s ~/.dotfiles/.bashrc ~/.bashrc
ln -s ~/.dotfiles/.gitconfig ~/.gitconfig
ln -s ~/.dotfiles/.fzf.zsh ~/.fzf.zsh
ln -s ~/.dotfiles/.fzf.bash ~/.fzf.bash
ln -s ~/.dotfiles/.p10k.zsh ~/.p10k.zsh
ln -s ~/.dotfiles/.gitconfig ~/.gitconfig
ln -s ~/.dotfiles/.cursor/settings.json ~/Library/Application\ Support/Cursor/User/settings.json
ln -s ~/.dotfiles/.cursor/keybindings.json ~/Library/Application\ Support/Cursor/User/keybindings.json
ln -s ~/.dotfiles/.cursor/extensions.json ~/.cursor/extensions/extensions.json

defaults -currentHost write -globalDomain NSStatusItemSelectionPadding -int 5
defaults -currentHost write -globalDomain NSStatusItemSpacing -int 5

```

# .dotfiles
