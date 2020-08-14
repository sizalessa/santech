# Hugo Scroll ![Test](https://github.com/janraasch/hugo-scroll/workflows/CI/badge.svg?branch=master&event=push)

📜 A [Hugo](https://gohugo.io/)-theme for pretty, quick and simple single-page websites.

![Screenshot Hugo Scroll Theme](https://raw.githubusercontent.com/janraasch/hugo-scroll/master/images/tn.png)

## Demo

For a current & working demo of this theme please check out https://janraasch.github.io/hugo-scroll/ 🎯.

## Quick Start

If you already have a hugo site on your machine, you can simply add this theme via

```
git submodule add https://github.com/janraasch/hugo-scroll.git themes/hugo-scroll
```

Then, adjust the `config.toml` as detailed below.

If you simply want to check out the `exampleSite`, you can run

```
git clone https://github.com/janraasch/hugo-scroll.git hugo-scroll
cd hugo-scroll
hugo server --source=exampleSite
```

## Adjust configuration / config.toml

Please check out the [config.toml](https://github.com/janraasch/hugo-scroll/blob/master/exampleSite/config.toml) included on the [exampleSite](https://github.com/janraasch/hugo-scroll/tree/master/exampleSite) of this theme.

## Adding content

You can add **a new section to the homepage** via running

```
hugo new homepage/my-new-content.md
```

To create **a page separate from the homepage**, run

```
hugo new my-new-page.md
```

## Issues / Feedback / Contributing
Please use [GitHub issues](https://github.com/janraasch/hugo-scroll/issues) and [Pull Requests](https://github.com/janraasch/hugo-scroll/pulls).

If you do not have a GitHub-account, feel free to hit me up via e-mail (see [janraasch.com](https://www.janraasch.com)).


## Sponsor [![Pay me][insert-coins-svg]][paypal-dot-me]
Please consider supporting my work on this theme via [PayPal][paypal-dot-me].

## Special Thanks 🎁

* Go to [Yonatan Wolowelsky](https://github.com/grmmph), for the great [GhostScroll](https://github.com/grmmph/GhostScroll)-theme which formed the basis of this [Hugo](https://gohugo.io/)-theme.
* Go to [Pexels](https://www.pexels.com), for supplying those wonderful *free* stock photos on the [exampleSite](https://github.com/janraasch/hugo-scroll/tree/master/exampleSite).

## License
[MIT License](http://en.wikipedia.org/wiki/MIT_License) © [Jan Raasch](https://www.janraasch.com)

[paypal-dot-me]: https://www.paypal.me/janraasch/29,00
[insert-coins-svg]: https://img.shields.io/badge/insert-coins-11dde2.svg
