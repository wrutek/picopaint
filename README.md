# Welcome Picopaint

Picopaint is an API for Picopaint project


PicoPaint provides an API for all online activities. It covers profiles management,
friends connections interactions, storing users sprites, images and palettes and
many more.

Currently we assume that everybody can create an account!!!


### Start the web server:

    revel run github.com/wrutek/picopaint

### Go to http://localhost:9000/ and you'll see:

    "It works"

## Code Layout

The directory structure of a generated Revel application:

    conf/             Configuration directory
        app.conf      Main app configuration file
        routes        Routes definition file

    app/              App sources
        init.go       Interceptor registration
        controllers/  App controllers go here
        views/        Templates directory

    messages/         Message files

    public/           Public static assets
        css/          CSS files
        js/           Javascript files
        images/       Image files

    tests/            Test suites


## Help

* The [API documentation](http://docs.picopaint.apiary.io).
* The [Getting Started with Revel](http://revel.github.io/tutorial/gettingstarted.html).
* The [Revel guides](http://revel.github.io/manual/index.html).
* The [Revel sample apps](http://revel.github.io/examples/index.html).

