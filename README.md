# Jupyter and JupyterLab

- [Credit and license](https://coderefinery.github.io/jupyter/license/)

## Local development

The following Gemfile will permit you to run jekyll locally

```
source 'https://rubygems.org'
gem 'github-pages', group: :jekyll_plugins
gem 'github-linguist'
gem 'rouge', '~>1.11.1'
```

Write it as Gemfile under the repository root.

```
$ export GEM_HOME=$HOME/.gem
$ export PATH=$PATH:$HOME/.gem/bin
$ bundler install
$ bundle exec jekyll serve
```

# Binder compability
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sunnivin/jupyter/tree/gh-pages/HEAD)

