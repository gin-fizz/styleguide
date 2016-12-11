# [Styleguide](https://style.pollistics.com/)

This is the living styleguide for pollistics.

[style.pollistics.com](https://style.pollistics.com/).

The styleguide is build with `jekyll`. To serve it locally, install that first, and then run `jekyll serve`.

You can then find your local development at <http://localhost:4000>

<details>
<summary>more</summary>
It's also possible to run it locally via `bundler`, then you run:

```sh
$ bundle install
$ bundle exec jekyll serve.
```

</details>

## Adding new components

All components are defined in `_components/name.md`. There you write a summary, syntax and examples.

Style is defined in `_sass/components/name.scss`.

:warning: also edit `_sass/__components__.scss` to include new files.

## Using the components

```html
<link rel="stylesheet" href="https://style.pollistics.com/src/main.css">
```

## Behind the scenes

Jekyll is being deployed to Netlify on every commit to `master`, as well as on every pull request a `staging` deploy is being made. You can see that one on "view checks", "view detail" on a pull request.
