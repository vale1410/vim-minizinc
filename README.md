vim-minizinc
============

Simple vim-Bundle for syntax highlighting for minizinc files and Gringo ASP files. Detects .mzn, .fzn and lp files. 
The definition of the syntax for vim is taken from the official minizinc-1.6 distribution. 



Now add to local bundle configuration and reload vims bundles:

```
$ echo Bundle \'vale1410/vim-minizinc\'  >> ~/.vimrc.bundle.local
$ vim +BundleInstall! +BundleClean +q
```

see for the original highlighting sources: 

* http://www.minizinc.org/
* http://potassco.sourceforge.net/
