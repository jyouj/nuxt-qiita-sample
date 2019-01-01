# nuxt-qiita-sample

> Nuxt Qiita viewer

花谷拓磨著「Nuxt.jsビギナーズガイド」Chapter2のサンプルアプリを少し改変してみたもの！
変更点
 - `layouts/default.vue`の追加
 - `vue.js/nuxt.js`の二つのタグ検索に対応

## Build Setup

``` bash
# install dependencies
$ npm install # Or yarn install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, checkout the [Nuxt.js docs](https://github.com/nuxt/nuxt.js).

## Qiita Token
``` bash
$ brew install direnv

$ echo 'eval "$(direnv hook bash)"' >> ~/.bashrc

$ touch .envrc

# write QIITA_TOKEN in .envrc
```
