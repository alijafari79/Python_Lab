# Oh my zsh

## Download & Install :
```
wget https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh
sh install.sh
```

## Enabling Plugins (zsh-autosuggestions & zsh-syntax-highlighting)
 - Download zsh-autosuggestions by
 
 ```
 git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions
 ```
 
 - Download zsh-syntax-highlighting by
 
 ```
 git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting
 ```

 - `nano ~/.zshrc` find `plugins=(git)`
 
 ```
 nano ~/.zshrc
 ```
 
 - Append `zsh-autosuggestions & zsh-syntax-highlighting` to  `plugins()` like this 
 
 `plugins=(git zsh-autosuggestions zsh-syntax-highlighting)`
 ```
 zsh-autosuggestions zsh-syntax-highlighting
 ```
 
 - Reopen terminal

### Ref
 - [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)
 - [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)
 - [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)
 - https://github.com/alijafari79/oh-my-zsh/
