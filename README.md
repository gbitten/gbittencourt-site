## About

This repository implements the [GBittencourt](http://www.gbittencourt.net/) site.

## Resources

This site is built using:

* [GitHub pages](https://pages.github.com/)
* [Jekyll](https://jekyllrb.com/)
* [Architect theme](https://github.com/pietromenna/jekyll-architect-theme)

## Install and run the site on Ubuntu

### Clone de repository

```terminal
git clone  https://github.com/gbitten/gbittencourt-site.git
cd gbittencourt-site
```

### Install Ruby and Ruby Gems

```terminal
sudo apt-get install ruby-full build-essential zlib1g-dev
```

### Add environment variables

```terminal
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```

### Install Jekyll

Install blundler:

```terminal
gem install bundler
```

Install Jekyll and other dependencies:

```terminal
bundle install
```

### Run the site locally

```terminal
bundle exec jekyll serve
```
