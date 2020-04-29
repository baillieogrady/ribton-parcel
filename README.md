# Ribton parcel
[![devDependency Status](https://img.shields.io/david/dev/roots/sage.svg?style=flat-square)](https://david-dm.org/baillieogrady/ribton-parcel#info=devDependencies)

**In development**

Ribton parcel is a static landing page built by replicating the [Ribton - product landing page](https://preview.themeforest.net/item/ribton-product-landing-page/full_screen_preview/25897391?_ga=2.164587135.170062314.1587242468-1630632801.1586424589).

The purpose was to demonstrate the stages I take to build simple static websites. I use [parceljs](https://parceljs.org/) for my build configuration so I can focus more on building the website.

## Development

### Requirements

Make sure all dependencies have been installed before moving on:

* [Node.js](https://nodejs.org/en/)

### Installation

Install parcel:

```
$ npm install -g parcel-bundler
```

Clone this repo:

```
$ git clone https://github.com/baillieogrady/ribton-parcel
```

### Build commands

Ensure you're inside the website directory:

* `parcel index.html` — Compile assets when file changes are made, start Browsersync session
* `parcel build index.html` — Compile assets for production

See more commands [here](https://parceljs.org/cli.html).
