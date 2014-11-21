# Add the Node JS .gitignore

## Sets up an empty package.json file
1.  npm init
2.  bower init
3.  check .gitignore
  + added bower_components
  + added _site
  + .sass
  + .sass-cache

## Dependencies
  + --save for dependencies that are necessary for site to run
    + e.g. jquery
      + this can be done with --save-dev if you use grunt concat plugin
  +--save-dev for dev dependencies that are not necessary for site to run
    + e.g. mocha
  1.  $ bower install "dependency" --save(-dev)
    1.  jquery
    2.  lodash
    3.  mocha
    4.  chai
    5.  normalize.css
    6.  normalize.scss
