

evil 为emacs绑定vim键

```sh
git clone https://github.com/emacs-evil/evil ~/.emacs.d/evil
```

编辑`~/.emacs`

```shell
(add-to-list 'load-path "~/.emacs.d/evil")
(require 'evil)
(evil-mode 1)
```



**siderbar**