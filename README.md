# nyarn

Good bye package-lock.json on project using yarn.

## Installation

```bash
$ npm i -g @matzkoh/nyarn
```

```bash
alias npm='nyarn npm'
alias yarn='nyarn yarn'
# or
# alias yarnpkg='nyarn yarnpkg'
```

## For example

```bash
$ npm init -y
$ npm i

$ ls -1
package-lock.json
package.json

$ yarn
The project has lockfile created by npm.
You should use npm instead of yarn.
```

```bash
$ yarn init -y
$ yarn

$ ls -1
node_modules
package.json
yarn.lock

$ npm i
The project has lockfile created by yarn.
You should use yarn instead of npm.
```
