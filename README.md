Assignment
=========================
## Quick Start ##

 -  Run 'npm install' to install all NPM dependency packages.
 -  Gulp and live-server should be installed globally by running `npm install -g gulp live-server`
 -  To start the live reload server, simply run `npm start`
 -  To build the assets run `gulp` in the root directory of the project. To watch files and build when files change run `gulp watch`

## Folder Structure and instruction to the developer ##

 -  Assets (JS, SASS) are stored in the `src/` directory.
 -  Assets are combined and minified and stored for use in `web/dist/` - files here should not be modified as they will be overwritten.
 -  To build the assets run `gulp` in the root directory of the project. To watch files and build when files change run `gulp watch`
 -  `web/` is the document root for the project, web servers should point to this directory.
 -  To start the live reload server, simply run `npm start`
 -  HTML files are contained under `web/` -> `web/index.html` is the default homepage.
 -  Images are stored under `web/images/`