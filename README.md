# Wasm webpack config

## Installation process

Install dependencies :
```shell
npm i
```

Load your WASM module in `src/index.js`

## Run

Launch webpack dev server on port `8080`
```shell
npm run serve
```

## Build

Build project into `dist` directory
```shell
npm run build
```

## Serve built project

- APACHE : edit `/etc/mime.types` to add `application/wasm    wasm;` row
- NGINX : same process in `/etc/nginx/mime.types`

> FIREFOX THROWS A MIME TYPE ERROR EVEN AFTER CONFIGURATION, CHROME DOES NOT

