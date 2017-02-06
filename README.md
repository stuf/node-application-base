
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

```
MIT License

Copyright (c) 2017 Stefan Rimaila

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
