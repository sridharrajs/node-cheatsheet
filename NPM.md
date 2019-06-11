# npm

`npm` is the default package manager for Node.js. It is included as a part of Node.js

You need to use `. npmrc` to specify registry other than default npm registry.

`package-lock.json` will be generated when you install dependencies for a project. This package-lock.json [should be committed into source control](https://stackoverflow.com/questions/44206782/do-i-commit-the-package-lock-json-file-created-by-npm-5)

------------

You can find both tilde(~) and caret(^) in package.json. 

> The tilde ~ matches the most recent patch version (the third number) for the specified minor version (the second number). ~1.2.3 will match all 1.2.x versions but will hold off on 1.3.0.

> The caret ^ is more relaxed. It matches the most recent minor version (the second number) for the specified major version (the first number). ^1.2.3 will match any 1.x.x release including 1.3.0, but will hold off on 2.0.0.

**source** [What's the difference between tilde(~) and caret(^) in package.json?](https://stackoverflow.com/a/22345808/978501)


------------

## Creating a repo

|Command|Description|
|-------|-----------|
|`npm init`|To enter the details through interaction|
|`npm init -y`|To create a repo quickly with default configurations|


## Installing and Uninstalling

|Command|Description|
|-------|-----------|
|`npm install` or `npm i` | For installing all the dependencies in `package.json`|
|`npm i <module>` | For installing a specific module|
|`npm uninstall <module>` or `npm un <module>` |  For uninstalling a specific module|

## Updating

|Command|Description|
|-------|-----------|
|`npm install npm@latest -g`|Update the `npm` to the latest version|
     
## Listing

|Command|Description|
|-------|-----------|
|`npm run`|To list all the run commands available in `package.json`|
|`npm ls -g --depth=0 --link=true`|To list all the globally installed links|


## Options

|Command|Description|
|-------|-----------|
|`npm repo`|To open the repo url on the default browser, provided `package.json` has a valid `repository` details|
|`npm bugs`|To open `issues` page of the repo on Github|

## Debugging

|Command|Description|
|-------|-----------|
|`npm cache clear —force`|To clear cache|



