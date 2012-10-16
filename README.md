# Angular Socket.io Seed

Start an awesome app with AngularJS on the front, Socket.io + Express + Node on the back. This
project is an application skeleton for writing [AngularJS](http://angularjs.org/) apps that use
web sockets to add real-time functionality. If you're not planning on using web sockets, you
should consider the [Angular Express Seed](https://github.com/btford/angular-express-seed) instead.

The seed contains angular libraries, test libraries and a bunch of scripts all preconfigured for
instant web development gratification. Just clone the repo (or download the zip/tarball) and
you're ready to develop your application.

The seed app shows how to wire together Angular client-side components with Socket.io and Express
on the server. It also illustrates writing angular partials/views with the Jade templating library.

_Note: Although Jade supports interpolation, you should be doing that mostly on the client. Mixing
server and browser templating will convolute your app. Instead, use Jade as a syntactic sugar for
HTML, and let AngularJS take care of interpolation on the browser side._

## How to use it

Clone the angular-socket-io-seed repository and start hacking!

### Running the app

Runs like a typical express app:

    node app.js

### Receiving updates from upstream

Just fetch the changes and merge them into your project with git.

## Directory Layout
    
    app.js              --> app config
    package.json        --> for npm
    public/             --> all of the files to be used in on the client side
      css/              --> css files
        app.css         --> default stylesheet
      img/              --> image files
      js/               --> javascript files
        app.js          --> declare top-level app module
        controllers.js  --> application controllers
        directives.js   --> custom angular directives
        filters.js      --> custom angular filters
        services.js     --> custom angular services
        lib/            --> angular and 3rd party JavaScript libraries
          angular/
            angular.js            --> the latest angular js
            angular.min.js        --> the latest minified angular js
            angular-*.js          --> angular add-on modules
            version.txt           --> version number
    routes/
      index.js          --> route for serving HTML pages and partials
    views/
      index.jade        --> main page for app
      layout.jade       --> doctype, title, head boilerplate
      partials/         --> angular view partials (partial jade templates)
        partial1.jade
        partial2.jade



## Docs

For more info on AngularJS read http://angularjs.org/
For more info on Express and Jade, read http://expressjs.com/ and http://jade-lang.com/
