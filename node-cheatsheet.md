# Node Cheatsheet

A glossary of terms for Node.js.


### General

| Term           | Meaning |
|----------------|----------------------------------|
| `Node.js`      | JavaScript for servers. |
| `server`   | Program that processes requests for the internet via HTTP. |
| `client`       | Application that accesses the information sent from the web server. Often the web browser. |
| `HTTP`         | Short for HyperText Transfer Protocol. The set of standards for transferring files over the internet. |
| `request`      | Request for a file, sent by the client to the server via HTTP. |
| `response`     | File sent by the server in response to an HTTP request. |
| `port`           | Number used to identify where to access the server. If server is running locally, you are able to access the application in your browser via `http://localhost:<port-number>`. |

### npm

| Term           | Meaning |
|----------------|----------------------------------|
| `npm`          | Package manager for Node.js. Allows you to install and publish open source Node projects. |
| `npm package`  | Open source Node project, published on npm. |
| `npm init`     | Command run in the terminal to initialise your Node project and create a package.json file. |
| `npm install <package-name>`  | Command run in the terminal to install an npm package. |
| `package.json` | File holding various metadata about a Node project, such as project name, description or license information, installed packages (aka dependencies). Created by `git init`. Usually located in the root directory. Package.json cheatsheet [here](http://browsenpm.org/package-json). |
| `dependencies` | Packages installed from npm that are necessary to run the project successfully. Listed in the package.json. |

### Node.js

| Term              | Meaning |
|-------------------|----------------------------------|
| `require("http")` | HTTP is a core module in Node.js. Requiring "http" allows you to access its methods. Documentation [here](https://nodejs.org/api/http.html). |
| `require("fs")`   | File system is a core module in Node.js. Requiring "fs" allows you to access its methods. Documentation [here](https://nodejs.org/api/fs.html). |
