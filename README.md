# Pure ESM TS Template

Template with boilerplate for a pure ESM package in TypeScript; inspired by this [gist](https://gist.github.com/sindresorhus/a39789f98801d908bbc7ff3ecc99d99c).

## Overview

I made this template because I wanted a clean starting point for my TypeScript packages without bloated & unnessasary configurations.

#### CommonJS Support

The aim of this template is be to pure ESM. However, if you do need to support CommonJS you can use the example package file: `package.cjs.json`

## Resources

### Example 'Install' disclaimer

| **Warning:** This package is native [ESM](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules) and doesn't provide a CommonJS export. If your project uses CommonJS, you'll have to [convert to ESM](https://gist.github.com/sindresorhus/a39789f98801d908bbc7ff3ecc99d99c) or use the [dynamic `import()`](https://v8.dev/features/dynamic-import) function. |
|---|
