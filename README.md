# Node Version

```txt
node - v14.8.0
npm - 6.14.7
```

- If node version doesn't exsit automatically Installed specific node version via nvm

```
nvm use
```

- Install node_modules dependencies

```shell
npm install
```

## Get Started

- To development mode

```shell
npm run dev
```

- To production mode

```shell
npm run prod
```

- To build a server code es6 to es5

```shell
npm run build
```

- Watching files changes

```shell
npm run watch
```

### Other scripts

- transpile - convert es6 and beyond code to es5 to a folder named `compiled-server`
- clean - delete transpiled folder
- build - clean and transpile
