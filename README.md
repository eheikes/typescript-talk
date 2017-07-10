# Intro to Typescript

This was a talk given at the Des Moines Web Geeks meetup on July 10, 2017.

The presentation can be viewed at [eheikes.github.io/typescript-talk](http://eheikes.github.io/typescript-talk/), or from the [`dist` folder](dist/) in this repository.

## Local Build

The presentation can be built and served locally using [Node.js](https://nodejs.org/). To begin, `git clone` this repository and then run `npm install` at the command line (in the new folder).

The npm tasks are:

* `npm run clean` -- Deletes the `dist` folder
* `npm run build` -- Compiles the presentation into the `dist` folder (you'll need [dos2unix](http://linuxcommand.org/man_pages/dos2unix1.html) on your machine)
* `npm run serve` -- Starts a local server to serve the presentation
* `npm start` -- Starts a local server and rebuilds the project if files change
* `npm run deploy` -- Deploys the presentation to the Github Page
