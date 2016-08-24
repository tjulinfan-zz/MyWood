1. install zsh: sudo apt-get install zsh
2. on-my-zsh
   * git clone git://github.com/robbyrussell/oh-my-zsh.git ~/.oh-my-zsh
   * cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc
3. download dracula and change the theme of zsh
   * git clone https://github.com/dracula/zsh.git
   * ln -s $DRACULA_THEME/zsh/dracula.zsh-theme $OH_MY_ZSH/themes/dracula.zsh-theme
   * go to ~/.zshrc and set ZSH_THEME="dracula"
   * change %c to %d in theme file, so that prompt will show full path.
4. cat /etc/shells
5. chsh -s $ZSH_PATH


