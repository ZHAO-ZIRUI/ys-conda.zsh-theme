# ys-conda.zsh-theme

A modified ys theme for oh-my-zsh to adapt conda env

## How to use

1. Download to zsh theme folder
   ```
   curl https://raw.githubusercontent.com/ZHAO-Zirui/ys-conda.zsh-theme/main/ys-conda.zsh-theme >> ~/.oh-my-zsh/themes/ys-conda.zsh-theme
   ```
   
3. Edit `.zshrc`
   ```
   ZSH_THEME="ys-conda"
   ```

4. Disable conda default display
   ```
   conda config --set changeps1 False
   ```

5. Reload zsh
   ```
   source ~/.zshrc
   ```
