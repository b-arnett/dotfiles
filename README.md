# dotfiles
Personal dot files

1.  Install command line toola
    # Apple CLI (mac)
    xcode-select --install

2. Clone repo into new hidden directory

    git clone https://github.com/b-arnett/dotfiles.git ~/.dotfiles


3. Create symlinks in the home directory to the real files in repo

    # Look into install scripts and bootstrapping tools to automate this

    ln -s ~/.dotfiles/.config ~/.config

4. Install Nix, followed by the related packages 
    # figure out process for this 



