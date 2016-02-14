# AngularJS Webpack Starter

[![Dependency Status](https://david-dm.org/dsebastien/angularjs-webpack-starter.svg?theme=shields.io&style=flat)](https://david-dm.org/dsebastien/modernWebDevBuild)
[![devDependency Status](https://david-dm.org/dsebastien/angularjs-webpack-starter/dev-status.svg?theme=shields.io&style=flat)](https://david-dm.org/dsebastien/modernWebDevBuild#info=devDependencies)
[![License](https://img.shields.io/cocoapods/l/AFNetworking.svg)](LICENSE.MD)

## About
A Webpack Starter kit featuring:
* AngularJS (setup, angular-material, router, ...)
* [TypeScript](http://www.typescriptlang.org/)
* [Redux](https://github.com/rackt/redux)
* [Immutable.js](https://facebook.github.io/immutable-js/)
* [JSData](http://www.js-data.io/)
* [RxJS](https://github.com/Reactive-Extensions/RxJS)
* [Lodash](https://lodash.com/)
* [SASS](http://sass-lang.com/)
* [PostCSS](https://github.com/postcss/postcss)
* [Autoprefixer](https://github.com/postcss/autoprefixer)
* [Karma](http://karma-runner.github.io/)
* [Protractor](https://angular.github.io/protractor/#/)
* [Jasmine](http://jasmine.github.io/)
* [Istanbul](https://gotwarlost.github.io/istanbul/)
* [TSLint](https://www.npmjs.com/package/tslint)
* [Typings](https://github.com/typings/typings)
* [TSDoc](https://www.npmjs.com/package/tsdoc)
* [moment](http://momentjs.com/)

... and a complete build based on Webpack/npm scripts with:
* hot module replacement (HMR): https://webpack.github.io/docs/hot-module-replacement.html
* unit tests (Karma & Jasmine)
* end to end tests (Protractor)
* test coverage reports (Istanbul)
  * html, lcov, junit
* TS to ES5 transpilation (TypeScript)
* SASS to CSS transpilation
* TS quality/style checks (TSLint)
* TS code documentation generation (TSDoc)
* development and production configurations
*
* ...

Check out the [change log](CHANGELOG.md)

## Angular 2
As you might know, Angular 2 is right around the corner. Be aware that this starter kit will soon be deprecated.

Note that this starter kit is derived from the Angular 2 Starter Kit: https://github.com/AngularClass/angular2-webpack-starter

## Status & roadmap
Check out the issues/labels & milestones to get an idea of what's next. For existing features, refer to the previous section.

## Installation
...

## Upgrade
Check out the [upgrade](UPGRADE.md) page

## Frequently Asked Questions (FAQ)
...

## Links
* https://github.com/karma-runner/karma-junit-reporter
* https://www.npmjs.com/package/karma-istanbul-reporter
* https://www.npmjs.com/package/karma-mocha-reporter

## Contributing
* Fork the project
* Create a feature branch in your fork
* Rebase  if needed to keep the project history clean
* Commit your changes & push to GitHub
* Try and flood me with pull requests :)

## Releasing a version

* commit all changes to include in the release
* edit the version in package.json
* respect semver
* update CHANGELOG.md
* update UPGRADE.md
* commit
* git tag
* git push --tags
* draft the release on GitHub (add description, etc)
* npm publish

## TODO
See the [project issues](https://github.com/dsebastien/angularjs-webpack-starter/issues/)

## License
This project and all associated source code is licensed under the terms of the [MIT License](https://en.wikipedia.org/wiki/MIT_License).
