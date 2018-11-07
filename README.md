# Flow Global Types

Now flow have strange behaviour. When we import type in [libdefs](https://flow.org/en/docs/libdefs/), these types become global for
all lint modules

## How reproduce

```
$ git clone git@github.com:underoot/global-flow-types.git
$ cd git@github.com:underoot/global-flow-types.git
$ npm i
$ npm run lint
$ npm run lint:fixed # Add type imports from libdefs
```