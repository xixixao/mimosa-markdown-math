# markdown-math

Simple [Mimosa](https://github.com/dbashford/mimosa) skeleton for markdown with mathsy affiliation.

## Use

**Importantly**
```
$ npm install -g marked
```

then as usual

```bash
$ npm install -g mimosa
$ mimosa skel:new minimal ProjectName
$ cd ProjectName
$ make
```

Go to [http://localhost:3000](http://localhost:3000). Changes are automatically reflected via live reload.

## Setup

[CoffeeScript](http://http://coffeescript.org/), [Stylus](http://learnboost.github.io/stylus/), [Jade](http://jade-lang.com/), [marked](https://github.com/chjj/marked/), [MathJax](http://www.mathjax.org/), [ASCIIMath](http://www1.chapman.edu/~jipsen/mathml/asciimath.html)

## Customize

You can switch to other type of math syntax by changing the URL param to other [MathJax configuration](http://docs.mathjax.org/en/latest/config-files.html#common-configurations).

```
script(src='http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-MML-AM_HTMLorMML')
```
