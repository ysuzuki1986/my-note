## 開発環境 - セッティング
### OS
* Ubuntu 18.04 LTS

### Terminal/shell
* byobu  
```$ sudo apt install byobu ```
* zsh  
```
$ sudo apt install zsh
$ chsh
  -> /usr/bin/zsh
$ sudo apt install koh-my-zsh
```

### Editor
* [VS Code](https://www.microsoft.com/ja-jp/dev/products/code-vs.aspx)
  * vscodevim.vim
  * bierner.markdow

### Tools
* [ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#latest-releases-via-apt-ubuntu)
```
$ sudo apt-get update
$ sudo apt-get install software-properties-common
$ sudo apt-add-repository ppa:ansible/ansible
$ sudo apt-get update
$ sudo apt-get install ansible
```