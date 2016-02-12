###### 1. install [neotree](https://github.com/jaypei/emacs-neotree) with package manager

```
[meta]-x package-list-packages
[ctrl]-s neotree
i
x
```


###### 2. Add neotree to config ( aka init.el ) to bind to f8
```
(add-to-list 'load-path "/some/path/neotree") ;; doesnt seem like i need this in emacs.predlude
(require 'neotree)
(global-set-key [f8] 'neotree-toggle)
```
