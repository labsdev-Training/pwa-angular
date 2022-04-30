# PWA - Angular

> PWA Angular for open source projects.

[![NPM Version][npm-badge]][npm-url]
![Node Version][node-badge]
![Angular Version][angular-badge]


This project provides the following features:


- **README.md** and **CHANGELOG.md** with information about the project, installation, usage, development, author and license.
- **Badges** for Travis, Appveyor, CircleCI, Coveralls, npm and License.

## Project files

```text
.
|--- src
|    |--- index.js
|--- test
|    |--- test.js
|--- .editorconfig
|--- .eslintignore
|--- .eslintrc.json
|--- .gitattributes
|--- .gitignore
|--- .npmrc
|--- .prettierrc
|--- .travis.yml
|--- appveyor.yml
|--- CHANGELOG.md
|--- circle.yml
|--- LICENSE
|--- main.js
|--- package.json
|--- README.md
```

## Installation

- Install Node 12.20

```bash
$ https://nodejs.org/download/release/latest-erbium/
```


- Install Angular 9

```bash
$ npm install -g @angular/cli@latest
```


## Usage

- Creating a project

```bash
# Create a directory for your project
$ ng new pwa-angular

# Change into directory
$ cd pwa-angular

# add angular 
$ ng add @angular/pwa

# Generate a project
$ ng serve
```

- Running project

| Action                                   | Usage               |
| ---------------------------------------- | ------------------- |
| Starting development mode                | `ng serve`         |

| Sending coverage results to Coveralls.io | `npm run coveralls` |

## Development

### Prerequisites

- Install [Node.js](https://nodejs.org/download/release/latest-erbium/)
- Install [npm](https://www.npmjs.com/)
- Install Angular 

```bash
$ npm install -g @angular/cli@latest
```

### Clone the repo

```bash
$ git clone https://github.com/portifolio-dev/pwa-angular.git
```

### Run project

```bash
# Change into directory
$ cd pwa-angular


```

## Author

[Rose Dias]()


## License

[MIT](https://github.com/robertoachar/generator-oss-project/blob/master/LICENSE)

[node-badge]: https://img.shields.io/badge/node-12.20-brightgreen

[angular-badge]: https://img.shields.io/badge/angular-13.3.4-brightgreen


[npm-badge]: https://img.shields.io/badge/npm-6.14.16-brightgreen


[npm-url]: https://www.npmjs.com/package/generator-oss-project
[npm-downloads-badge]: https://img.shields.io/npm/dt/generator-oss-project.svg
[npm-downloads-url]: https://www.npmjs.com/package/generator-oss-project
[travis-badge]: https://travis-ci.org/robertoachar/generator-oss-project.svg?branch=master
[travis-url]: https://travis-ci.org/robertoachar/generator-oss-project
[circleci-badge]: https://circleci.com/gh/robertoachar/generator-oss-project/tree/master.svg?style=shield
[circleci-url]: https://circleci.com/gh/robertoachar/generator-oss-project
[appveyor-badge]: https://ci.appveyor.com/api/projects/status/github/robertoachar/generator-oss-project?branch=master&svg=true
[appveyor-url]: https://ci.appveyor.com/project/robertoachar/generator-oss-project
[coveralls-badge]: https://coveralls.io/repos/github/robertoachar/generator-oss-project/badge.svg?branch=master
[coveralls-url]: https://coveralls.io/github/robertoachar/generator-oss-project?branch=master
[license-badge]: https://img.shields.io/github/license/robertoachar/generator-oss-project.svg
[license-url]: https://opensource.org/licenses/MIT

https://www.webfx.com/tools/emoji-cheat-sheet/

https://shields.io/
