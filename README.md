# Starving Artist Modified Jekyll Theme

This Jekyll theme is designed for a very basic display of artist work.
## Installation

The recommended installation is using rbenv and bundler.

### Install rbenv

Install rbenv and follow the instructions to update `.bash_profile`.

```
brew install rbenv
rbenv init
```

### Install the local version of Ruby

Install the local version of Ruby as defined by `.ruby-version`.

```
rbenv install
gem update --system
gem install bundler
```

### Install dependencies

Install all project dependencies from `Gemfile`.

```
bundler install
```

## Local development

When developing locally jekyll can be used to serve a local website.

```
jekyll serve
```

## Credits

This repository is entirely based on the great work of [chrisanthropic/starving-artist-jekyll-theme: A portfolio theme for Jekyll for artists to display their work - http://chrisanthropic.github.io/starving-artist-jekyll-theme/](https://github.com/chrisanthropic/starving-artist-jekyll-theme)