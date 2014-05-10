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

#### Run Middleman

View the local site at [localhost:4567](http://localhost:4567)

```
$ bundle exec middleman
```

#### Build production site

Generates static site in `/build` directory.

```
$ bundle exec middleman build
```

## Note

If Bower is installed, run:

```
$ bower install
```
#### Bower defaults

- [assets_init](https://github.com/joshfry/assets_init)
  - Replace the contents of `/source/assets/` with `/vendor/bower/assets_init/source`.
- jQuery.js
- Fastclick.js