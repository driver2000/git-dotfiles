A simple .gitconf Template
==========================

a .gitconf file template

How to install
--------------
```sh
$ git clone https://github.com/driver2000/git-dotfiles.git
$ mkdir ~/git.d
$ ln -s git-dotfiles/gitconfig ~/git.d/gitconfig
```
Git (1.7.10+) now supports this syntax in .gitconfig:

```gitconfig
[include]
    path = ~/git.d/gitconfig
```
Add your user and email
----
```sh
$ git config --local user.name your name
$ git config --local user.email your_mail@mail.com
```
if you want set `user.name` and `user.email` globally use `--global` instead `--local`
or edit the conf file directly :

```
$ git config -e [--global]
```

### Fork it !

