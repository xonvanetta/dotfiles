# dotfiles with ansible

## TODO
* add timer/config based security scans with clamAV
* fix localectl or add to .xinitrc to set locale

## install requirements
`ansible-galaxy install -r requirements.yml`


# missing go installs
`go install github.com/google/go-jsonnet/cmd/jsonnetfmt@latest`
`go install github.com/brancz/gojsontoyaml@latest`
`go install github.com/jsonnet-bundler/jsonnet-bundler/cmd/jb@latest`