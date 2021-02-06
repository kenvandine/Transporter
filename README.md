# Transporter

[![Get it on AppCenter](https://appcenter.elementary.io/badge.svg)](https://appcenter.elementary.io/com.github.bleakgrey.transporter)

Simple [magic-wormhole](https://github.com/warner/magic-wormhole) client designed for elementary OS.

![Transporter Screenshot](https://raw.githubusercontent.com/cassidyjames/transporter/master/data/screenshot.png)

## Building and Installation

You'll need some dependencies to build:

* libgranite-dev
* meson
* valac

And you'll need these to actually run [magic-wormhole](https://github.com/warner/magic-wormhole):

* build-essential
* libffi-dev
* libssl-dev
* python3-pip
* python3-dev
* zip

Run these commands to configure the build environment:

    meson build --prefix=/usr
    cd build

Build and install:

    ninja
    ninja install
    
Run:

    com.github.bleakgrey.transporter

## Contributing

If you feel like contributing, you're always welcome to help the project in many ways:

* Reporting any issues
* Suggesting ideas and functionality
* Submitting pull requests

## Credits

* Original app and design by [@bleakgrey](https://github.com/bleakgrey)
* Magic Wormhole itself by [@warner](https://github.com/warner)
* Lithuanian translation by [@welaq](https://github.com/welaq)
* French and Italian translation by [@papou84](https://github.com/papou84)
* Brazilian Portuguese translation by [@btd1337](https://github.com/btd1337)
* German translation by [@p3732](https://github.com/p3732)
