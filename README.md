# GlossGen Website

This is the official website for GlossGen, built with Jekyll and hosted on GitHub Pages.

## Prerequisites

- Ruby version 2.7.0 or higher
- RubyGems
- GCC and Make

## Setup

1. Install Jekyll and Bundler:

```bash
gem install jekyll bundler
```

2. Install dependencies:

```bash
bundle install
```

3. Start the development server:

```bash
bundle exec jekyll serve
```

The site will be available at `http://localhost:4000`.

## Development

- The main stylesheet is in `assets/css/main.scss`
- Page layouts are in the `_layouts` directory
- Homepage styles are in `_sass/_home.scss`
- Add new pages in the root directory with `.html` or `.md` extension

## Deployment

The site is automatically deployed to GitHub Pages when changes are pushed to the main branch.

## License

Copyright © 2024 GlossGen. All rights reserved.
