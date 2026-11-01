# Tris Ramadhan's website

A personal website built with Jekyll and the GitHub Pages gem, published from the `gh-pages` branch.

## Run locally

Requirements: Ruby and Bundler.

Install the project dependencies, then start Jekyll:

```sh
bundle install
bundle exec jekyll serve
```

Open [http://localhost:4000](http://localhost:4000) to view the site. Jekyll rebuilds the site as you edit files. Stop the server with `Ctrl+C`.

## Site pages

- `index.md` contains the landing page bio and profile photo.
- `blog.html` lists posts at `/blog/`. The Blog item in the site navigation currently links to [Medium](https://medium.com/@trisrmdh).
- New posts belong in `_posts/` and use Jekyll's dated filename format, such as `YYYY-MM-DD-title.markdown`.

## Site assets and metadata

- `assets/profile.jpg` is the square profile image shown on the landing page.
- `favicon.png` is the site favicon.
- Montserrat is used for page paragraphs; IBM Plex Sans is used for the navigation and footer. Both are loaded from Google Fonts.
- Page title, description, Open Graph, and Twitter Card metadata are defined in `_includes/head.html`.
- Footer contact and social links are defined in `_includes/footer.html`.

## Build

To generate the static site without starting the local server:

```sh
bundle exec jekyll build
```

The generated files are written to `_site/`.
