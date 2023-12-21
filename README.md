# dotfiles with ansible

## TODO
* add timer/config based security scans with clamAV

## Archinstall

### URL
`https://raw.githubusercontent.com/xonvanetta/dotfiles/master/user_configuration.json`

### post install
First `sudo su` as the user created to then run the magic

## running this magic
`ansible-playbook desktop.yml -K`

## install requirements
`ansible-galaxy install -r requirements.yml`