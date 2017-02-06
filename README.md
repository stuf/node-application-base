
# node-application-base
Provides a basic application base for Node that includes a default configuration for linting, testing and getting the ball rolling quickly.

Included:

 * Some libraries that seem to always appear in my projects; [`ramda`][ramda], [`partial.lenses`][partial.lenses], [`kefir`][kefir], [`kefir.atom`][kefir.atom]
 * BDD-based testing with [`mocha`][mocha] and [`chai`][chai]
 * Code coverage reporting with [`nyc`][nyc] and [`codecov`][codecov]
 * Linting with [`eslint`][eslint]
 * Code compilation with [`babel`][babel]
 * Debugging support for [`VS Code`][vscode]

[ramda]: https://github.com/ramda/ramda
[partial.lenses]: https://github.com/calmm-js/partial.lenses
[kefir]: https://github.com/rpominov/kefir
[kefir.atom]: https://github.com/calmm-js/kefir.atom
[mocha]: https://github.com/mochajs/mocha
[chai]: https://github.com/chaijs/chai
[nyc]: https://github.com/istanbuljs/nyc
[codecov]: https://github.com/codecov/codecov-node
[eslint]: https://github.com/eslint/eslint
[babel]: https://github.com/babel/babel
[vscode]: https://code.visualstudio.com/

## Requirements

 * [`yarn`][yarn] instead of `npm` (easy install on OSX: `brew update && brew install yarn`)

[yarn]: https://yarnpkg.com/

## Getting started

```
git clone https://github.com/stuf/node-application-base.git
cd node-application-base
yarn
yarn start
```

### Run tests

```
yarn run test
```

### Build

```
yarn run build
```

### Push

Basically runs `lint` and `test` before invoking `git push`. Convenience script to avoid accidentally pushing broken code.

```
yarn run push
```

## Acknowledgements

## License

Released under the [MIT License](LICENSE)