# Evens dotfiles

Managed with [chezmoi](https://github.com/twpayne/chezmoi).

## Instructions

1. Clone this repo
2. Create symlink `ln -s ~/.dotfiles/files /Users/evenh/.local/share/chezmoi`
3. Create a config: `mkdir -p ~/.config/chezmoi && touch ~/.config/chezmoi/chezmoi.yaml`.


Edit the configuration to your needs:
```yaml
sourceVCSCommand: git
data:
  git:
    name: My Name
    email: my@email.com
    signingkey: 0xDEADBEEF
```