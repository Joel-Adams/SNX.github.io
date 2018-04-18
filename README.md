# RedHatGov.io

[![Build Status](https://travis-ci.org/RedHatGov/redhatgov.github.io.svg?branch=docs)](https://travis-ci.org/RedHatGov/redhatgov.github.io)


----

[RedHatGov.io][redhatgov] is an open source collection of workshop materials that
cover various topics relating to Red Hat's product portfolio.

----

## To start developing

If you want to build RedHatGov.io right away:

##### You have a working [Hugo environment][hugo]. (Including Pygments)

    $ git clone https://github.com/Joel-Adams/SNX.github.io.git
    $ cd SNX.github.io
    $ hugo server

### Install AsciiDoc
Install using yum or dnf on Fedora

To install Asciidoctor on Fedora (or RHEL via EPEL) using the rubygem-asciidoctor package:

    Open a terminal
    Run the installation command on Fedora:
    $ sudo dnf install asciidoctor

The benefit of installing the gem using this method is that the package manager will also install Ruby and RubyGems if not already on your machine.
Install using apt-get on Debian or Ubuntu

To install Asciidoctor on Debian or Ubuntu:

    Open a terminal
    Type the following apt-get command using sudo:
    $ sudo apt-get install asciidoctor

The benefit of installing the gem via apt-get is that the package manager will also install Ruby and RubyGems if not already on your machine.
Install using apk on Alpine Linux

To install Asciidoctor on Alpine Linux using the asciidoctor package:

    Open a terminal
    Type the following apk command using sudo:
    $ sudo apk add asciidoctor

The benefit of installing the gem via apk is that the package manager will also install Ruby and RubyGems if not already on your machine.


## Setting up on public host

    $ sudo hugo server --bind=0.0.0.0 --baseUrl=http://{{ URL }} --port=80
