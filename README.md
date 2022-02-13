> remove layers of complexity.


## Usage

```
$ cd myapp
$ git init
$ podi init git@myserver:/dir/to/deploy
.pod dir created
$ git push git@myserver
# PROFIT!
```

## Install

```bash
$ wget "https://raw.githubusercontent.com/coderofsalvation/podi/master/podi"
$ chmod 755 podi
$ ./podi
usage: 
    init git@server:/dir/to/deploy [branch] [port] [name]   initializes a deployment 
    recipe <name_or_url>                                    installs a recipe from podi repo or url
```

## Docs

* [adding your own recipes](doc/recipes.md)
