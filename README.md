NAME
====
`imap-am` - Interactively apply git patches straight from an IMAP server.

SYNOPSIS
========
`imap-am [options] server [folder]`
Interactively apply git patches straight from an IMAP server.

ARGUMENTS
=========
* `server`       IMAP server
* `folder`       IMAP folder to search

OPTIONS
=======
* `-h, --help`   show this help message and exit
* `--user USER`  IMAP user name (default: $USER)
* `--tls`        Use a secure connection (SSL)
* `--port PORT`  Port to connect to (default: 143 or 993)

INSTALLATION
============

Unix/Linux:

    sudo python setup.py install


Unix/Linux (single user):

    python setup.py install --user --install-scripts ~/bin


Other:

    python setup.py install

