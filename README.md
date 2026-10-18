# Tris Ramadhan's website

This repository contains a personal website built with Jekyll and the GitHub Pages gem.

## Run locally

Requirements: Ruby and Bundler.

Install the project dependencies, then start Jekyll:

```sh
bundle install
bundle exec jekyll serve
```

Open [http://localhost:4000](http://localhost:4000) to view the site. Jekyll rebuilds the site as you edit files. Stop the server with `Ctrl+C`.

## Site pages

- `index.md` is the About page at `/`.
- `blog.html` lists posts at `/blog/`.
- New blog posts go in `_posts/` and use Jekyll's dated filename format, such as `YYYY-MM-DD-title.markdown`.

## Build

To generate the static site without starting the local server:

```sh
bundle exec jekyll build
```

The generated files are written to `_site/`.
