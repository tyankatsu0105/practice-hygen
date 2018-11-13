# 使い方

```bash
$ yarn hygen generate new --name Card --dir componets

Loaded templates: _templates
       added: _templates/Card/new/store.ejs.t
       added: _templates/Card/new/tests-store.ejs.t
       added: _templates/Card/new/tests-vue.ejs.t
       added: _templates/Card/new/vue.ejs.t

$ yarn hygen Card new

Loaded templates: _templates
       added: src/components/Card.vue
       added: src/store/modules/card.js
       added: tests/store/card.spec.js
       added: tests/components/Card.spec.js
```

```bash
$ yarn hygen generate new --name Card --dir views

Loaded templates: _templates
       added: _templates/Card/new/store.ejs.t
       added: _templates/Card/new/tests-store.ejs.t
       added: _templates/Card/new/tests-vue.ejs.t
       added: _templates/Card/new/vue.ejs.t

$ yarn hygen Card new

Loaded templates: _templates
       added: src/views/Card.vue
       added: src/store/modules/card.js
       added: tests/store/card.spec.js
       added: tests/views/Card.spec.js
```

- --name | ファイル名
- --dir | ディレクトリ名