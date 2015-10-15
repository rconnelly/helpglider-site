# Site Content Editing #
Use these gulp commands when working on content (not bootstrap theme).

## Dev Preview ##
Previews content that is being worked on. Useful when you are working on the site's content. 

```
$ gulp preview
```
## Publish Preivew ##

Run this command to preview a final version before pushing up to AWS. This command will copy all html, css, and js and then run a server to preview. Use this command to do a final check before going live.

```
$ gulp publish-preview
```

## Publish To AWS ##

Run this command to copy all production files to  

```
$ gulp publish
```

# Theme Editing #
Use these commands when working on the theme of the site.

Run this command to minify css and js and copy to dist folder.

```
$ gulp build
```

Run this command if you want realtime minification for editing purposes

```
$ gulp watch
```


# More Bootstrap Theme Instructions #

Within your Bootstrap Theme you’ll find the following directories and files, grouping common resources and providing both compiled and minified distribution files, as well as raw source files.

```
toolkit/
  ├── gulpfile.js
  ├── package.json
  ├── README.md
  ├── docs/
  ├── less/
  │   ├── bootstrap/
  │   ├── custom/
  │   ├── variables.less
  │   └── toolkit.less
  ├── js/
  │   ├── bootstrap/
  │   └── custom/
  ├── fonts/
  │   ├── bootstrap-entypo.eot
  │   ├── bootstrap-entypo.svg
  │   ├── bootstrap-entypo.ttf
  │   ├── bootstrap-entypo.woff
  │   └── bootstrap-entypo.woff2
  └── dist/
      ├── toolkit.css
      ├── toolkit.css.map
      ├── toolkit.min.css
      ├── toolkit.min.css.map
      ├── toolkit.js
      └── toolkit.min.js
```

#### Docs and Examples

The `docs` directory contains all the static resources for your Themes docs and examples. To view, just open in your favorite browser!

```
$ open docs/index.html
```


#### Gulpfile.js

We've also included an optional Gulp file to help you get started with theme customization. You’ll need to install Node.js and Gulp before using our included gulpfile.js.

To install Node visit [https://nodejs.org/download](https://nodejs.org/download/).

To install gulp, run the following command:

```
$ npm install gulp -g
```

When you’re done, install the rest of the theme's dependencies:

```
$ npm install
```

From here on out, simply run `gulp` from your terminal and you're good to go!

+ `gulp` - recompiles and minifies your theme assets.


#### Support

If you experience any problems with the above, or if you think you've found a bug with your theme - please don't hesitate to reach out to themes@getbootstrap.com. thanks!
