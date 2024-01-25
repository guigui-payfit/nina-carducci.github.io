# Nina Carducci website

Nina Carducci website can be seen on your web browser by opening the "index.html" file with the "Live Server" extension from your VSCode editor. The tab to be opened URL is by default : http://localhost:5500/.

# Update of dependencies

Currently, the code depends on Bootstrap (CSS & JS) and jQuery (JS). To use the latest and stable versions of :

- Bootstrap : go on https://getbootstrap.com/ and apply instructions in the "Include via CDN" section.
- jQuery : go on https://releases.jquery.com/ and paste HTML lines related to the last minified version.

# File minification

## Minify CSS files

After a modification of a not-minified CSS file (without `.min` in the file name), ensure to create a minified version of your file as the minified file must be the one loaded by `index.html` for better performances.
You can minimify online a CSS file [here](https://www.toptal.com/developers/cssminifier).

## Minify JS files

After a modification of a not-minified JS file (without `.min` in the file name), ensure to create a minified version of your file as the minified file must be the one loaded by `index.html` for better performances.
You can minimify online a JS file [here](https://skalman.github.io/UglifyJS-online/).

# Microdata validation

## Rich Snippet Google validator

You can validate [Schema.org](https://www.schema.org/) microdata with the [Rich Snippet Google validator](https://search.google.com/test/rich-results).

## Facebook Open Graph microdata validator

You can validate Open Graph microdata with this [debugger](https://developers.facebook.com/tools/debug/).

## Twitter card validator

You can validate Twitter cards with this [validator](https://cards-dev.twitter.com/validator).
