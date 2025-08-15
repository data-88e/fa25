# Data 88E Fall 2025 Website

[![Deploy Jekyll site to Pages](https://github.com/data-88e/fa25/actions/workflows/jekyll.yml/badge.svg)](https://github.com/data-88e/fa25/actions/workflows/jekyll.yml)
[![Run all page tests](https://github.com/data-88e/fa25/actions/workflows/rspec.yml/badge.svg)](https://github.com/data-88e/fa25/actions/workflows/rspec.yml)

## Set Up

**The berkeley-class-site template requires Ruby 3.3.7 or higher and bundler >= 2.6**
Install Ruby before continuing. You can check your Ruby version by running:

```bash
ruby --version
bundle --version
```

Prerequisites:

- You have everything that [Jekyll requires](https://jekyllrb.com/docs/installation/)
- You have installed [Bundler](https://bundler.io/): Run `gem install jekyll bundler`

## Clone the repository (SSH) and install dependencies

```bash
git clone git@github.com:data-88e/fa25.git
bundle install
```

## Local Testing
View the site locally 

```
cd fa25
bundle exec jekyll serve
```

## Deployment

Via [GitHub Pages](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll).


## License

[MIT](LICENSE)

