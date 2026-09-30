WIP module for the Gryd development tools.


# Package deploy instructions

- You have to create an account to npmjs.org

https://docs.npmjs.com/creating-and-publishing-an-org-scoped-package


- Login into your account running on terminal 

> npm login

- Check the version you are publishing

> npm version

- Update the version if needed 

> npm version 2.0.0

- Publish the package

> npm publish --access public

# Settings

- `port`: the port to listen on.
- `beforeListen`: optional; called after the app directory is loaded. The port is not bound
  until the promise it returns resolves, and a rejection fails the boot.
- `callbackFn`: optional; called once the port is bound.
