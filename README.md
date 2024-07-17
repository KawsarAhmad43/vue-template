# vue-project

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```


# New Project create and initialization
- 1. npm init vue@latest
   - a. chose Project name
   - b. add typescript: no
   - c. jsx support: no
   - d. Vue router: yes
   - e. pinia: no
   - f. vitest: no
   - g. end to end test: no
   - h. eslint: no
   - i. add vue detools 7: no
- 2.cd project and observe structure(public, src, jsconfig.json, package.json, vite.config.js)
- 3. npm install
- 4. npm run dev
   your app will be run on localhost:5174







# How does it work:
  main entrypoint root->index.html where <div id="app"></div>   this app is the instance of my vue app
  it will be initialized by src/main.js here app will be mounted..from here App.vue will be loaded
  you can consider App.vue as master-layout like laravel where routerlink is injected and others component will be injected

  
