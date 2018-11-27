# sublime-gettext

[![Package Control](https://packagecontrol.herokuapp.com/downloads/Gettext.svg?style=flat-square)](https://packagecontrol.io/packages/Gettext)
[![GitHub tag](https://img.shields.io/github/tag/idleberg/sublime-gettext.svg?style=flat-square)](https://github.com/idleberg/sublime-gettext/tags)

Sublime Text support for Gettext

## Installation

### Package Control

1. Make sure you already have [Package Control](https://packagecontrol.io/) installed
2. Choose *“Install Package”* from the Command Palette (<kbd>Super</kbd>+<kbd>Shift</kbd>+<kbd>p</kbd>)
3. Type *“Gettext”* and press <kbd>Enter</kbd>

With [auto_upgrade](http://wbond.net/sublime_packages/package_control/settings/) enabled, Package Control will keep all installed packages up-to-date!

### Using Git

1. Change to your Sublime Text `Packages` directory
2. Clone repository `git clone https://github.com/idleberg/sublime-gettext.git 'Gettext'`

### Manual installation

1. Download the latest [ZIP file](https://github.com/idleberg/sublime-gettext/archive/master.zip)
2. Unzip the archive to your Sublime Text `Packages` directory

## Usage

### Snippets

- `ctx` => Plural message in a context
- `hdr` => Header
- `id` => Message ID
- `idp` => Message ID plural
- `msg` => Simple Message
- `msgc` => Simple message in a context
- `msgcp` => Plural message in a context
- `msgp` => Plural message
- `str` => Message string
- `strp` => Message string plural

## License

If not otherwise specified (see below), files in this repository fall under the following license:

	Permission to copy, use, modify, sell and distribute this
	software is granted. This software is provided "as is" without
	express or implied warranty, and with no claim as to its
	suitability for any purpose.

An exception is made for files in readable text which contain their own license information, or files where an accompanying file exists (in the same directory) with a “-license” suffix added to the base-name name of the original file, and an extension of txt, html, or similar. For example “tidy” is accompanied by “tidy-license.txt”.

## Credits

- Syntax, Preferences: [gettext.tmbundle](https://github.com/textmate/gettext.tmbundle)
- Snippets: [language-gettext](https://github.com/ArnaudRinquin/atom-language-gettext)
