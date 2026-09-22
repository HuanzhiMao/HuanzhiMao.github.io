This site uses [Minimal Mistakes 4.28.1](https://github.com/mmistakes/minimal-mistakes/releases/tag/4.28.1).
The theme's layouts, includes, Sass, JavaScript, and UI translations are vendored
in this repository. Keep them in sync with the version pinned in `Gemfile`.

Run `bundle install`, then `bundle exec jekyll serve` to preview the site.
Run `JEKYLL_ENV=production bundle exec jekyll build` to check the production build.

When upgrading the theme, preserve the customizations in `_layouts/home.html`
(no post listing) and `_includes/footer.html` (no social/feed links, copyright
uses the author's name), along with the site's configuration, navigation, and content.

The bundled JavaScript is ready to use. After editing JavaScript sources, run
`npm install` and `npm run build:js` to regenerate the bundle and source map.
