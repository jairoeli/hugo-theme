# Hugo Theme

This is the custom [Hugo](https://gohugo.io) theme powering my personal site, [jairoeli.github.io](https://jairoeli.github.io).

## Customization

There are a few points of customization included in this theme:

- The header menu is driven by building a `[[menu.main]]` menu
- The footer menu is driven by building a `[[menu.footer]]` menu
- Content at `layouts/partials/home.html` will be injected into the homepage, above the "Recent Posts" section

## Developing

To develop the theme, there is only really one thing to note - all Sass code is in `sass/` and must be compiled with `make`.

## License

See `LICENSE.md` for usage.
