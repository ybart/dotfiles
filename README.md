# Installing Developer Tools

1. Open Terminal
2. Type git
3. Choose to install developer tools
4. Generate secure identity key pair and add it to SSH Agent & GitHub account
    - https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/
    - https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/

# Bootstrap dotfiles

1. cd ~
2. git clone git@github.com:ybart/dotfiles.git
3. ./dotfiles/bin/dotfiles setup

# Track a dotfile

You can track a dotfile by issuing the following command:

./dotfiles/bin/dotfiles add .gitconfig Brewfile

# TODO

- Setup Oh-my-zsh
- Setup Editor configuration / Plugins
- Terminal settings
- System configuration
- Add dotfiles to path
