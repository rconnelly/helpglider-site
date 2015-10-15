
# Setup #

#### Gulpfile.js

The site uses a Gulp file to manage theme and site content editing. You’ll need to install Node.js and Gulp before using our included gulpfile.js.

To install Node visit [https://nodejs.org/download](https://nodejs.org/download/).

To install gulp, run the following command:

```
$ npm install gulp -g
```

When you’re done, install the rest of the theme's dependencies:

```
$ npm install
```

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

Run this command if you want realtime minification for editing purposes.

```
$ gulp watch
```


#### Bootstrap Theme Support

If you experience any problems with the above, or if you think you've found a bug with your theme - please don't hesitate to reach out to themes@getbootstrap.com. thanks!
