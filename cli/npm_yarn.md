# npm-cli

## npm

```bash
npm info react version   # get version number 
npm list react # get react all versions
npm list --depth=0   # get first level dependency and version info
npm list -g --depth 0 # get global cli package
npm config ls # show config in current registry

npm cache verify # before npm v6
npm cache clean # clean all cache folder, after npm v5

npm version <major|minor|patch>
```

[Scope Definition 1](https://docs.npmjs.com/misc/scope)  
[Scope Definition 2](https://docs.npmjs.com/getting-started/scoped-packages)  
@somescope/somepackagename

### NPM install error solution

```sh
npm cache verify
npm cache clean --force
npm i -g npm

# delete package-lock.jso
```

## yarn

```sh
yarn add <name>
yarn remove <name>
```
