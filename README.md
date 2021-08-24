# Gulp & BrowserSync in SASS

This is a setup for Sass, gulp and browser sync compiling SCSS into CSS file in its own folder.

## Setup
Step 1: Create a folder

Step 2: Install `npm install -g gulp-cli` globally

Step 3: Initialize with folder from step 1 with `npm init`

Step 4: Install the following dev dependencies with npm
`npm install -D gulp gulp-sass browser-sync`

Step 5: Create a file, `gulpfile.js` as gulp is a build tool and controls what gulp is going to do.

### Run the installation
Use `gulp style` to create the dist/css folder included in it is the CSS file. Make sure you include it in `index.html` head element.

The `gulp watch` automatically watch the file and refreshes the browser on save of the document.

#### Author
Teri Eyenike
