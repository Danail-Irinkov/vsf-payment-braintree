# Vue Storefront Braintree Payment Extension

Braintree Payment module for [vue-storefront](https://github.com/DivanteLtd/vue-storefront), by [Daniel Coull - Sutton Silver].

![Demo](docs/demo.png)

## Installation:

By hand (preferer):
```shell
$ git clone git@github.com:danrcoull/vsf-payment-braintree.git ./vue-storefront/src/modules/payment-braintree
```

Registration the Braintree module. Go to `./src/modules/index.ts`
```js
...
import { GoogleAnalytics } from './google-analytics';
import { Braintree } from './payment-braintree';

export const registerModules: VueStorefrontModule[] = [
  ...
  GoogleAnalytics,
  Braintree
]
```

## Braintree payment API extension

Install additional extension for `vue-storefront-api`:
```shell
$ cp -f ./API/braintree ../vue-storefront-api/src/api/extensions/
```
