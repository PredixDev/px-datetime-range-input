Px-Datetime-Range-Field [![Build Status](https://travis-ci.org/PredixDev/px-datetime-range-field.svg?branch=master)](https://travis-ci.org/PredixDev/px-datetime-range-field)
-----------------------------------------------

[![px-datetime-range-field demo](px-datetime-range-field.png?raw=true)](https://predixdev.github.io/px-datetime-range-field)

## Overview

Px-Datetime-Range-Field is a Predix Experience ('Px') component

## documentation

Read the full API and view the demo [here](https://predixdev.github.io/px-datetime-range-field).

## Local Development

Read https://github.com/pages/PX/technical-principles/

From the component's directory...

```
$ npm install
$ bower install
$ gulp sass
```

### API and examples

From the component's directory

```
$ gulp serve
```

Starts a local server. Navigate to the root of that server (e.g. http://localhost:8080/) in a browser to open the API documentation page, with link to the "Demo" / working examples.

### LiveReload

By default grunt depserve is configured to enable LiveReload and will be watching for modifications in your root directory as well as `/css`.

Your browser will also need to have the LiveReload extension installed and enabled. For instructions on how to do this please refer to [livereload.com/extensions/](http://livereload.com/extensions/).

Add, remove, modify file system patterns specified in the `depserve.options.livereload` array in your `Gruntfile.js`

This is an example depserve configuration:

```
depserve: {
    options: {
        open: '&lt;%= depserveOpenUrl %&gt;,
        livereload: [__dirname + "/js", __dirname + "/css", __dirname]
    }
}
```

Disable LiveReload by removing the `livereload` key from the configuration object.

### DevMode

From the component's directory run:

```
$ grunt devmode
```

Starts a local server exactly the same as if you had run `grunt depserve` however in addition it also runs `grunt watch` concurrently which will execute commands on file change according to the specified matching patterns.

This is an example `grunt watch` configuration which watches for changes to SASS files, then on changes executes SASS compilation and automatic prefixing:

```
watch: {
    sass: {
        files: ['sass/**/*.scss'],
        tasks: ['sass', 'autoprefixer'],
        options: {
            interrupt: true
        }
    }
}
```

GE Coding Style Guide
---------------------

[GE JS Developer's Guide](https://github.com/GeneralElectric/javascript)


### Known Issues
