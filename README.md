On December 12, 2017 [Storify] [announced] that they were going to shut down
completely on May 16, 2018. Users have until then to download their stories at
which point they will disappear from the web.

*storified* is a little utility for downloading your stories as HTML, XML and
JSON--which can be handy if you have a bunch of stories. The goal is to also 
add functionality for downloading referenced images, CSS and JavaScript which
will break when Storify goes offline.

## Install

1. Install [Python](https://python.org)
2. pip install storified

## Run

    % storified.py <account name>

This will create a directory with the same name as your account name, that
contains a sub-directory for each story, which in turn contains the HTML, JSON
and XML export files for the story.

