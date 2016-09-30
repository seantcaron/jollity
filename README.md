Jollity IRC Client for Plan 9 v1.1
----------------------------------
Sean Caron scaron@umich.edu

INSTALLATION

mk
cp ./jollity /usr/you/bin/yourarch

USE

./jollity server nick [port]

If [port] is not specified the program will default to 6667.

NOTES

Jollity is a reasonably full featured and robust irc client for plan 9 that supports most of the original IRC standard (RFC 1459).

Though the client is robust, there isn't really much support for anything beyond the original RFC 1459 standard, such as DCC or most of CTCP with the singular exception that we do support sending responses to CTCP VERSION requests (vanity).

Jollity intentionally provides a similar user experience to ircII in dumb terminal mode on a UNIX system, with a few command tweaks to suit the preferences of the author.

TODO

1. Implement complete CTCP

2. Implement DCC