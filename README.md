[![Build Status](https://travis-ci.org/Josef-Friedrich/jekyll-navigation-tree.svg?branch=master)](https://travis-ci.org/Josef-Friedrich/jekyll-navigation-tree)
[![Rubygems downloads](https://img.shields.io/gem/dt/jekyll-navigation-tree.svg)](https://rubygems.org/gems/jekyll-navigation-tree)

# jekyll-navigation-tree

A Jekyll plugin for building hierarchial navigation trees from pages.

## Usage

```liquid
{% navigation_tree %}
```

```liquid
{% navigation_tree base/path %}
```

### Excluding Files

A list of URL patterns can be specified in the Jekyll configuration using a
`nav_tree:excludes` key. For example:

```yaml
nav_tree:
  excludes:
    - /foo.html
    - /assets*
    - /photos/*/*jpg.html
```

Items to exclude can be glob patterns with wildcards.

## Links

* [Source code on Github](https://github.com/Josef-Friedrich/jekyll-navigation-tree)
* [Project page on rubygems](https://rubygems.org/gems/jekyll-navigation-tree)
