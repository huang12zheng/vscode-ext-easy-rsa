# Welcome to your VS Code Extension

## What's in the folder

* This folder contains all of the files necessary for your extension.
* `package.json` - this is the manifest file in which you declare your language support and define the location of the grammar file that has been copied into your extension.
* `syntaxes/vars.tmLanguage.json` - this is the Text mate grammar file that is used for tokenization.
* `language-configuration.json` - this is the language configuration, defining the tokens that are used for comments and brackets.

## Get up and running straight away

* Make sure the language configuration settings in `language-configuration.json` are accurate.
* Press `F5` to open a new window with your extension loaded.
* Create a new file with a file name suffix matching your language.
* Verify that syntax highlighting works and that the language configuration settings are working.

## Make changes

* You can relaunch the extension from the debug toolbar after making changes to the files listed above.
* You can also reload (`Ctrl+R` or `Cmd+R` on Mac) the VS Code window with your extension to load your changes.

## Add more language features

* To add features such as intellisense, hovers and validators check out the VS Code extenders documentation at https://code.visualstudio.com/docs

## Install your extension

* To start using your extension with Visual Studio Code copy it into the `<user home>/.vscode/extensions` folder and restart Code.
* To share your extension with the world, read on https://code.visualstudio.com/docs about publishing an extension.

## publish
```
$ vsce package
# myExtension.vsix generated
$ vsce publish
```

```issue
错误1：Error:Missing publisher name. Learn more:
解决方式：在package.json中将刚刚创建好的发布账号配置进去"publisher":"your name",
错误2：Error:Make sure to edit the README.md file before you publish your extension
解决方式：看下README.md文件中是否有http地址
错误3：A ‘repository’field is missing from the 'package.josn' manifest file .Do you want to continue? [y/n] 
解决方式：y
错误4：ERROR  Access Denied: hzgood needs the following permission(s) on the resource /hzgood to perform this action: View user permissions on a resource
vsce publish -p zzvvdhcwkfjmn2wjp6lmx4lbrmj2msg5bcozvfgom4qlhcsboufq
```