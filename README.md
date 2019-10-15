This repository contains instructions for setting up everything that I need

# Editors

## Visual Studio Code

[Visual Studio Code](https://code.visualstudio.com/) is my current preferred general purpose editor.  

### Extensions

#### Must Have
- Python
- Vim
- [VSpaceCode](https://github.com/VSpaceCode/VSpaceCode)

#### Specific Use Case
- Docker

## Spacemacs<a id="sec-1" name="sec-1"></a>

If using spacemacs, use my [dotspacemacs](https://github.com/waynchi/dotspacemacs) configuration

### MELPA<a id="sec-1-1" name="sec-1-1"></a>

    (require 'package)
    (add-to-list
     'package-archives
     '("melpa" . "https://stable.melpa.org/packages/")
     t)
     
# Color Scheme

I use the [Dracula](https://draculatheme.com/) theme.

- [Visual Studio Code](https://draculatheme.com/visual-studio-code/)
- [Powershell](https://github.com/dracula/powershell)
