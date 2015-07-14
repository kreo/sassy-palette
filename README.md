# Sassy-palette

Color palette agnostic tool for _designers_ and front-end engineers. 

Sassy-palette simplifies design process by providing a nice API for mocking up random colors and gives full control over outputted colors.

## Why should I use it? 

* Comfy color fetching function
* Powerfull API for outputting random colors.
* Color palette agnostic. Can be used with __ANY__ color palette
* Improves and simplifies design process

## [Codepen.io Demo](http://codepen.io/Skoks/pen/waXoYY)

## [Documentation](http://skoks.github.io/sassy-palette/)

## [Sassmeister Playground](http://sassmeister.com/gist/ae041ed388b87eacba0d)

## Color palettes 

Sassy-palette uses [Google Material Colors](http://www.google.com/design/spec/style/color.html) by defualt, but it can be extended with your custom palette. 

For changing global palette, update `$palette` variable in `_sassy-palette/_config.scss`:

    $palette: $google-material-palette;

## Installation

_Git_:

    git clone git@github.com:Skoks/sassy-palette.git ./

_Bower_:

    bower install sassy-palette --save-dev

## Requirements

* Ruby Sass `v3.4`
* LibSass `v3.2`
