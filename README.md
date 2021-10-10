# docker-baseimage-ubuntu

## Build
```bash
make build
```

## remove imagem
```bash
eval "$(pyenv vars)"
make rmi
```

```text
system/
├── entrypoint.sh
├── etc
│   └── sdk
│       └── config
├── opt
│   └── sdk
│       └── bin
│           ├── entrypoint.sh
│           └── sdk.sh
├── root
│   ├── docker-mods
│   ├── etc
│   │   └── cont-init.d
│   │       ├── 01-envfile
│   │       ├── 10-adduser
│   │       ├── 90-custom-folders
│   │       └── 99-custom-scripts
│   └── usr
│       └── bin
│           └── with-contenv
├── su-exec
│   ├── LICENSE
│   ├── Makefile
│   ├── README.md
│   ├── su-exec
│   └── su-exec.c
└── var
    └── sdk

13 directories, 15 files
```
