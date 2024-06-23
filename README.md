## Overview

This repository was designed for learning Webpack 5.

There are 2 special branches that you may want to check out:

- single-page-application. Contains webpack configuration for a Single Page Application.
- multiple-page-application. Contains webpack configuration for a Multiple Page Application.

## Single Page Application

#### Run in Development Mode

1. `git checkout single-page-application`
1. `npm run dev`

Application will be served on the `http://localhost:9000/`.

#### Run in Production Mode

1. `git checkout single-page-application`
1. `npm run build`
1. `npm start`

Application will be served on the `http://localhost:3000/`.

## Multiple Page Application

#### Run in Development Mode

1. `git checkout multiple-page-application`
1. `npm run dev`

Application will be served on the `http://localhost:9000/`.
It will show an empty page.

In order to go to the "Hello World" page, go to `http://localhost:9000/hello-world.html`.

In order to go to the "Kiwi" page, go to `http://localhost:9000/kiwi.html`.

#### Run in Production Mode

1. `git checkout multiple-page-application`
1. `npm run build`
1. `npm start`

Application will be served on the `http://localhost:3000/`.
It will show an empty page.

In order to go to the "Hello World" page, go to `http://localhost:3000/hello-world`.

In order to go to the "Kiwi" page, go to `http://localhost:3000/kiwi`.
