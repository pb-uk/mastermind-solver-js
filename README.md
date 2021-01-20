# Boilerplate module

> Solver for the puzzle game Mastermind™.

## Getting Started: in a web page

Current major browsers are supported but not Internet Explorer (edit `targets`
in `rollup.config.js` and run `npm run build` to change this).

Load the script from the CDN:

```html
<script src="https://cdn.jsdelivr.net/npm/pbuk-uk/mastermind-solver@0"></script>
```

The module is exported as `MastermindSolver`:

```html
<script>
  document.write(MastermindSolver.version);
</script>
```

## Getting Started: in Node.js

Node >= 10 is currently supported in the distributed modules.

Install from `npm`:

```console
$ npm i boilerplate-module
```

Require CommonJS module:

```js
// Default should work...
const MastermindSolver = require('mastermind-solver');
// ...or specify CommonJS module.
const MastermindSolver = require('mastermind-solver/dist/cjs');
```

or import as an ES6 module:

```js
// Default should work...
import MastermindSolver from 'mastermind-solver';
// ...or specify ES6 module.
import MastermindSolver from 'mastermind-solver/dist/esm';
```

### Using

## Documentation

## Contributing

## License

Distributed under the MIT License. See [LICENSE] for more information.

## Contact

https://github.com/pbuk-uk/mastermind-solver-js/issues

## Acknowledgements

Mastermind is a registered trade mark of Hasbro, Inc.
