# swc-lessons-tools

This repo copied `bin` folder, `_config.yml` and `Makefile` from
`https://github.com/carpentries-i18n/shell-novice/tree/653d9d70f9da3e434393fb63b4c3ce2537912c5c`.
The intention here is just to have a easy place to get these files that helps to check swc lessons
that doesn't have these files.

## Setup

1. create a conda environment: `conda env create -n swc-lessons-tools --file environment.yaml`
2. install a ruby dependency: `make install`
3. run the desired (make) command. E.g. `make lesson-check-all`

PS: at this moment just `make install` and `make lesson-check-all` were tested.
