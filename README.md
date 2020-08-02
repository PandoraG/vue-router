# vue-router [![Build Status](https://img.shields.io/circleci/project/vuejs/vue-router/master.svg)](https://circleci.com/gh/vuejs/vue-router) [![npm package](https://img.shields.io/npm/v/vue-router.svg)](https://www.npmjs.com/package/vue-router) [![bitHound Overall Score](https://www.bithound.io/github/vuejs/vue-router/badges/score.svg)](https://www.bithound.io/github/vuejs/vue-router) [![Issue Stats](http://issuestats.com/github/vuejs/vue-router/badge/issue?style=flat)](http://issuestats.com/github/vuejs/vue-router)

**Compatibility Note:** `vue-router` requires Vue.js 0.12.10+ and currently does not support Vue.js 2.0.

### 介绍

`vue-router` is the official router for [Vue.js](http://vuejs.org). It deeply integrates with Vue.js core to make building Single Page Applications with Vue.js a breeze. Features include:

- Nested route/view mapping
- Modular, component-based router configuration
- Route params, query, wildcards
- View transition effects powered by Vue.js' transition system
- Fine-grained navigation control
- Links with automatic active CSS classes
- HTML5 history mode or hash mode, with auto-fallback in IE9
- Restore scroll position when going back in history mode

Get started with the [documentation](http://vuejs.github.io/vue-router).

### dev setup

```bash
# install deps
npm install

# build dist files
npm run build

# serve example app at localhost:8080
npm run serve-example

# and unit tests at localhost:8081
npm run dev

# lint & run all tests
npm test

# run unit tests only
npm run unit

# run e2e tests only
npm run e2e-local
```

### 文件目录

```bash
├──  build/                   # 构建相关文件
│  ├── build.js
│  ├── ci.sh
│  ├── e2e.sh
│  ├── harma.config.js
│  ├── nightwatch.local.json
│  ├── nightwatch.sauce.json
│  ├── release.sh
│  ├── update-docs.sh
│  └── webpack.dev.config.js

├── dist/                     # 打包后文件
│  ├── vue-router.js
│  └── vue.router.min.js

├── docs/                     # 项目文档
│  ├── assets/
│  ├── en/
│  ├── ja/
│  ├── zh-cn/
│  ├── book.json
│  └── LANGS.md

├── example/                 # 实例
│  ├── advanced/
│  └── basic/


├── lib/                   # 第三方库or作者封装代码
│  ├── dsl.js
│  └── route-recognizer.js

├── src/                 # 主程序目录
│  ├── directives/
│     ├── link.js
│     └── view.js
│  ├── history/
│     ├── abstract.js
│     ├── hash.js
│     └── html5.js
│  ├── index.js
│  ├── override.js
│  ├── pipeline.js
│  ├── route.js
│  ├── transition.js
│  └── util.js

├── test/                  # 单元测试代码
│  ├── e2e/
│    └── test.js
│  ├── unit/
│    ├── lib/
│    ├── specs/
│    ├── .eslintrc
│    ├── index.html
│    └── webpack.config.js

├── .bithoundrc        # 忽略文件，功能应该类似.gitignore， 其他没有找到更好的解释
├── .eslintrc          # eslint配置文件
├── .gitignore         # git忽略文件配置
├── bower.json         # 客户端库管理工具bower 声明文件
├── circle.yml         # CircleCI 配置文件
├── issue_template.md  # issue说明 & 模版
├── LICENSE            # 版权声明文件
├── package.json       # 项目信息
└── README.md          # 项目说明
```
