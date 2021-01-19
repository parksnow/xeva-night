# Welcome to your VS Code Extension

## What's in the folder

* This folder contains all of the files necessary for your color theme extension.
* `package.json` - this is the manifest file that defines the location of the theme file and specifies the base theme of the theme.
* `themes/xeva-dark-color-theme.json` - the color theme definition file.

 https://code.visualstudio.com/api/references/theme-color
 https://github.com/primer/github-vscode-theme/blob/master/src/theme.js

## Get up and running straight away

* Press `F5` to open a new window with your extension loaded.
* Open `File > Preferences > Color Themes` and pick your color theme.
* Open a file that has a language associated. The languages' configured grammar will tokenize the text and assign 'scopes' to the tokens. To examine these scopes, invoke the `Inspect TM Scopes` command from the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on Mac) .

## Make changes

* Changes to the theme file are automatically applied to the Extension Development Host window.

## Adopt your theme to Visual Studio Code

* The token colorization is done based on standard TextMate themes. Colors are matched against one or more scopes.

To learn more about scopes and how they're used, check out the [color theme](https://code.visualstudio.com/api/extension-guides/color-theme) documentation.

## Install your extension

* To start using your extension with Visual Studio Code copy it into the `<user home>/.vscode/extensions` folder and restart Code.
* To share your extension with the world, read on https://code.visualstudio.com/docs about publishing an extension.


## Colors

- workbench color setting.
- token color setting.
- use **Inspect TM Scopes** checkout token color setting.

* background: #042b36
* foreground: #a8a8a8

* black   : #1c1c1c
* red     : #ce3035
* green   : #005f00
* yellow  : #cdcd00
* blue    : #5c6bc0
* magenta : #bb4db9
* cyan    : #00a6b2
* white   : #bbbbbb

* lightblack   : #32312f
* lightred     : #f9555f
* lightgreen   : #00d700
* lightyellow  : #ffff55
* lightblue    : #0000ee
* lightmagenta : #ff00ff
* lightcyan    : #00e5e5
* lightwhite   : #ffffff

### Emacs Color

``` lisp
      (red        "#ce3035")
      (coral      "#ff0000")
      (brownred   "#870000")
      (orange     "#ff8700")
      (darkkhaki  "#d7af5f")
      (yellow     "#cdcd00")
      (grassgreen "#afaf00")
      (teagreen   "#004e40")
      (cyangreen  "#00afaf")
      (lightgreen "#00af87")
      (green      "#00d700")
      (cyan       "#00bcd4")
      (steelblue  "#000087")
      (blue       "#0000ee")
      (skyblue    "#2599e0")
      (indigo     "#5c6bc0")
      (violet     "#ba68c8")
      (purple     "#bb4dbf")
      (lightpink  "#d33682")
      (pink       "#e91e63")
      (brown      "#875f00")
      (teal       "#005f00")
      (steelblack "#1c1c1c")
      (gray       "#555")
      (grey       "#7c7c7c")
      (steelgrey  "#32312f")
      (nake       nil)
      (fg         "#a8a8a8")
      (bg         nil)
      (bufferid   "#00f900"))
```
