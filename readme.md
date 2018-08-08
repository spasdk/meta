SPA SDK management
==================

## Usage ##

Install global dependencies:

```bash
sudo npm install -g meta
```

Get meta repo:

```bash
git clone https://github.com/spasdk/meta.git spasdk
# or for Github users with granted access
git clone git@github.com:spasdk/meta.git spasdk
cd spasdk
```

All preparations:

```bash
npm install
meta git update
meta npm install
sudo meta npm link --all
```


## Packages ##

 Repo                                                                              | Build status                                                                                                                                              | NPM version                                                                                                                                               | Dependencies status                                                                                                                                            | devDependencies status
-----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------
[spa-app](https://github.com/spasdk/app.git)                                       | [![build status](https://img.shields.io/travis/spasdk/app.svg?style=flat-square)](https://travis-ci.org/spasdk/app)                                       | [![npm version](https://img.shields.io/npm/v/spa-app.svg?style=flat-square)](https://www.npmjs.com/package/spa-app)                                       | [![dependencies status](https://img.shields.io/david/spasdk/app.svg?style=flat-square)](https://david-dm.org/spasdk/app)                                       | [![dependencies status](https://img.shields.io/david/dev/spasdk/app.svg?style=flat-square)](https://david-dm.org/spasdk/app)
[spa-boilerplate](https://github.com/spasdk/boilerplate.git)                       | [![build status](https://img.shields.io/travis/spasdk/boilerplate.svg?style=flat-square)](https://travis-ci.org/spasdk/boilerplate)                       | (n/a)                                                                                                                                                     | [![dependencies status](https://img.shields.io/david/spasdk/boilerplate.svg?style=flat-square)](https://david-dm.org/spasdk/boilerplate)                       | [![dependencies status](https://img.shields.io/david/dev/spasdk/boilerplate.svg?style=flat-square)](https://david-dm.org/spasdk/boilerplate)
[spa-component](https://github.com/spasdk/component.git)                           | [![build status](https://img.shields.io/travis/spasdk/component.svg?style=flat-square)](https://travis-ci.org/spasdk/component)                           | [![npm version](https://img.shields.io/npm/v/spa-component.svg?style=flat-square)](https://www.npmjs.com/package/spa-component)                           | [![dependencies status](https://img.shields.io/david/spasdk/component.svg?style=flat-square)](https://david-dm.org/spasdk/component)                           | [![dependencies status](https://img.shields.io/david/dev/spasdk/component.svg?style=flat-square)](https://david-dm.org/spasdk/component)
[spa-component-button](https://github.com/spasdk/component-button.git)             | [![build status](https://img.shields.io/travis/spasdk/component-button.svg?style=flat-square)](https://travis-ci.org/spasdk/component-button)             | [![npm version](https://img.shields.io/npm/v/spa-component-button.svg?style=flat-square)](https://www.npmjs.com/package/spa-component-button)             | [![dependencies status](https://img.shields.io/david/spasdk/component-button.svg?style=flat-square)](https://david-dm.org/spasdk/component-button)             | [![dependencies status](https://img.shields.io/david/dev/spasdk/component-button.svg?style=flat-square)](https://david-dm.org/spasdk/component-button)
[spa-component-checkbox](https://github.com/spasdk/component-checkbox.git)         | [![build status](https://img.shields.io/travis/spasdk/component-checkbox.svg?style=flat-square)](https://travis-ci.org/spasdk/component-checkbox)         | [![npm version](https://img.shields.io/npm/v/spa-component-checkbox.svg?style=flat-square)](https://www.npmjs.com/package/spa-component-checkbox)         | [![dependencies status](https://img.shields.io/david/spasdk/component-checkbox.svg?style=flat-square)](https://david-dm.org/spasdk/component-checkbox)         | [![dependencies status](https://img.shields.io/david/dev/spasdk/component-checkbox.svg?style=flat-square)](https://david-dm.org/spasdk/component-checkbox)
[spa-component-flicker](https://github.com/spasdk/component-flicker.git)           | [![build status](https://img.shields.io/travis/spasdk/component-flicker.svg?style=flat-square)](https://travis-ci.org/spasdk/component-flicker)           | [![npm version](https://img.shields.io/npm/v/spa-component-flicker.svg?style=flat-square)](https://www.npmjs.com/package/spa-component-flicker)           | [![dependencies status](https://img.shields.io/david/spasdk/component-flicker.svg?style=flat-square)](https://david-dm.org/spasdk/component-flicker)           | [![dependencies status](https://img.shields.io/david/dev/spasdk/component-flicker.svg?style=flat-square)](https://david-dm.org/spasdk/component-flicker)
[spa-component-grid](https://github.com/spasdk/component-grid.git)                 | [![build status](https://img.shields.io/travis/spasdk/component-grid.svg?style=flat-square)](https://travis-ci.org/spasdk/component-grid)                 | [![npm version](https://img.shields.io/npm/v/spa-component-grid.svg?style=flat-square)](https://www.npmjs.com/package/spa-component-grid)                 | [![dependencies status](https://img.shields.io/david/spasdk/component-grid.svg?style=flat-square)](https://david-dm.org/spasdk/component-grid)                 | [![dependencies status](https://img.shields.io/david/dev/spasdk/component-grid.svg?style=flat-square)](https://david-dm.org/spasdk/component-grid)
[spa-component-input](https://github.com/spasdk/component-input.git)               | [![build status](https://img.shields.io/travis/spasdk/component-input.svg?style=flat-square)](https://travis-ci.org/spasdk/component-input)               | [![npm version](https://img.shields.io/npm/v/spa-component-input.svg?style=flat-square)](https://www.npmjs.com/package/spa-component-input)               | [![dependencies status](https://img.shields.io/david/spasdk/component-input.svg?style=flat-square)](https://david-dm.org/spasdk/component-input)               | [![dependencies status](https://img.shields.io/david/dev/spasdk/component-input.svg?style=flat-square)](https://david-dm.org/spasdk/component-input)
[spa-component-list](https://github.com/spasdk/component-list.git)                 | [![build status](https://img.shields.io/travis/spasdk/component-list.svg?style=flat-square)](https://travis-ci.org/spasdk/component-list)                 | [![npm version](https://img.shields.io/npm/v/spa-component-list.svg?style=flat-square)](https://www.npmjs.com/package/spa-component-list)                 | [![dependencies status](https://img.shields.io/david/spasdk/component-list.svg?style=flat-square)](https://david-dm.org/spasdk/component-list)                 | [![dependencies status](https://img.shields.io/david/dev/spasdk/component-list.svg?style=flat-square)](https://david-dm.org/spasdk/component-list)
[spa-component-modal](https://github.com/spasdk/component-modal.git)               | [![build status](https://img.shields.io/travis/spasdk/component-modal.svg?style=flat-square)](https://travis-ci.org/spasdk/component-modal)               | [![npm version](https://img.shields.io/npm/v/spa-component-modal.svg?style=flat-square)](https://www.npmjs.com/package/spa-component-modal)               | [![dependencies status](https://img.shields.io/david/spasdk/component-modal.svg?style=flat-square)](https://david-dm.org/spasdk/component-modal)               | [![dependencies status](https://img.shields.io/david/dev/spasdk/component-modal.svg?style=flat-square)](https://david-dm.org/spasdk/component-modal)
[spa-component-page](https://github.com/spasdk/component-page.git)                 | [![build status](https://img.shields.io/travis/spasdk/component-page.svg?style=flat-square)](https://travis-ci.org/spasdk/component-page)                 | [![npm version](https://img.shields.io/npm/v/spa-component-page.svg?style=flat-square)](https://www.npmjs.com/package/spa-component-page)                 | [![dependencies status](https://img.shields.io/david/spasdk/component-page.svg?style=flat-square)](https://david-dm.org/spasdk/component-page)                 | [![dependencies status](https://img.shields.io/david/dev/spasdk/component-page.svg?style=flat-square)](https://david-dm.org/spasdk/component-page)
[spa-component-panel](https://github.com/spasdk/component-panel.git)               | [![build status](https://img.shields.io/travis/spasdk/component-panel.svg?style=flat-square)](https://travis-ci.org/spasdk/component-panel)               | [![npm version](https://img.shields.io/npm/v/spa-component-panel.svg?style=flat-square)](https://www.npmjs.com/package/spa-component-panel)               | [![dependencies status](https://img.shields.io/david/spasdk/component-panel.svg?style=flat-square)](https://david-dm.org/spasdk/component-panel)               | [![dependencies status](https://img.shields.io/david/dev/spasdk/component-panel.svg?style=flat-square)](https://david-dm.org/spasdk/component-panel)
[spa-component-progress-bar](https://github.com/spasdk/component-progress-bar.git) | [![build status](https://img.shields.io/travis/spasdk/component-progress-bar.svg?style=flat-square)](https://travis-ci.org/spasdk/component-progress-bar) | [![npm version](https://img.shields.io/npm/v/spa-component-progress-bar.svg?style=flat-square)](https://www.npmjs.com/package/spa-component-progress-bar) | [![dependencies status](https://img.shields.io/david/spasdk/component-progress-bar.svg?style=flat-square)](https://david-dm.org/spasdk/component-progress-bar) | [![dependencies status](https://img.shields.io/david/dev/spasdk/component-progress-bar.svg?style=flat-square)](https://david-dm.org/spasdk/component-progress-bar)
[spa-component-scrollbar](https://github.com/spasdk/component-scrollbar.git)       | [![build status](https://img.shields.io/travis/spasdk/component-scrollbar.svg?style=flat-square)](https://travis-ci.org/spasdk/component-scrollbar)       | [![npm version](https://img.shields.io/npm/v/spa-component-scrollbar.svg?style=flat-square)](https://www.npmjs.com/package/spa-component-scrollbar)       | [![dependencies status](https://img.shields.io/david/spasdk/component-scrollbar.svg?style=flat-square)](https://david-dm.org/spasdk/component-scrollbar)       | [![dependencies status](https://img.shields.io/david/dev/spasdk/component-scrollbar.svg?style=flat-square)](https://david-dm.org/spasdk/component-scrollbar)
[spa-component-tab](https://github.com/spasdk/component-tab.git)                   | [![build status](https://img.shields.io/travis/spasdk/component-tab.svg?style=flat-square)](https://travis-ci.org/spasdk/component-tab)                   | [![npm version](https://img.shields.io/npm/v/spa-component-tab.svg?style=flat-square)](https://www.npmjs.com/package/spa-component-tab)                   | [![dependencies status](https://img.shields.io/david/spasdk/component-tab.svg?style=flat-square)](https://david-dm.org/spasdk/component-tab)                   | [![dependencies status](https://img.shields.io/david/dev/spasdk/component-tab.svg?style=flat-square)](https://david-dm.org/spasdk/component-tab)
[spa-component-widget](https://github.com/spasdk/component-widget.git)             | [![build status](https://img.shields.io/travis/spasdk/component-widget.svg?style=flat-square)](https://travis-ci.org/spasdk/component-widget)             | [![npm version](https://img.shields.io/npm/v/spa-component-widget.svg?style=flat-square)](https://www.npmjs.com/package/spa-component-widget)             | [![dependencies status](https://img.shields.io/david/spasdk/component-widget.svg?style=flat-square)](https://david-dm.org/spasdk/component-widget)             | [![dependencies status](https://img.shields.io/david/dev/spasdk/component-widget.svg?style=flat-square)](https://david-dm.org/spasdk/component-widget)
[spa-dom](https://github.com/spasdk/dom.git)                                       | [![build status](https://img.shields.io/travis/spasdk/dom.svg?style=flat-square)](https://travis-ci.org/spasdk/dom)                                       | [![npm version](https://img.shields.io/npm/v/spa-dom.svg?style=flat-square)](https://www.npmjs.com/package/spa-dom)                                       | [![dependencies status](https://img.shields.io/david/spasdk/dom.svg?style=flat-square)](https://david-dm.org/spasdk/dom)                                       | [![dependencies status](https://img.shields.io/david/dev/spasdk/dom.svg?style=flat-square)](https://david-dm.org/spasdk/dom)
[spa-eslint](https://github.com/spasdk/eslint.git)                                 | (n/a)                                                                                                                                                     | [![npm version](https://img.shields.io/npm/v/spa-eslint.svg?style=flat-square)](https://www.npmjs.com/package/spa-eslint)                                 | [![dependencies status](https://img.shields.io/david/spasdk/eslint.svg?style=flat-square)](https://david-dm.org/spasdk/eslint)                                 | [![dependencies status](https://img.shields.io/david/dev/spasdk/eslint.svg?style=flat-square)](https://david-dm.org/spasdk/eslint)
[spa-gettext](https://github.com/spasdk/gettext.git)                               | [![build status](https://img.shields.io/travis/spasdk/gettext.svg?style=flat-square)](https://travis-ci.org/spasdk/gettext)                               | [![npm version](https://img.shields.io/npm/v/spa-gettext.svg?style=flat-square)](https://www.npmjs.com/package/spa-gettext)                               | [![dependencies status](https://img.shields.io/david/spasdk/gettext.svg?style=flat-square)](https://david-dm.org/spasdk/gettext)                               | [![dependencies status](https://img.shields.io/david/dev/spasdk/gettext.svg?style=flat-square)](https://david-dm.org/spasdk/gettext)
[spa-keys](https://github.com/spasdk/keys.git)                                     | [![build status](https://img.shields.io/travis/spasdk/keys.svg?style=flat-square)](https://travis-ci.org/spasdk/keys)                                     | [![npm version](https://img.shields.io/npm/v/spa-keys.svg?style=flat-square)](https://www.npmjs.com/package/spa-keys)                                     | [![dependencies status](https://img.shields.io/david/spasdk/keys.svg?style=flat-square)](https://david-dm.org/spasdk/keys)                                     | [![dependencies status](https://img.shields.io/david/dev/spasdk/keys.svg?style=flat-square)](https://david-dm.org/spasdk/keys)
[spa-preloader](https://github.com/spasdk/preloader.git)                           | [![build status](https://img.shields.io/travis/spasdk/preloader.svg?style=flat-square)](https://travis-ci.org/spasdk/preloader)                           | [![npm version](https://img.shields.io/npm/v/spa-preloader.svg?style=flat-square)](https://www.npmjs.com/package/spa-preloader)                           | [![dependencies status](https://img.shields.io/david/spasdk/preloader.svg?style=flat-square)](https://david-dm.org/spasdk/preloader)                           | [![dependencies status](https://img.shields.io/david/dev/spasdk/preloader.svg?style=flat-square)](https://david-dm.org/spasdk/preloader)
[spa-request](https://github.com/spasdk/request.git)                               | [![build status](https://img.shields.io/travis/spasdk/request.svg?style=flat-square)](https://travis-ci.org/spasdk/request)                               | [![npm version](https://img.shields.io/npm/v/spa-request.svg?style=flat-square)](https://www.npmjs.com/package/spa-request)                               | [![dependencies status](https://img.shields.io/david/spasdk/request.svg?style=flat-square)](https://david-dm.org/spasdk/request)                               | [![dependencies status](https://img.shields.io/david/dev/spasdk/request.svg?style=flat-square)](https://david-dm.org/spasdk/request)
[spa-wamp](https://github.com/spasdk/wamp.git)                                     | [![build status](https://img.shields.io/travis/spasdk/wamp.svg?style=flat-square)](https://travis-ci.org/spasdk/wamp)                                     | [![npm version](https://img.shields.io/npm/v/spa-wamp.svg?style=flat-square)](https://www.npmjs.com/package/spa-wamp)                                     | [![dependencies status](https://img.shields.io/david/spasdk/wamp.svg?style=flat-square)](https://david-dm.org/spasdk/wamp)                                     | [![dependencies status](https://img.shields.io/david/dev/spasdk/wamp.svg?style=flat-square)](https://david-dm.org/spasdk/wamp)


## Contribution ##

If you have any problems or suggestions please open an [issue](https://github.com/spasdk/meta/issues)
according to the contribution [rules](.github/contributing.md).


## License ##

`@spasdk/meta` is released under the [GPL-3.0 License](http://opensource.org/licenses/GPL-3.0).
