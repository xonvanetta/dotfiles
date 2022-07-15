# dotfiles with ansible

## TODO
* add timer/config based security scans with clamAV
* fix localectl or add to .xinitrc to set locale

## install before
* python, python-virtualenv and one more

## running this magic
`ansible-playbook desktop.yml -k -K`

## install requirements
`ansible-galaxy install -r requirements.yml`