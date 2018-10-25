# vue-cli-content-hash-reproduce

## Way to Reproduce
Do the following 4 steps in two machines, compare the content-hash in `dist/js/app.<content-hash>.js`, you will find them not matched.

```bash
git clone https://github.com/zhangbobell/vue-cli-content-hash-reproduce.git

cd vue-cli-content-hash-reproduce

yarn

NODE_ENV=production yarn build
```


## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn run serve
```

### Compiles and minifies for production
```
yarn run build
```

### Run your tests
```
yarn run test
```

### Lints and fixes files
```
yarn run lint
```
