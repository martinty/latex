# Latex with Visual Studio Code

Using Visual Studio Code as a Latex editor.

## Setup

Extensions:

- [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)
- [LTeX](https://marketplace.visualstudio.com/items?itemName=valentjn.vscode-ltex)

Install Latex:

```sh
# Arch Linux Family
sudo pacman -S texlive-most

# For Ubuntu, you might need a ppa:
sudo add-apt-repository ppa:jonathonf/texlive
sudo apt update && sudo apt install texlive-full

# Fedora
sudo dnf install texlive-scheme-full

# macOS MacTex Install
brew cask install mactex-no-gui

# Updating the packages
sudo tlmgr update --self && sudo tlmgr update --all
```

Use `minted`:

- [Code Highlighting with minted](https://es.overleaf.com/learn/latex/Code_Highlighting_with_minted)
- [How to install minted in Ubuntu](https://tex.stackexchange.com/questions/40083/how-to-install-minted-in-ubuntu)
- [How to enable `shell escape` -- Visual Studio Code (Latex Workshop extension)](https://tex.stackexchange.com/questions/516604/how-to-enable-shell-escape-or-write18-visual-studio-code-latex-workshop)

## About this document

This latex document is based on a method template from TDT4173 on NTNU.
