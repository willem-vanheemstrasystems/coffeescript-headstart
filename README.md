# coffeescript-headstart
CoffeeScript - Headstart

Based on http://learnwebtutorials.com/hello-world-coffeescript-example

## Installation

Run the following command to install coffee script globally using npm

npm install coffee-script -g

or

npm install

as in package.json we have set a postscript that will install coffee-script globally

## Compiling *.coffee to *.js

Run the following example (note: the output must come BEFORE the source)

coffee -o src/js/ -c src/coffee/helloworld.coffee

as a result a new file is created, named src/js/helloworld.js

## Let Watch recompile automatically

To automate the compiling of any *.coffee files to *.js files, use watch (-w) as follows:

coffee -w -o src/js/ -c src/coffee/helloworld.coffee

To escape watch use CTRL+C.
