# dotfiles with ansible

## TODO
* add timer/config based security scans with clamAV
* fix localectl or add to .xinitrc to set locale

## install before
* python, python-virtualenv and one more

## Archinstall

### URL
`https://raw.githubusercontent.com/xonvanetta/dotfiles/master/user_configuration.json`

### post install
First `sudo su` as the user created to then run the magic

## running this magic
`ansible-playbook desktop.yml -K`

## install requirements
`ansible-galaxy install -r requirements.yml`