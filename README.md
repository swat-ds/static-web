# :raised_hands: Static Web Development :raised_hands:

Resources used for Static Web Development workshop, [Tri-Co Hackathon 2019](https://tri-co-hackathon.github.io) @ Swarthmore College, Feb 8-9.

## What is [Jekyll](https://jekyllrb.com/)?

Jekyll is Ruby Gem that ...

... parses plaintext files ...

- HTML
- CSS/SASS
- Markdown
- YML
- json, csv, etc.

... and automagically generates HTML

***But there are [many many static site generators](https://www.staticgen.com/)***

## Getting started

A more detailed version of these instructions can be found [here](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/).

1. clone or download a Jekyll theme
2. Make sure the `Gemfile` has this line `gem 'github-pages', group: :jekyll_plugins`
3. `$ cd project-directory` **/ navigate to project directory you just downloaded**
3. `$ gem install bundler` **/ install the helper gem bundles**
4. `$ bundle install --path vendor/bundle` **/ install the gems listed in the Gemfile**
5. `$ bundle exec jekyll serve` **/ develop locally**
6. `$ bundle exec jekyll build` **/ build site files**

## GitHub Pages

- You can add an arbitrary `index.html` to any branch and [select it in the repo settings](https://help.github.com/articles/configuring-a-publishing-source-for-github-pages/)
- [GitHub supported themes](https://pages.github.com/themes/)
- [GitHub remote theme support](https://help.github.com/articles/adding-a-jekyll-theme-to-your-github-pages-site/#adding-a-jekyll-theme-in-your-sites-_configyml-file)

## Resources

- **[Presentation Slides](https://slides.com/swatref/deck-116)**
- **[Jekyll](https://jekyllrb.com/)**
- **[Bundler](https://bundler.io/)**
- **[Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)**
- **[YAML](https://learnxinyminutes.com/docs/yaml/)**
- **[GitHub Pages](https://pages.github.com/)**
- **[GitHub Pages <3 Jekyll](https://help.github.com/articles/using-jekyll-as-a-static-site-generator-with-github-pages/)**
- **[lunr.js](https://lunrjs.com/)**
- **[DataTables](https://github.com/DataTables/DataTables)**
- **[Leaflet.js](https://leafletjs.com/)**



---

# Pineapple

Pineapple is a minimalistic [Jekyll](https://jekyllrb.com) portfolio theme that focuses on putting your projects in the spotlight.

![Pineapple screenshot](https://user-images.githubusercontent.com/9528895/38713105-6dda8a74-3ec7-11e8-8062-8aa6cf24c795.jpg)

See Pineapple in action on the [demo site](https://arnolds.io/pineapple/).

## Contents

- [Setup](#setup)
- [Deploy to Github Pages](#deploy-to-github-pages)
- [Creating projects](#creating-projects)
- [Resources](#resources)
- [License](#license)

## Setup

Install dependencies:

```
$ gem install jekyll bundler
```

Pulldown the project:

```
$ git clone git@github.com:arnolds/pineapple.git
$ cd pineapple
```

Start Jekyll:

```
$ jekyll serve
```

Browse to http://127.0.0.1:4000/pineapple/ for some Pineapple goodness.

## Deploy to Github Pages

1. Fork this repository, then rename the repository to yourgithubusername.github.io.
2. Update user configuration values in `_config.yml`, and also set `baseurl: ""`.

## Creating projects

Projects are created as `.md` documents within the `_posts/projects` directory. They follow the same naming conventions as regular [Jekyll posts](https://jekyllrb.com/docs/posts/). Pineapple comes with four example projects, which you should use as a guide for creating your own e.g. [Red Pineapple](_posts/projects/2017-04-01-redpineapple.md).

## Resources

- [Apple Devices PSD Mockup Templates](https://www.graphicsfuel.com/2016/04/apple-devices-psd-mockup-templates/)

## License

Open sourced under the [MIT license](LICENSE.md).

test commit
