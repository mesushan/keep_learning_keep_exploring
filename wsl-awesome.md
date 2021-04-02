## Customize the WSL / WSL2 in windows
[Best tutorial I found](https://www.the-digital-life.com/awesome-wsl-wsl2-terminal/)

- Installing windows terminal
- WSL terminal with zsh
- Using oh-my-zsh to make prettier
- Using nerd-fonts and powerlevel1ok
- Make background of terminal transparent
- Chaning icons and name of different terminal


Resolving the issue of pip not available in wsl and upgrading python version 
```
sudo apt-get update
sudo apt-get install python3-pip
```

Sometimes, creating virutalenv might not work in wsl as mentioned [here](https://virtualenv.pypa.io/en/latest/installation.html), for that use this command
```
pip3 install virtualenv
python3 -m virtualenv (virtualenv name)
```
