# Node Cheatsheet

A glossary of terms for Node.js.


| Term           | Meaning |
|----------------|----------------------------------|
| `Node.js`      | JavaScript for servers. |
| `web server`   | Program that processes requests for the internet via HTTP. |
| `HTTP`         | Short for HyperText Transfer Protocol. The set of standards for transferring files over the internet. |
| `npm`          | Package manager for Node.js. Allows you to install and publish open source Node projects. |
| `npm package`  | Open source Node project, published on npm. |
| `npm init`     | Command run in the terminal to initialise your Node project and create a package.json file. |
| `npm install <package-name>`  | Command run in the terminal to install an npm package. |
| `npm install <package-name>` `--save`  | Command run in the terminal to install an npm package, `--save`  or `-S` instructs NPM to include the package inside of the `dependencies` section of your package.json automatically. [Refer Docs](https://docs.npmjs.com/cli/install). |
| `npm install <package-name>` `--save-dev` | Command run in the terminal to install an npm package, `--save-dev` or `-D` instructs NPM to include the package inside of the `devDependencies` section of your package.json automatically. |
| `npm install <package-name>` `--save-optional` | Command run in the terminal to install an npm package, `--save-optional` or `-O` instructs NPM to include the package inside of the `optionalDependencies` section of your package.json automatically. |
| `package.json` | File holding various metadata about a Node project, such as project name, description or license information, installed packages (aka dependencies). Usually located in the root directory. Package.json cheatsheet [here](http://browsenpm.org/package-json). |
| `dependencies` | Packages installed from npm that are necessary to run the project successfully. Listed in the package.json. |
