# Wren Security Documentation Website

Wren Security documentation website is based on [Antora](https://antora.org) and [GitHub Pages](http://pages.github.com).
Main development branch contains Antora configuration files.
Website is built through GitHub Action pipeline that deploys all artifacts into `gh-pages` branch.


## Development guide


### Prerequisites

First of all you have to install [NodeJS](https://nodejs.org) and all needed dependencies through NPM (`npm install`).


### Development build

To execute development build run this command:

    npx antora --fetch antora-playbook.yml

Then open following URL `file:///{GIT_REPOSITORIES}/docs.wrensecurity.org/build/site/index.html` in your browser.