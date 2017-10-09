# Understanding 'modules'

## What's a module?
Modules are just small programs you can integrate with the bigger program you are writing.

Modules would be listed in your `package.json`.

There are 3 types of modules.

### a. Node core module
'Core' Node modules come with Node automatically.
Examples of common core modules are `http`, `fs` and `path`.

There is a list of all the core modules and their methods on the Node.js website.

### b. Node 3rd-party module
There are thousands of open-source, 3rd-party Node modules that other clever people have written. You can download useful 3rd-party modules (also known as "packages") from [npm](http://npmjs.com) (the node package manager).

The npm website says:

> npm makes it easy for JavaScript developers to share and reuse code, and it makes it easy to update the code that you're sharing.

The npm command-line tool comes automatically with Node. You can install 3rd-party packages on the command line, so no need to download from the npm website or anything.

### c. Modules you've written

Also called a module, but slightly different from the first two.

These are modules you write yourself in your code. We will talk about this later on in step 7.
