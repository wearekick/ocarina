# Ocarina

Ocarina is a collection of style guides for [Kick Interactive](http://www.wearekick.co.uk) written in [Sass](http://sass-lang.com/) and JavaScript.

```
git clone git@github.com:wearekick/ocarina.git
cd ocarina
```


## Documentation

An online version of the documentation for Ocarina is hosted on [GitHub pages](https://pages.github.com/) and available at [wearekick.github.com/ocarina](http://wearekick.github.com/ocarina).

### Requirements

Ocarina's documentation is built using the static site generator [Jekyll](https://jekyllrb.com/) which runs on Ruby. To develop this locally you will need Ruby version 2.0.0, or higher.

```
# Check version of Ruby
ruby -v
```

If the command above returns a lower number or you don't have Ruby installed, you can get version 2 using [RVM](https://rvm.io) or directly from the [Ruby website](https://www.ruby-lang.org/en/downloads/).

You will also need to have NodeJS. This can be installed using [NVM](https://github.com/creationix/nvm) or directly from the [Node.js website](https://nodejs.org/en/download/).

### Installation

The project's dependencies can be installed using NPM. 

```
npm install
```

### Developing

To run a local jekyll server use the following command and point your browser to `http://localhost:4000`.

```
npm start
```
