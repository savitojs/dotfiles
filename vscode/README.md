# Config for VSCode

This section is not automated intentionally, However, you can add [vscode submodule for dotbot](https://github.com/hujianxin/dotbot-vscode)

```bash
code --list-extensions > vscodefile
```

Submodule

```bash
[submodule "lib/whichcraft"]
 	path = lib/whichcraft
	url = https://github.com/pydanny/whichcraft
```

## Install packages

```bash
vscode.py -c vscode.packages.conf.yaml
```