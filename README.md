Repository for the website waakster.nl.

This is a fork of Methods. See: https://github.com/18F/methods (https://methods.18f.gov)

###  Install

You will need [Ruby](https://www.ruby-lang.org) ( > version 2.1.5 ). You may consider using a Ruby version manager such as [rbenv](https://github.com/sstephenson/rbenv) or [rvm](https://rvm.io/) to help ensure that Ruby version upgrades don’t mean all your [gems](https://rubygems.org/) will need to be rebuilt.

On macOS, you can use [Homebrew](http://brew.sh/) to install Ruby in `/usr/local/bin`, which may require you to update your `$PATH` environment variable:

```
shell
$ brew update
$ brew install ruby
```

To serve this website locally, using `waakster` as the name of your new repository:
Run each of the following steps to get the site up and running.

```
git clone https://github.com/waakster/waakster.github.io.git waakster
cd waakster
bundle install
bundle exec jekyll serve
```

You should be able to see the site at: `http://localhost:4000/`

