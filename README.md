# IDMX 11ty Sass Starter

The set of development scripts in this starter is configured to watch and compile a simple Sass structure using 11ty.

The code is located in the `src` folder and the page is created in the `public` folder.

The `settings.json` in the `.vscode` folder sets the `LiveServer` configuration to serve from the `public` folder and can be used to serve the built page.

The build process includes minifiying and autoprefixing of styles via the `postbuild` script, which runs automatically after a `build`.

## Installation

**`npm install`**

>Run this command once to install the needed node modules.

## Development Scripts

**`npm start`**

> This script runs 11ty with hot reload and served at the url localhost:8080. It will reload whenever there are HTML or Sass changes.

**`npm run build`**

> This script does a production build and includes minified, autoprefixed CSS.

Use this as the "Publish command" if needed by hosting services such as Netlify.

## Resources

<small>The starter was inspired by [11ty Sass Skeleton](https://github.com/5t3ph/11ty-sass-skeleton) by [@5t3ph](https://twitter.com/5t3ph)</small>

Devil's Edge by Wilfrid Wilson Gibson

This poem is represented in the layout of the page as simplistic with a dark theme showing the struggle of the character within the poem.

Credit for the poem goes to Wilfrid Wilson Gibson and can be found at: 
https://www.public-domain-poetry.com/wilfrid-wilson-gibson/devils-edge-38024

Where as the photo found on Unsplash was posted by Daniel Jensen and can be found at:
https://unsplash.com/photos/closeup-photo-of-persons-hand-NMk1Vggt2hg