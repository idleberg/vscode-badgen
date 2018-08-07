# Badgen

[![The MIT License](https://flat.badgen.net/badge/license/MIT/orange)](http://opensource.org/licenses/MIT)
[![GitHub](https://flat.badgen.net/github/release/idleberg/vscode-badgen)](https://github.com/idleberg/vscode-badgen/releases)
[![Visual Studio Marketplace](https://vsmarketplacebadge.apphb.com/installs-short/idleberg.badgen.svg?style=flat-square)](https://marketplace.visualstudio.com/items?itemName=idleberg.badgen)
[![CircleCI](https://flat.badgen.net/circleci/github/idleberg/vscode-badgen)](https://circleci.com/gh/idleberg/vscode-badgen)
[![David](https://flat.badgen.net/david/dev/idleberg/vscode-badgen)](https://david-dm.org/idleberg/vscode-badgen?type=dev)

Snippets to quickly insert [Badgen](http://badgen.net) badgen Markdown documents — like those you can see above.

This package is also available for [Atom](https://github.com/idleberg/atom-badgen)

## Installation

### Extension Marketplace

Launch Quick Open, paste the following command, and press <kbd>Enter</kbd>

`ext install badgen`

### Packaged Extension

Download the package extension from the the [release page](https://github.com/idleberg/vscode-badgen/releases) and install it from the command-line:

```bash
$ code --install-extension badgen-*.vsix
```

### Clone Repository

Change to your Visual Studio Code extensions directory:

```bash
# Windows
$ cd %USERPROFILE%\.vscode\extensions

# Linux & macOS
$ cd ~/.vscode/extensions/
```

Clone repository as `badgen`:

```bash
$ git clone https://github.com/idleberg/vscode-badgen badgen
```

### Usage

**Note:** By default, the quick suggestions are disabled for Markdown files. You can enable them by setting `editor.quickSuggestions` to `true`.

All snippets start with the prefix `svg-` and is followed by the service you're adressing, with some services offering multiple choices.

Examples:

* `svg-pypi-dl-day` - daily downloads on PyPI
* `svg-pypi-dl-month` - monthly downloads on PyPI
* `svg-travis` - build status on Travis
* `svg-travis-branch` - build status on Travis for a specific branch
* `svg-npm-ver` - the version of a Node package
* `svg-gpl3` - link to GNU General Public License, Version 3

Please refer to the [snippet guide](https://github.com/idleberg/vscode-badgen/blob/master/snippets.md) for a complete list.

## License

This work is licensed under [The MIT License](https://opensource.org/licenses/MIT)

## Donate

You are welcome support this project using [Flattr](https://flattr.com/submit/auto?user_id=idleberg&url=https://github.com/idleberg/vscode-badgen) or Bitcoin `17CXJuPsmhuTzFV2k4RKYwpEHVjskJktRd`

[ai]: http://www.androidicons.com
[brandico]: https://github.com/fontello/brandico.font
[cc]: https://github.com/cc-icons/cc-icons
[dashicons]: https://github.com/WordPress/dashicons
[devicons]: https://github.com/vorillaz/devicons
[ei]: https://github.com/outpunk/evil-icons
[el]: https://github.com/reduxframework/Elusive-Icons
[fa]: https://github.com/FortAwesome/Font-Awesome
[fi]: http://zurb.com/playground/foundation-icons
[fl]: https://github.com/Lukas-W/font-linux
[geomicon]: https://github.com/jxnblk/geomicons-open
[glyphicon]: https://getbootstrap.com/components/#glyphicons
[icono]: https://github.com/saeedalipoor/icono
[ion]: https://github.com/driftyco/ionicons
[line]: http://www.elegantthemes.com/blog/resources/how-to-use-and-embed-an-icon-font-on-your-website
[mdi]: https://github.com/Templarian/MaterialDesign-Webfont
[mfg]: https://github.com/MfgLabs/mfglabs-iconset
[mfizz]: https://github.com/fizzed/font-mfizz
[octicon]: https://github.com/github/octicons
[oi]: https://github.com/iconic/open-iconic
[openwebicons]: https://github.com/pfefferle/openwebicons
[pf]: https://github.com/vendocrat/PaymentFont
[ratchicon]: http://goratchet.com/components/#ratchicons
[st]: https://github.com/parkerbennett/stackicons
[typcn]: https://github.com/stephenhutchings/typicons.font
[ui]: http://semantic-ui.com/elements/icon.html
[wi]: https://github.com/erikflowers/weather-icons
[zmdi]: https://github.com/zavoloklom/material-design-iconic-font
