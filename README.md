# use.perl.org Static Archive

A static archive of use.perl.org, which was a Perl-specific blogging website created by Chris Nandor and hosted at Geeknet. It was up from early 2001 until late 2010. This is a project along the lines of Archive Team to save historical Perl websites and keep the content going. Using this repository you can host your own use.perl.org mirror.

Table of Contents
=================

   * [use.perl.org Static Archive](#useperlorg-static-archive)
      * [Searching](#searching)
      * [How This Was Built](#how-this-was-built)
      * [Contributions / Issues / Pull Requests](#contributions--issues--pull-requests)
      * [Author](#author)

## Searching

This is a git repo, hosted on github - either clone the repo and grep/ack/ag/whatever it, or use the search function of github

## How This Was Built

This was generated using [WWW::UsePerl::Server](https://metacpan.org/pod/release/LBROCARD/WWW-UsePerl-Server-0.36/lib/WWW/UsePerl/Server.pm) and some hacking of the code/data to make it work with recent version of Catalyst and be able to generate static content by using RESTful style URLs rather than query parameters.

More info to come ...

## TODO

* ~Fix those users with spaces in their names~
* Find source of mojibake (suspect it might actually be the data dump?)
* Substitute out all hardcoded references to use.perl.org/\* to point at the local domain (`egrep -R --color 'use.perl.org/[^"]' *`)

## Contributions / Issues / Pull Requests

Go ahead!

## Author

[Lee Johnson](https://github.com/leejo)
