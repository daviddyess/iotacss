# iotaCSS Starter Kit
#### by David Dyess II ([@daviddyess](https://github.com/daviddyess))

"[iotaCSS](http://iotacss.com) is a SASS based, Object Oriented CSS framework that fully adapts to your design and provides everything you need to develop in a fast and clean way." -iotaCSS

The point of this project is to bring all of iotaCSS together into a complete starter kit.

### Disclaimer:

iotaCSS was not created nor is it maintained by David Dyess II. This project simply uses the greatness, but can't claim credit for it.

#### Dislaimer II:

This is a work in progress, but feel free to add any issues, pull requests, or feature requests. 

Bug reports, pull requests, or feature requests for [iotaCSS modules](https://github.com/iotacss/) should be reported in the module's [iotaCSS repo](https://github.com/iotacss/).

## Getting Started

1. Check out the documentation on the [iotaCSS.com](https://www.iotacss.com/) web site.
2. Fork this repo
3. Install:

`npm install`

4. Customize
5. Use your favorite SASS compiler, for node-sass:

`npm install -g node-sass`

`node-sass src/main.scss dist/main.css`
* A compiled version is already in the repo as dist/preview.css to preview

## Settings

The best way to know what the settings are right now is to view each repo at [iotaCSS Github](https://github.com/iotacss).

I am in the process of documenting settings within each of the files in `/src`.

To customize, simply edit the appropriate file in the `/src` folder. 

You can also add files within the `/src/settings`, `/src/tools`, etc. folders, just remember to `@import` them in the `main.scss` file.

## Tips and Tricks

1. Remember this is SASS, so you have to override variables before the @import

## Links

* [iotaCSS.com](https://www.iotacss.com/)
* [iotaCasts.com](https://www.iotacasts.com/)
* [NPM /~iotacss](https://www.npmjs.com/~iotacss)
  * If you notice a module listed that isn't incuded here, please submit an issue and it'll be added.
* [Github /iotacss](https://github.com/iotacss/)


## Why?

iotaCSS is wonderful, but managing all of the different modules individually through NPM can be a hassle. This kit gives you the option of selecting which modules to include, without having to add or remove anything. You simply use a setting and SASS does the rest. This is not a fork of iotaCSS, all of the dependencies here are the same NPM modules you would install indvidually.

## Legal

iotaCSS is Copyright © 2016–2017 iotaCSS and is released under the Apache License, 2.0.

The iotaCSS Starter Kit is Copyright © 2017 David Dyess II and also licensed under the Apache License, 2.0 for consistency.

