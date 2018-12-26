# Need to install code command

- OpenCommandPalatte(Shift + Command + P)
- Install  Shell Command: Install 'code' command in PATH command.

# Output extensions

```
cd ~./dotfiles/.vscode
code --list-extensions > .vscode/extensions
```

# Install extensions
```
cat ./extensions | while read line
do
  code --install-extension $line
done
```e

