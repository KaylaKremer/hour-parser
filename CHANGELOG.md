# Changelog

## v1.1.0

- **BREAKING**: `toDecimal` and `toHHMM` will now _always_ return a `string` type, regardless of input.
- **BREAKING**: `toDecimal` will now return a blank string when passed an invalid value, just like `toHHMM` does.
- The build system now uses TypeScript 3.9.2 and targets ES2020.

## v1.0.0

Initial release