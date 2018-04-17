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

## Setting up on public host

    $ sudo hugo server --bind=0.0.0.0 --baseUrl=http://{{ DOMAIN }} --port=80
