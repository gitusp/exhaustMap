# most-package-seed

A starter kit for a [most/core](https://github.com/mostjs/core) package.

## What it does out of the box

- Compiles TypeScript, generates typings
- Builds CommonJS and ES2015 modules, and also UMD module (you know, for CDNs)
- Runs tests with Mocha (and `power-assert`)

## How to use

1. Clone (or fork) the repo.
2. If you clone, don’t forget to change the git remote.
3. Edit `package.json`
   1. Search and replace `most-package-seed` with your package name of choice
   2. Don’t forget to remove `"private": true`.
4. Edit `README.md` for good measure.
5. You’re ready to code.

## What it lacks

Flow types generation is missing, even though they probably can be converted from the TS typings.
