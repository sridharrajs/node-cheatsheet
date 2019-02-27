# npm

`npm` is the default package manager for Node.js. It is included as a part of Node.js

## Creating a repo

`npm init` => To enter the details through interaction

`npm init -y` => To create a repo quickly with default configurations


## Installing and Uninstalling


`npm install` or `npm i` => For installing all the dependencies in `package.json`

`npm i <module>` => For installing a specific module

`npm uninstall <module>` or `npm un <module>` =>  For uninstalling a specific module

## Updating

`npm install npm@latest -g` => Update the `npm` to the latest version
     
## Listing

`npm run` => To list all the run commands available in `package.json`

`npm ls -g --depth=0 --link=true` => To list all the globally installed links


## Options

`npm repo`    => To open the repo url on the default browser, provided `package.json` has a valid `repository` details

`npm bugs`    => To open `issues` page of the repo on Github

## Debugging

`npm cache clear —force` => To clear cache 



