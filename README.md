<img src="http://media.northbynorthwestern.com.s3.amazonaws.com/media/img/nbn_logo.svg" alt="drawing" width="100"/>


# generator-nbn-interactives

A [Yeoman](http://yeoman.io) generator to scaffold a development environment for building NBN interactive pieces. Borrowed from POLITICO.

See the docs on [readthedocs](http://generator-politico-interactives.readthedocs.io/en/latest/).

## How to use
To use, you will download this template onto your computer and create a symbolic link.

First, make sure you're using Node version 10.15.0.

```nvm install 10.15.0 ```

```nvm use 10.15.0```

Restart your terminal session and check that it's using the right version:

```node -v```

Make sure you have node and yarn installed:

```brew install yarn --without-node```

Clone this repository onto your machine:

`git clone https://github.com/northbynorthwestern/generator-nbn-interactives.git`

Go into the directory where you just cloned this repository:

```cd generator-nbn-interactives```

Inside the directory,
install the dependencies and create a symbolic link to the directory:

 ```npm install -g gulp-cli yo```

 ```npm link```

Somewhere else, make a directory for your project and run ```yo nbn-interactives``` inside of it.

## Developing a project
Once you have set up the template inside a directory, you can work on coding your project. You will do all of your work in the `src` directory (short for source).

HTML: your main html file is `src/templates/index.html`

CSS: your main stylesheet is `src/scss/_graphics.scss` (but you could add code into any of those files and it would still work).

JS: you will add JavaScript to `src/js/main-app.js`
