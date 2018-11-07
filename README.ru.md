# Flow Global Types

Сейчас Flow обладает странным поведением: импорт типов в [libdefs](https://flow.org/en/docs/libdefs/) становится
глобальными для всех модулей, подвергаемых линтингу.

## Как вопроизвести

```
$ git clone git@github.com:underoot/global-flow-types.git
$ cd git@github.com:underoot/global-flow-types.git
$ npm i
$ npm run lint
$ npm run lint:fixed # Добавляем импорт типа из libdefs
```