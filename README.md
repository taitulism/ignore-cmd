**PROJECT STATUS:** Works. Linux only. API Could change.  
**CURRENT VERSION:** 0.0.4  
**FOLLOWS SEMVER:** Not yet.  
**DEFAULT BRANCH:** develop  

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)



ignore-cmd
==========
## SHELL SCRIPT

Add paths to .gitignore .npmignore from CLI.  
Creates the ignore file if not exists (e.g. creates `.gitignore`).  
Currently only adds items.


Install
-------
```sh
$ npm install -g ignore-cmd
```


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
Ignore node_modules/ in (g)it:
```sh
$ ignore -g node_modules/
```

<br />

Ignore multiple paths in (b)oth gitignore and npmignore:
```sh
$ ignore -b drafts/ playground/ todo.txt
```
