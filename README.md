#Middleman Broker

A middleman primer for Windows. Kick off a new middleman project with boilerplate code, starting from a fresh Windows install.

Built with [Middleman](http://middlemanapp.com). Read the [docs &rarr;](http://middlemanapp.com/basics/getting-started)

## Get Started

### Install required development environment
Starting from scratch, install, in order:

- [GIT for windows](http://git-scm.com/)
- [RubyInstaller for windows](http://rubyinstaller.org/)
  - [Ruby Develpment Kit for windows](https://github.com/oneclick/rubyinstaller/wiki/Development-Kit)
- [Bundler](http://bundler.io)
- [Node](http://nodejs.org/)
- [Bower](http://bower.io/)

#### Install Gems

```
$ bundle install --path=vendor
```

#### Install Bourbon, Neat and Bitters

Follow the instructions on each site to install:
- [Bourbon](http://bourbon.io)
- [Neat](http://neat.bourbon.io/)
- [Bitters](http://bitters.bourbon.io/)

Then go to to /source/assets/scss and run the respective installers
```
$ npm install node-bourbon
```

```
$ npm install node-neat
```

```
$ bitters install
```

#### Run Bower

```
$ bower install
```
##### Bower defaults

- [assets_init](https://github.com/kgcreative/assets_init)
- jQuery.js
- Fastclick.js

##### Important:
  - Replace the contents of `/source/assets/` with `/vendor/bower/assets_init/source`.

#### Run Middleman

View the local site at [localhost:4567](http://localhost:4567)

```
$ bundle exec middleman
```

### Build production site

Generates static site in `/build` directory.

```
$ bundle exec middleman build
```