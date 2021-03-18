npm init
git add README.md

git commit -m "first commit"
git branch -M main

git remote add origin https://github.com/adithyaa23/webpack.git
git push -u origin main

** or push an existing repository from the command line **

git remote add origin https://github.com/adithyaa23/webpack.git
git branch -M main
git push -u origin main

\*\*Webpack setup
npm init -y
npm i -D webpack webpack-cli webpack-dev-server

adding babel
bable-loader,babel-core and babel-preset-env is added with babel config babel-preset-env need to be added

Source map
devtool: "source-map",

for parsing css
npm i -D css-loader mini-css-extract-plugin

hot module Reloading
in devServer set hot:true

sass loadings
npm i -D sass sass-loader

postcss loaders
npm i -D postcss postcss-loader postcss-preset-env and create postcss.config.js

.browsrlist
for adding support of different browsers
