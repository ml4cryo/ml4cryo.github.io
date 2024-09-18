# Website ML4Cryo

This is based on Julia Kaltenborn's website.

## Installation
Get:
- bundle
- sass stuff
- ruby
- gem

## Usage

Watch changes in your css file:
```
sass --watch _sass/mystyles.scss:assets/css/mystyles.css
```

Build it (needs to be done evertime you change configs, yamls, etc.)
Builds to ML4cryo/ml4cryo.github.io/_site

```
bundle exec jekyll build --watch
```

Run website (in separate terminal) e.g. http://127.0.0.1:4000

```
bundle exec jekyll serve --incremental
```

## CSS

assets/css/mystyles.css

Overwrite css properties here:

_sass/main.scss

[see sass website](https://sass-lang.com/)


insert `style="color: #224760;"'

