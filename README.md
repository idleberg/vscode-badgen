# Badgen

[![The MIT License](https://flat.badgen.net/badge/license/MIT/orange)](http://opensource.org/licenses/MIT)
[![GitHub](https://flat.badgen.net/github/release/idleberg/vscode-badgen)](https://github.com/idleberg/vscode-badgen/releases)
[![Visual Studio Marketplace](https://vsmarketplacebadge.apphb.com/installs-short/idleberg.badgen.svg?style=flat-square)](https://marketplace.visualstudio.com/items?itemName=idleberg.badgen)
[![CircleCI](https://flat.badgen.net/circleci/github/idleberg/vscode-badgen)](https://circleci.com/gh/idleberg/vscode-badgen)
[![David](https://flat.badgen.net/david/dev/idleberg/vscode-badgen)](https://david-dm.org/idleberg/vscode-badgen?type=dev)

Snippets to quickly insert [Badgen](http://badgen.net) badges Markdown documents — like those you can see above.

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

## Usage

Snippets follow the naming scheme of Badgen URL, e.g. `badgen-npm` is used for npm badges and `badgen-amo` for Mozilla Add-ons. Please refer to the [snippet guide](https://github.com/idleberg/vscode-badgen/blob/master/snippets.md) for a complete list.

### Enable Quick Suggestions

By default, Visual Studio Code has quick suggestions disabled for Markdown files. You can enable it in your settings as follows.

```json
"[markdown]": {
    "editor.quickSuggestions": true
}
```

Alternatively, press <kbd>Ctrl</kbd>+<kbd>Space</kbd> after typing the `badgen` prefix to show the list of suggestions.

## Related

- [Badgen for Atom](https://atom.io/packages/badgen)

## License

This work is licensed under [The MIT License](https://opensource.org/licenses/MIT)

## Donate

You are welcome support this project using [Flattr](https://flattr.com/submit/auto?user_id=idleberg&url=https://github.com/idleberg/vscode-badgen) or Bitcoin `17CXJuPsmhuTzFV2k4RKYwpEHVjskJktRd`
