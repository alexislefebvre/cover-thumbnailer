# Cover Thumbnailer

> This repository is the continuation of the [Bazaar / Launchpad][lp] one. This
> is legacy code that have not been maintained for years, so it may not work
> out of the box and fixes can take time to be released.

Cover thumbnailer is a small Python script which displays music album covers
in Nautilus, preview of pictures which are in a folder and more.

The script fits in Nautilus like any other thumbnailer of the GNOME
thumbnail factory; so you don't have to run it manually to generate
thumbnails.

Cover Thumbnailer is free software distributed under the GNU GPL v3+ license,
you are free to modify and redistribute it under the terms of the license.


[lp]: https://launchpad.net/cover-thumbnailer


## Requirements

Cover Thumbailer dependencies:

* PIL / pillow (on Ubuntu: `sudo apt install python-pil`)
* PyGI

Cover Thumbnailer GUI dependencies:

* PyGTK 2 (on Ubuntu: `sudo apt install python-gtk2`; this package is not available on Ubuntu 20.04, you'll need to use this PPA to install it: `sudo add-apt-repository ppa:nrbrtx/python2-stuff`)

Development / Build dependencies:

* GNU gettext


## Installing Cover Thumbnailer

Clone this repository:

    git clone https://github.com/flozz/cover-thumbnailer.git
    # or through SSH:
    git clone git@github.com:flozz/cover-thumbnailer.git

Move to directory:

    cd cover-thumbnailer/

To install Cover thumbnailer, run the following command as root:

    ./install.sh --install


## Uninstalling Cover Thumbnailer

To uninstall Cover thumbnailer, run the following command as root:

    /usr/share/cover-thumbnailer/uninstall.sh --remove


## Configuring Cover Thumbnailer

Cover Thumbnailer provides a GUI tool to configure it. Just run the following
command to start the tool:

    cover-thumbnailer-gui

