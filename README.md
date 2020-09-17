# Engineering at Bestow

## Contributing

This is a public repository. Changes that are merged to `main` are automatically deployed to a publicly visible GitHub pages site.

These commands will install the dependencies needed for the static site generator, [Jeykll](https://jekyllrb.com/). This allows the site to be build and previewed locally.
```
bundle install --path vendor/bundle
```

To start a local server, run:
```
bundle exec jekyll serve
```
Then navigate to `http://localhost:4000/` in your favorite web browser. Append the `--watch` argument to the above command for auto-generation when changes are saved.


[Using Jekyll with Bundler](https://jekyllrb.com/tutorials/using-jekyll-with-bundler/)