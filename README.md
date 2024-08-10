# Debian Installation

### sudo apt install wget curl build-essential unzip python3.11-venv

## Nvm installation

### curl https://raw.githubusercontent.com/creationix/nvm/master/install.sh | bash

### source ~/.profile

### nvim install --lts

## Neovim installation

### curl -LO https://github.com/neovim/neovim/releases/latest/download/nvim-linux64.tar.gz

### sudo rm -rf /opt/nvim

### sudo tar -C /opt -xzf nvim-linux64.tar.gz

### export PATH="$PATH:/opt/nvim-linux64/bin"

## Lazygit installation

### https://github.com/jesseduffield/lazygit/releases

### wget https://github.com/jesseduffield/lazygit/releases/download/v0.43.1/lazygit_0.43.1_Linux_x86_64.tar.gz

### tar -xvf lazygit_0.43.1_Linux_x86_64.tar.gz

### sudo cp lazygit /usr/bin/

## Nvim config clone

### cd .config

### git clone https://github.com/emre-yildiz-dev/nvim

### nvim
