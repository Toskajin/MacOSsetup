# Zsh

#### Install zsh

```text
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

#### Step2 Install plugins and  theme

```text
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

```text
git clone https://github.com/zsh-users/zsh-autosuggestions $ZSH_CUSTOM/plugins/zsh-autosuggestions
```

```text
vim ~/.zshrc

plugins=(git zsh-autosuggestions zsh-syntax-highlighting)
```

#### Install Theme

```text
git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k
```

```text
#Set ZSH_THEME=powerlevel10k/powerlevel10k in your ~/.zshrc.

ZSH_THEME="powerlevel10k/powerlevel10k"
```

#### Re-load configuration

```text
source ~/.zshrc
```



