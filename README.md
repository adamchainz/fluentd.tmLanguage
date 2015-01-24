Syntax highlighting for Fluentd
===============================

Got some [fluentd](http://www.fluentd.org/) configuration files you wish were easier on the eyes? Look no further!

## Screenshot

![Screenshot](/screenshot.png?raw=true)

## Installation

### Package Manager

First, install the Package Control plugin, instructions here: http://wbond.net/sublime_packages/package_control.

Once you install Package Control, restart Sublime Text and bring up the Command Palette (`Command+Shift+P` on OS X, `Control+Shift+P` on Linux/Windows).

Select "Package Control: Install Package", wait while Package Control fetches the latest package list, then select "Ansible" when the list appears.

The advantage of using this method is that Package Control will automatically keep this package up to date with the latest version.

### Manual

Clone the repository in your Sublime Text "Packages" directory:

    git clone https://github.com/adamchainz/sublime-fluentd.git Fluentd

The "Packages" directory is located at:

* OS X:
    `~/Library/Application Support/Sublime Text 3/Packages/`
* Linux:
    `~/.Sublime Text 3/Packages/`
* Windows:
    `%APPDATA%/Sublime Text 3/Packages/`
