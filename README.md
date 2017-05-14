**PROJECT STATUS:** Just got started. Nothing to see here.  
**CURRENT VERSION:** `0.0.1`  
**FOLLOWS SEMVER:** Not yet.  
**DEFAULT BRANCH:** `develop`  

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)



ignore-cmd
==========
Add paths to .gitignore .npmignore from cmd.  
Creates the ignore file if not exists (e.g. creates `.gitignore`).  
Currently only adds items.




Usage
-----
```sh
Usage:    ignore <flag> <path> [...paths]

    flag      -g  add to .gitignore
              -n  add to .npmignore
              -b  add to both

    path       The path you want to ignore (e.g. /node_modules/)

    paths      Ignore multiple paths
```




Examples
--------
```sh
# Ignore node_modules/ in (g)it
$ ignore -g node_modules/
```

```sh
# Ignore multiple paths in (b)oth gitignore and npmignore
$ ignore -b drafts/ playground/ todo.txt
```
