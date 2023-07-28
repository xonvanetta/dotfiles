# dotfiles with ansible

## TODO
* add timer/config based security scans with clamAV

## install before
* python, python-virtualenv and one more

## running this magic
`ansible-playbook desktop.yml -k -K`

## install requirements
`ansible-galaxy install -r requirements.yml`

### buguntu

1. `#use-ssh-agent` in /etc/X11/Xsession
2. https://bugs.launchpad.net/ubuntu/+source/xorg/+bug/1922414
3. manully build `i3blocks` from repo