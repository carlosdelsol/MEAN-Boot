# Installation

To take advantage of Web Starter Kit you need to:

1. Install the dependencies if you don't already have them.
2. Get a copy of the code.
3. Modify the application to your liking.
4. Deploy your production code.

## Dependencies

The dependencies are:
* [Node.js](http://nodejs.org)
* [gulp.js](http://gulpjs.com)
* [Less](http://lesscss.org/)
* [BootStrap](http://getbootstrap.com/)

### Node

Bring up a terminal and type `node --version`.
If you require Node, go to [nodejs.org](http://nodejs.org/) and click on the big green Install button.

### BootStrap

If you require Bootstrap, it can be installed from the [Bootstrap downloads](http://getbootstrap.com/getting-started/) page.

### Less

If Less is installed it should return a version number at or above 3.3.x.
If you don't see any errors, proceed to check for [gulp](#gulp).
If you need to install Less, see the command-line instructions on the [Less installation]((http://lesscss.org/#using-less-installation) page.

### Gulp

Bring up a terminal and type `gulp --version`.
If Gulp is installed it should return a version number at or above 3.5.x.
If you need to install Gulp, open up a terminal and type in the following:

```sh
$ npm install --global gulp
```

This will install Gulp globally. Depending on your user account, you may need to gain elevated permissions using `sudo` (i.e `sudo npm install --global gulp`). Next, install the local dependencies Web Starter Kit requires:

```sh
$ sudo npm install
```

That's it! You should now have everything needed to use the Web Starter Kit.

# Getting the code

Once you have all of the dependencies installed, you only need to get the code.
[Download](https://github.com/carlosdelsol/MEAN-Bootstrap.git) a zip of version 0.4.0.
Extract the files where you want to work from.
Then start building awesome things!

You may also want to get used to some of the [commands](commands.md) available.
