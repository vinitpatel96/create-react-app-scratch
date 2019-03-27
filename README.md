*Creating a React App from scratch*

https://www.youtube.com/watch?v=deyxI-6C2u4

- React: main library
- React Dom: used to be a part of React however now that React is used in environment that don't don't include the DOM, now we use this library
- npm i react react-dom

- Webpack: beacause all of our react code has to be compiled and bundled into one file. 
- Dev Server: webpack dev server that includes live reload
- npm i --save-dev webpack webpack-dev-server webpack-cli

- Babel: need because react uses ES6 classes, so need to transpile that stuff down to browser friendly code. 
- Babel loader: need to compile JSX
- Babel env: compile ES6 and beyond
- HTML webpack plugin: generate build html file
- npm i --save-dev babel-core babel-loader babel-preset-env babel-preset-react html-webpack-plugin

- Set up webpack config

- html-webpack-plugin: simplifies creation HTML files to serve your bundles. use templates

- in order to use presets babel env, react. create .babelrc in root. 

- add scripts to package.json. to run webpack dev server and other to build it out in dist folder (package.json)