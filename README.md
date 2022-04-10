

# LibreSlam

[![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://github.com/hhuslamlab/libreslam/blob/master/LICENSE) [![Ruby](https://badgen.net/badge/icon/ruby?icon=ruby&label)](https://https://ruby-lang.org/)

This is the source code for the [LibreSlam workshop](https://slam.phil.hhu.de/libreslam).


## Installation

### Ubuntu

#### Pre-requisites

Install Ruby and other prerequisites
``` sh
sudo apt-get install ruby-full build-essential zlib1g-dev
```

Avoid installing RubyGems packages (called gems) as the root user. Instead, set up a gem installation directory for your user account. The following commands will add environment variables to your ~/.bashrc file to configure the gem installation path:

``` sh
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```

Install Jekyll and Bundler

``` sh
gem install jekyll bundler
```

#### Jekyll packages

``` sh
bundle install
```

`

## Running

``` sh
bundle exec jekyll serve
```


