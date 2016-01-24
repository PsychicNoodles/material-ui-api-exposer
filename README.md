# Material-UI-API-Exposer

A simple script that exposes the components in MaterialUI, which are normally only accessable when compiling with it as a dependency, to the global window context. Useful for when using libraries that cannot be compiled using Browserify/Webpack, such as Clojurescript-based ones.

Run the script with `npm run build`.

Output goes by default into lib/material-ui.js. This can be changed by going into the package.json file and changing the `build` script.