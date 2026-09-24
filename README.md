# Vance Yu (郁万祥)

Source repository for my academic homepage, built with [Academic Pages](https://academicpages.github.io/), a GitHub Pages template for personal and professional portfolio-oriented websites.

**Live site:** <https://vance-yu.github.io/hello/>

## About

- **Name:** Vance Yu (郁万祥)
- **Bio:** M.S. student at Nankai University; incoming Ph.D. at HKU (2027).
- **Location:** Tianjin, China
- **Email:** onexiangg.yu@gmail.com
- **GitHub:** [Vance-Yu](https://github.com/Vance-Yu)

## Running Locally

To preview changes before pushing to GitHub:

1. Install the dependencies.

   On Linux / Windows Subsystem for Linux:
   ```bash
   sudo apt install ruby-dev ruby-bundler nodejs
   ```

   On macOS:
   ```bash
   brew install ruby
   brew install node
   gem install bundler
   ```

1. Install the Ruby dependencies:
   ```bash
   bundle install
   ```
   If you hit a `Gem::FilePermissionError`, install the gems locally instead:
   ```bash
   bundle config set --local path 'vendor/bundle'
   bundle install
   ```

1. Serve the site and watch for changes:
   ```bash
   bundle exec jekyll serve -l -H localhost
   ```
   The site is then available at `http://localhost:4000`.

## Credits

This site is built on the [Academic Pages](https://academicpages.github.io/) template, which was forked (then detached) by [Stuart Geiger](https://github.com/staeiou) from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) and is currently maintained by [Robert Zupko](https://github.com/rjzupkoii).
