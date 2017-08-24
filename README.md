VoteCoin 1.0.11
===============

What is VoteCoin?
-----------------

[VoteCoin](https://votecoin.site/) is an implementation of the "Zerocash" protocol.
Forked from ZCash, based on Bitcoin's code, it intends to offer a far higher standard of privacy
through a sophisticated zero-knowledge proving scheme that preserves
confidentiality of transaction metadata. Technical details are available
in our [Protocol Specification](https://github.com/zcash/zips/raw/master/protocol/protocol.pdf).

This software is the VoteCoin client. It downloads and stores the entire history
of VoteCoin transactions; depending on the speed of your computer and network
connection, the synchronization process could take a day or more once the
blockchain has reached a significant size.

Security Warnings
-----------------

**VoteCoin is experimental and a work-in-progress.** Use at your own risk.

Building
--------

Build VoteCoin along with most dependencies from source by running
cd ./zcutil
./votecoin_build.sh.

License
-------

For license information see the file [COPYING](COPYING).
