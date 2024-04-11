# Install

## Requirements
Install ruby on Ubuntu system
```shell
sudo apt-get install ruby-full build-essential zlib1g-dev
```

The following commands will add environment variables to your `~/.bashrc` file to configure the gem installation path:
```shell
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```

## Jekyll setup
Jekyll setup: https://jekyllrb.com/docs/step-by-step/01-setup/

```shell
gem install jekyll bundler
```

To initialize the `Gemfile` with gem dependecies
```shell
bundle init
```

To install the gems and resolve dependecies
```shell
bundle install
```

Localhost build command
```shell
bundle exec jekyll serve --livereload
```
