# wasp-mode

Syntax highlighting for the Wasp programming language in Emacs. Requires Emacs 24.3 or later.

## Installation

You can use built-in package manager (package.el) or do everything by your hands.

### Using package manager

Add the following to your emacs config file

```elisp
(require 'package)
(add-to-list 'package-archives
             '("melpa" . "https://melpa.org/packages/") t)
(package-initialize)
```

Then use `M-x package-install RET wasp-mode RET` to install the mode.
Use `M-x wasp-mode` to change your current mode.

### Manual

Download the mode to your local directory. You can do it through `git clone` command:

```
git clone git://github.com/thechampagne/wasp-mode.git
```

Then add path to wasp-mode to load-path list — add the following to your emacs config file

```elisp
(add-to-list 'load-path
	     "/path/to/wasp-mode/")
(require 'wasp-mode)
```

Use `M-x wasp-mode` to change your current mode.

## License

This repo is released under the [GPL-3.0](https://github.com/thechampagne/wasp-mode/blob/main/LICENSE).
