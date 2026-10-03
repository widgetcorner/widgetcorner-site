# Widget Corner

Public website for Widget Corner LLC, served by GitHub Pages from `docs/` at
[widgetcorner.com](https://widgetcorner.com).

A static HTML/CSS site with no build step, external fonts, or JavaScript dependency.
The `/pocapp/` download shortcut uses a small script to select the appropriate store;
its download links also work without JavaScript.

## Local preview

```sh
python3 -m http.server 4173 --bind 127.0.0.1 --directory docs
```

Open [localhost:4173](http://localhost:4173).

## Files

- `docs/index.html`: studio homepage and featured apps.
- `docs/assets/site.css`: shared layout, colors, responsive rules, and dark appearance.
- `docs/assets/`: studio mark, app artwork, screenshots, and local store badges.
- `docs/<app>/index.html`: product pages, including apps in development.
- `docs/<app>/support/` and `docs/<app>/privacy/`: help and policy documents.
- `docs/support/`: studio support hub.
- `docs/pocapp/`: Play On Con store shortcut and download fallback.

Keep all published paths and support anchors stable when updating content.
App-specific palettes are defined by the `theme-*` classes in the shared stylesheet.
