# modules

Some npm modules to use in a good ol' fashioned `<script>` tag.

Links found and files downloaded **2020 June 10** or date noted

## jquery - 2020jun10

npm
* https://www.npmjs.com/package/jquery

guide
* https://jquery.com/download/

cdn
* https://code.jquery.com/jquery-3.5.1.js
* https://code.jquery.com/jquery-3.5.1.min.js

files
```
page_modules/jquery-3.5.1.js
page_modules/jquery-3.5.1.min.js
```

## vue, vue router - 2020jun10

npm
* https://www.npmjs.com/package/vue
* https://www.npmjs.com/package/vue-router

guide
* https://vuejs.org/v2/guide/installation.html
* https://router.vuejs.org/installation.html

cdn
* https://vuejs.org/js/vue.js
* https://vuejs.org/js/vue.min.js
* https://unpkg.com/vue-router/dist/vue-router.js

files
```
page_modules/vue.js
page_modules/vue.min.js
page_modules/vue-router.js
```

## react, react dom, babel standalone - 2020jun10

npm
* https://www.npmjs.com/package/react
* https://www.npmjs.com/package/react-dom
* https://www.npmjs.com/package/@babel/standalone

guide
* https://reactjs.org/docs/cdn-links.html
* https://reactjs.org/docs/add-react-to-a-website.html

cdn
* https://unpkg.com/babel-standalone@6/babel.min.js
* https://unpkg.com/react@16/umd/react.development.js
* https://unpkg.com/react@16/umd/react.production.min.js
* https://unpkg.com/react-dom@16/umd/react-dom.development.js
* https://unpkg.com/react-dom@16/umd/react-dom.production.min.js

files
```
page_modules/babel.min.js
page_modules/react.development.js
page_modules/react.production.min.js
page_modules/react-dom.development.js
page_modules/react-dom.production.min.js
```

## js-yaml - 2020jun10

npm
* https://www.npmjs.com/package/js-yaml

guide
* http://nodeca.github.io/js-yaml/

github zip
* https://github.com/nodeca/js-yaml/releases
* https://github.com/nodeca/js-yaml/archive/3.14.0.zip
* js-yaml-3.14.0.zip/dist/js-yaml.js
* js-yaml-3.14.0.zip/dist/js-yaml.min.js

files
```
page_modules/js-yaml.js
page_modules/js-yaml.min.js
```

## markdown-it, highlight.js - 2020jun10

npm
* https://www.npmjs.com/package/markdown-it
* https://www.npmjs.com/package/highlight.js

guide
* https://markdown-it.github.io/
* https://github.com/markdown-it/markdown-it#install
* https://cdnjs.com/libraries/markdown-it
* https://highlightjs.org/download/

cdn
* https://cdnjs.cloudflare.com/ajax/libs/markdown-it/11.0.0/markdown-it.js
* https://cdnjs.cloudflare.com/ajax/libs/markdown-it/11.0.0/markdown-it.min.js
* https://cdn.jsdelivr.net/gh/highlightjs/cdn-release@10.0.3/build/highlight.min.js
* https://cdn.jsdelivr.net/gh/highlightjs/cdn-release@10.0.3/build/styles/default.min.css

files
```
page_modules/markdown-it.js
page_modules/markdown-it.min.js
page_modules/highlight.min.js
page_modules/highlight.min.css (renamed from default.min.css)
```

## moment - 2020jun10

npm
* https://www.npmjs.com/package/moment

guide
* https://momentjs.com/

cdn
* https://momentjs.com/downloads/moment.js
* https://momentjs.com/downloads/moment.min.js

files
```
page_modules/moment.js
page_modules/moment.min.js
```

## collections - 2020jul19

npm
* https://www.npmjs.com/package/collections

guide
* http://www.collectionsjs.com/

github zip
* https://github.com/montagejs/collections/releases
* https://github.com/montagejs/collections/archive/v5.1.11.zip
* collections-5.1.11.zip/collections.min.js

files
```
page_modules/collections.min.js
```

## smartquotes - 2020dec12

npm
* https://www.npmjs.com/package/smartquotes

guide
* https://smartquotes.js.org/
* https://github.com/kellym/smartquotes.js

files
```
page_modules/smartquotes.js
page_modules/smartquotes.js.map
```

## Notes

Targets I'm interested in:

* HTML's `<script src="">` *[link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/script)*
* node's `require()` *[link](https://nodejs.org/api/modules.html#modules_require_id)*
* [Electron](https://www.electronjs.org/)
* [Beaker](https://beakerbrowser.com/)
* The browser's `file:///` URI scheme *[link](https://tools.ietf.org/html/rfc8089)*
* Babel [standalone](https://babeljs.io/docs/en/babel-standalone)

package.json saves all these modules the node way; where in `node_modules` are the files you downloaded?

can't you get each one of these from [UNPKG](https://unpkg.com/) or another recent similar site? how does unpkg deal with a npm module that has a bunch of additional dependencies?
