#NationBuilder Foundation Theme

# [NationBuilder Foundation](http://foundation.ianpatrickhines.com)

According to [Zurb](http://zurb.com), [Foundation](http://foundation.zurb.com) is “the most advanced responsive front-end framework in the world.” You can quickly prototype and build custom themes that work on any kind of device with Foundation, which includes layout constructs (like a fully responsive grid), elements and best practices.

**NationBuilder Foundation** is a NationBuilder theme built on the Foundation framework in order to allow for rapid development of cutting edge, responsive NationBuilder themes.

To learn more about what’s included in Foundation, check out <http://foundation.zurb.com/docs>

To see a live demo of the theme, check out <http://foundation.ianpatrickhines.com>

## Copyright / License

The Foundation theme framework is Copyright (c) 2014 ZURB, inc. and subject to the [MIT License](https://github.com/zurb/foundation/blob/master/LICENSE).

This repository — the Foundation NationBuilder theme — is Copyright (c) 2014 Ian Patrick Hines and is also subject to the [MIT License](https://github.com/ianpatrickhines/nationbuilder-foundation/blob/master/LICENSE.markdown).

## How to use this theme

**Note:** *This theme is not designed to be used “as-is.” It has been left intentionally raw and unstyled, albeit functional.*

You’ll find that the overall structure of this theme has been relatively unchanged from NationBuilder’s Aware theme. All files are in a single directory (as required by NationBuilder).

[theme.scss](https://github.com/ianpatrickhines/nationbuilder-foundation/blob/master/theme.scss) includes Foundation’s Sass files, all of which are included in the theme and can be edited individually. I’ve compiled it and referenced it in the [layout.html](https://github.com/ianpatrickhines/nationbuilder-foundation/blob/master/layout.html) file as [style.min.css](https://github.com/ianpatrickhines/nationbuilder-foundation/blob/master/style.min.css).

[tablet-and-desktop.scss](https://github.com/ianpatrickhines/nationbuilder-foundation/blob/master/tablet-and-desktop.scss) includes a variety of styles designed to force Foundation’s styles on native NationBuilder HTML elements. NationBuilder’s liquid markup outputs some code snippets that cannot be modified to conform with Foundation’s syntax (pagination, for example), so additional styles were required to create aesthetic uniformity.

NationBuilder uses these two files as the core stylesheets for its themes. They do not need to be pre-compiled, and instead should be uploaded to the theme directly as .scss files. NationBuilder will compile them server-side and render the minified CSS.

To use this theme on your nation, download this repository to your local drive, create a new NationBuilder theme (do not clone your existing theme… create a new, blank theme), and upload every file in the directory to that theme. Publish the theme, and you're in business.