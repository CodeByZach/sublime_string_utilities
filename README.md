StringUtilities
===============
[![Latest Release](https://img.shields.io/github/tag/CodeByZach/sublime_string_utilities.svg?label=version)](https://github.com/CodeByZach/sublime_string_utilities/releases)

StringUtilities is a Sublime Text 3 plugin, which adds to the editor useful string functions like:

* Expand Selection to Whole String
* Convert Tabs to Spaces
* Convert Spaces to Tabs
* Convert Spaces to `&nbsp;` (Non-breaking space)
* Convert Chars to HTML Entities
* Convert HTML Entities to Chars
* Convert Underscores <-> Dashes
* Convert camelCase <-> Underscores
* Convert camelCase <-> Dashes
* Convert PascalCase <-> Underscores
* Convert PascalCase <-> Dashes
* Convert Single Quotes To Double
* Convert Double Quotes To Single
* Encode as URL Notation
* Decode from URL Notation
* Convert To Unicode Notation
* Convert From Unicode Notation
* Convert To Base64
* Convert From Base64
* Convert To Hex
* Convert From Hex
* Convert HTML Color Hex To RGB
* Convert HTML Color RGB To Hex
* Calculate MD5
* Calculate SHA1
* Calculate SHA224
* Calculate SHA256
* Calculate SHA384
* Calculate SHA512
* Convert Unixtime <-> Datetime
* Insert Current Datetime
* Insert Password (6 to 64 char, optionally with spec symbols)
* Decode HeidiSQL password
* Insert Internal IP
* Insert External IP
* Prettify JSON String
* Convert PHP Object to Array


Installation
------------------

 * Install [Package Manager](https://packagecontrol.io).
 * Use <kbd>Cmd</kbd>/<kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> then `Package Control: Install Package`.
 * Look for `StringUtilities` and install it.

If you prefer to install manually, install git, then:

Clone the repository in a subfolder "StringUtilities" in your Sublime Text "Packages" directory:

    git clone https://github.com/CodeByZach/sublime_string_utilities "<Sublime Text 3 Packages folder>/StringUtilities"


The "Packages" directory is located at:

* Linux: `~/.config/sublime-text-2/Packages/`
* OS X: `~/Library/Application Support/Sublime Text 2/Packages/`
* Windows: `%APPDATA%/Sublime Text 2/Packages/`

Or enter
```python
sublime.packages_path()
```
into the console (<kbd>Ctrl</kbd>+<kbd>`</kbd>).

Compatibility
------------------

StringUtilities runs on both Sublime Text plugin hosts:

* Python 3.3: Sublime Text 3, and Sublime Text 4 before build 4213
* Python 3.14: Sublime Text 4 build 4213 and later

Changes must keep working on both. Avoid language features and standard library additions newer than Python 3.3 (for example f-strings, `secrets` or `html.unescape`), or provide a fallback.

Usage
------------------

* Right click on editor window (first select text if function is convert type) and select StringUtilities menu item.

Todo
------------------

 * Add some missed functions
