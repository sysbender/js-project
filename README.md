# js-project

https://www.youtube.com/playlist?list=PLcCp4mjO-z99IPNCrhEyrZimdUG5QXjPd

- version control
- CI CD

- quality
- tooling
- module support
- document
- demo

## CI CD

- install,
  - clean install - npm ci
  - security audit - npm audit -
- lint,
  - linter - eslint , stylelint
  - formatter - prettier
- test,
  - test suite - jest, mocha, ava
  - code coverage - myc, codecov, coveralls
- build,
  - transpile - babel, typescript, flow
  - pre-process - sass, less, postcss (compile, auto-prefix)
  - uglify - uglify-js, terser, (minify, mingle, optimize)
  - bundle - webpack, rollup, parcel (concat, tree-shake)
  - compress - gzip
  - other
    - copy, delete, move files
    - check bundle size
    - strip unused code ( ts, flow, proptyes in react)
- push,
  - release - github, bitbucket, gitlab
  - publish - npm , other registry
- deploy
  - host - heroku, surge, github-pages

### task execution

- CLI - npm
- task runner - old
  - grunt, gulp, brunch
-

## eslint, prettier, editorConfig

```shell
npm i -D eslint
npx eslint --init
npx eslint src/*.js
npx eslint src/*.js --fix

npm i -D prettier-eslint
npm i -D prettier-eslint-cli

npx prettier-eslint 'src/**/*.js' --write

```
