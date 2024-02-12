# Dope

A tag-based [Ghost](https://github.com/TryGhost/Ghost) theme based on [Dope](https://github.com/TryGhost/Dope/) but with up to six fixed featured tags in the carousel.

# Instructions

1. [Download this theme](https://github.com/slunsford/monday/archive/main.zip)
2. Log into Ghost, and go to the `Design` settings area to upload the zip file
3. **Enter tag *slugs* in the `Homepage` section of the `Design` settings.**

# Development

Styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need [Node](https://nodejs.org/), [Yarn](https://yarnpkg.com/) and [Gulp](https://gulpjs.com) installed globally. After that, from the theme's root directory:

```bash
# Install
yarn

# Run build & watch for changes
yarn dev
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.

The `zip` Gulp task packages the theme files into `dist/dope.zip`, which you can then upload to your site.

```bash
yarn zip
```

# Copyright & License

Copyright (c) 2013-2023 Ghost Foundation - Released under the [MIT license](LICENSE).
