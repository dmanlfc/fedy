# Fedy

Fedy lets you install multimedia codecs and additional software that Fedora
[doesn't want to ship][forbidden-items], like mp3 support, Adobe Flash, Oracle
Java etc., and much more with just a few clicks.

## Installation

Installation instructions can be found on https://www.folkswithhats.org.

_Do not follow instructions from any other source!_

## Usage

After installation, search for `Fedy` in the menu/overview or type `fedy` in
the terminal.

### Custom plugins

Plugins are loaded from the following locations:

* `~/.locale/share/fedy/plugins`
* `/usr/share/fedy/plugins`

## Contributing

We welcome all contributions. There are a few ways to get involved:

* [Create issues][gh-fedy-issues] for bugs or feature requests
* Create [pull requests][gh-fedy-pulls] with your awesome patches
* Donate for infrastructure costs and project development

For more information, see [CONTRIBUTING.md](CONTRIBUTING.md).

## Licenses

This repository contains several projects. Look for the `LICENSE` file in each
project's directory. A quick reference can be seen below:

* **Fedy** (`src/gui`): GNU GPL v3
* **The source for folkswithhats.org** (`src/www`): MIT

[forbidden-items]: http://fedoraproject.org/wiki/Forbidden_items?rd=ForbiddenItems
[gh-fedy]: https://github.com/folkswithhats/fedy
[gh-fedy-issues]: https://github.com/folkswithhats/fedy/issues
