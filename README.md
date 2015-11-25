# Flux TodoMVC Example

## How to run the application

You must have [npm](https://www.npmjs.org/) installed on your computer.
From the root project directory run these commands from the command line:

    npm install

This will install all dependencies.

To build the javascript files of application, first run this command:

    webpack

This will perform an initial build and will update client.js and server.js with any changes you wish to make.

Install gulp globally:

    npm install gulp -g

To enable watcher you have to run this command:

    gulp watch

This will watch the javascript folder ToDoList and when you save any changed file it will recompile the bundles.

