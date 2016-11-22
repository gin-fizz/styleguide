# Styleguide

This is the living styleguide for pollistics.

[gin-fizz.github.io/styleguide](https://gin-fizz.github.io/styleguide).

This is running in `jekyll`. To serve it locally, install that first, and then run `jekyll serve`.

## Adding new components

All components are defined in `_components/name.md`. There you write a summary, syntax and examples.

Style is defined in `_sass/components/name.scss`.

:warning: also edit `_sass/__components__.scss` to include new files.

## Using the components

```html
<link rel="stylesheet" href="https://gin-fizz.github.io/styleguide/src/main.css">
```
