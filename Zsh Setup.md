# Zsh Setup



## Install Zsh and Oh My Zsh

```bash
# install zsh
sudo apt install zsh

# install oh my zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

# comfirm zsh is successfully installed
zsh

# set zsh as the default shell
chsh -s /bin/zsh
```

### Conda Commend Setup

Open `~/.zshrc`, add 

```bash
source ~/anaconda3/bin/activate
# or
source <Anaconda3 Path>/bin/activate
```

to the file.

![](pictures\p1.png)

Then, 

```bash
source ~/.zshrc
```



## Powerline Font

### On Linux

```bash
sudo apt install fonts-powerline
```

### On Windows

- Download [CascadiaCode-2111.01.zip](https://github.com/microsoft/cascadia-code/releases/download/v2111.01/CascadiaCode-2111.01.zip)
- unzip and copy all the `ttf` files to `C:/Windows/Fonts`

- Restart `Windows Termial`, open `settings`, choose `Cascadia Mono PL` or `Cascadia Code PL`



## Powerlevel10k Theme

### Install and Switch to p10k Theme

- Install p10k theme

  ```bash
  git clone https://github.com/romkatv/powerlevel10k.git ~/.oh-my-zsh/custom/themes/powerlevel10k
  ```

- Open `~/.zshrc`, set 

  ```bash
  ZSH_THEME="powerlevel10k/powerlevel10k"
  ```

### Install Mono Font

- Download [Meslo_LG_M_Regular_Nerd_Font_Complete_Mono](https://github.com/ryanoasis/nerd-fonts/blob/master/patched-fonts/Meslo/M/Regular/complete/Meslo%20LG%20M%20Regular%20Nerd%20Font%20Complete%20Mono.ttf)
- copy the `ttf` file to `C:/Windows/Fonts`

- Restart `Windows Termial`, open `settings`, choose `MesloLGM Nerd Font Mono`

### p10k Theme Configuration

```bash
p10k configure
```

