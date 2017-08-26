# ng-seed/spa
> Please support this project by simply putting a Github star. Share this library with friends on Twitter and everywhere else you can.

**`ng-seed/spa`** is a seed project for Angular apps following the common patterns and [best practices](https://angular.io/styleguide) in file and application organization, providing the following features:

- Ready-to-go build system using [gulp] and [Webpack] for working with [TypeScript].
- Adjustable build configuration via `json` file (`./config/build-config.json`).
- Production and development modes.
- [Webpack DLL]s to speed up development builds.
- [AoT compilation] for rapid page loads on production builds (*using **`ngc`***).
- Tree-shaking the production builds with `harmony` branch of [UglifyJs2].
- Hot Module Replacement with [Webpack] and [webpack-hot-middleware].
- Both inline and external SCSS compilation.
- Lazy loading of modules.
- Uses [ngx-config] for configuration management.
- Uses [ngx-cache] for caching.
- Uses [ngx-translate] and [ngx-i18n-router] for i18n support.
- Uses [ngx-meta] for SEO.
- ~Sample unit tests with Jasmine and Karma including code coverage via istanbul.~
- ~End-to-end tests with Protractor.~
- [angular-tslint-rules] as configuration preset for [TSLint] and [codelyzer].
- Managing the type definitions using @types.

> Built with `Angular v2.4.0`, bundled with `gulp v4.0` and `webpack v3.4.1`.

You can find the live app [here](https://ng-seed-spa.azurewebsites.net).

## Prerequisites
Packages in this seed project depend on `@angular v2.4.0`. Older versions contain outdated dependencies, might produce errors.

Also, please ensure that you are using **`Typescript v2.1.6`** or higher.

## Installing
```
# clone the repo
git clone https://github.com/ng-seed/spa.git
cd spa

# checkout to `angular-2.4.x` branch
git checkout angular-2.4.x

# use npm (or yarn) to install the dependencies
npm install

# run tslint
npm run lint

# dev build
npm run build:dev
# prod build
npm run build:prod

# start the server
npm run serve
# start the server (with HMR support)
npm run serve:hmr
```

Navigate to `http://localhost:1337` in your browser.

## Contributing
If you want to file a bug, contribute some code, or improve documentation, please read up on the following contribution guidelines:
- [Issue guidelines](CONTRIBUTING.md#submit)
- [Contributing guidelines](CONTRIBUTING.md)
- [Coding rules](CONTRIBUTING.md#rules)
- [ChangeLog](CHANGELOG.md)

## License
The MIT License (MIT)

Copyright (c) 2017 [Burak Tasci]

[gulp]: http://gulpjs.com
[Webpack]: http://webpack.github.io
[TypeScript]: https://github.com/Microsoft/TypeScript
[Webpack DLL]: https://robertknight.github.io/posts/webpack-dll-plugins
[AoT compilation]: https://angular.io/docs/ts/latest/cookbook/aot-compiler.html
[UglifyJs2]: https://github.com/mishoo/UglifyJS2/tree/harmony
[webpack-hot-middleware]: https://github.com/glenjamin/webpack-hot-middleware
[ngx-config]: https://github.com/fulls1z3/ngx-config
[ngx-cache]: https://github.com/fulls1z3/ngx-cache
[ngx-translate]: https://github.com/ngx-translate/core
[ngx-i18n-router]: https://github.com/fulls1z3/ngx-i18n-router
[ngx-meta]: https://github.com/fulls1z3/ngx-meta
[Jasmine]: https://jasmine.github.io
[Karma]: https://karma-runner.github.io
[Istanbul]: https://github.com/webpack-contrib/istanbul-instrumenter-loader
[Protractor]: http://www.protractortest.org
[angular-tslint-rules]: https://github.com/fulls1z3/angular-tslint-rules
[TSLint]: https://github.com/palantir/tslint
[codelyzer]: https://github.com/mgechev/codelyzer
[Burak Tasci]: http://www.buraktasci.com
