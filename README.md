SublimeLinter-eslint
=========================

This linter plugin for [SublimeLinter](https://github.com/SublimeLinter/SublimeLinter) provides an interface to [ESLint](https://github.com/nzakas/eslint). It will be used with files that have the “javascript” syntax.

## Installation
SublimeLinter 3 must be installed in order to use this plugin. 

Please install via [Package Control](https://sublime.wbond.net/installation).

Before using this plugin, you must ensure that `eslint` is installed on your system. To install `eslint`, do the following:

- Install [Node.js](http://nodejs.org) (and [npm](https://github.com/joyent/node/wiki/Installing-Node.js-via-package-manager) on Linux).

- Install `eslint` globally by typing the following in a terminal:
```
npm install -g eslint
```
    
- Or install `eslint` locally in your project folder (**you must have package.json file there**):
```
npm install eslint
```



## Settings

- SublimeLinter settings: http://sublimelinter.readthedocs.org/en/latest/settings.html
- Linter settings: http://sublimelinter.readthedocs.org/en/latest/linter_settings.html

You can configure `eslint` options in the way you would from the command line, with `.eslintrc` files. For more information, see the [eslint docs](https://github.com/nzakas/eslint/wiki).



## FAQ and Troubleshooting

### I've got 'SublimeLinter: ERROR: eslint cannot locate 'eslint' in ST console when I try to use locally installed `eslint`.

You **must** have `package.json` file if install `eslint` locally. Also, restart project or ST itself after to make sure SublimeLinter uses correct `eslint` instance.

```
npm init -f
npm install eslint
```




