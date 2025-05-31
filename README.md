# Debian Installation

### sudo apt install wget curl build-essential unzip python3.11-venv

## Nvm installation

### curl https://raw.githubusercontent.com/creationix/nvm/master/install.sh | bash

### source ~/.profile

### nvm install --lts

## Neovim installation

### curl -LO https://github.com/neovim/neovim/releases/download/stable/nvim-linux-x86_64.tar.gz

### sudo rm -rf /opt/nvim

### sudo tar -C /opt -xzf nvim-linux64.tar.gz

### echo 'export PATH="$PATH:/opt/nvim-linux-x86_64/bin"' >> ~/.profile

### source ~/.profile

## Lazygit installation

### https://github.com/jesseduffield/lazygit/releases

### wget https://github.com/jesseduffield/lazygit/releases/download/v0.51.1/lazygit_0.51.1_Linux_x86_64.tar.gz

### tar -xvf lazygit_0.51.1_Linux_x86_64.tar.gz

### sudo cp lazygit /usr/bin/

### Nvim config clone

### cd ~

### mkdir .config

### cd .config

### git clone https://github.com/emre-yildiz-dev/nvim

### nvim
