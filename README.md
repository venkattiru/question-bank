# question-bank
create question bank

webpack config:

we just created configurations that will be used by Webpack when bundling our react project

the first two lines are quite straight-forward we are just importing HtmlWebpackPlugin that we installed earlier and path which is a Node build in package that handles file paths in a node project | learn more about path here

entry: specifies the main file (the entry) of our application which will be the index.js file we created

output: specifies where Webpack will put it's files after bundling and we specify the path and the file name of that Webpack bundle

target: specifies where our app will run

devServer: specifies our development server settings

port: specifies the port our app will run on once started
static: specifies the directory webpack will use to serve static files
open: automatically open the browser after it had bundled our files
hot: enables webpack Hot module replacement exchanges, adds, or removes modules while an application is running, without a full reload. to improve performance
liveReload: automatically update the app as you make changes
resolve: tells Webpack files to consider when building our app you can specifies files with several extensions

modules: where we specify rules about how Webpack will handle different files when building our app

plugin: where we specify plugins to use with webpack and we will need HTMLWebpackPlugin which will generate html files for our bundles and are twlling it to use our index.html file in the public folder as a template