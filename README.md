# generator-yogurt [![Build Status](https://secure.travis-ci.org/vdv73rus/generator-yogurt.png?branch=master)](https://travis-ci.org/vdv73rus/generator-yogurt)

A generator for [Yeoman](http://yeoman.io).


## Getting Started

### What is Yeoman?

Trick question. It's not a thing. It's this guy:

![](http://i.imgur.com/JHaAlBJ.png)

Basically, he wears a top hat, lives in your computer, and waits for you to tell him what kind of application you wish to create.

Not every new computer comes with a Yeoman pre-installed. He lives in the [npm](https://npmjs.org) package repository. You only have to ask for him once, then he packs up and moves into your hard drive. *Make sure you clean up, he likes new and shiny things.*

```
$ npm install -g yo
```

### Yeoman Generators

Yeoman travels light. He didn't pack any generators when he moved in. You can think of a generator like a plug-in. You get to choose what type of application you wish to create, such as a Backbone application or even a Chrome extension.

To install generator-yogurt from npm, run:

```
$ npm install -g generator-yogurt
```

Finally, initiate the generator:

```
$ yo yogurt
```

### Getting To Know Yeoman

Yeoman has a heart of gold. He's a person with feelings and opinions, but he's very easy to work with. If you think he's too opinionated, he can be easily convinced.

If you'd like to get to know Yeoman better and meet some of his friends, [Grunt](http://gruntjs.com) and [Bower](http://bower.io), check out the complete [Getting Started Guide](https://github.com/yeoman/yeoman/wiki/Getting-Started).

## What's next?
Just run
```
$ grunt server
$ grunt watch
```

And open http://127.0.0.1:9001 at your browser!

Then, if you change any of your jade template or sass stylesheet, your browser would be reloaded automatically! Open your work on many devices/screens and enjoy!

## What's inside?
* Jade (with partials)
* SASS

### Optionally
* Normalize.css or Eric Meyer reset.css
* Jquery
* SASS Data URI (base64 images generator)
* Russian rouble symbol font
* Imagemin optimization
* CSSO stylesheets optimization
* CSS concatination
* Sticky footer option

## Release history
* 2014-06-16 **0.0.6** - Remove optimization tasks from options, jade templates refactored, sticky footer option added.
* 2014-04-08 **0.0.5** - 'npm publish' makes me crazy. %)
* 2014-04-08 **0.0.4** - Grunt CSSO module added.
* 2014-04-07 **0.0.3** - Grunt imagemin module added.
* 2014-04-03 **0.0.2** - Russian rouble sign support added.
* 2014-04-02 **0.0.1** - first release.

## License

[MIT License](http://en.wikipedia.org/wiki/MIT_License)
