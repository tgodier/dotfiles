# Set up 

1. sudo apt install git vim 
2. clone repo 
    git clone https://github.com/tgodier/dotfiles.git ~/.dotfiles 
3. cd .dotfiles
4. chmod +x install.sh
5. run ./install.sh
3. symlink: 

````
ln -sv ~/.dotfiles/.vimrc ~

ln -sv ~/.dotfiles/.bashrc ~
````

4. reload bash
    source ~/.bashrc
