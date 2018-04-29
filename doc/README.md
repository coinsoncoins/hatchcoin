Hatchcoin Core
=============

Setup
---------------------
Hatchcoin Core is the original Hatchcoin client and it builds the backbone of the network. It downloads and, by default, stores the entire history of Hatchcoin transactions (which is currently more than 7 GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download Hatchcoin Core, visit [hatchcoin.org](https://hatchcoin.org).

Running
---------------------
The following are some helpful notes on how to run Hatchcoin on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/hatchcoin-qt` (GUI) or
- `bin/hatchcoind` (headless)

### Windows

Unpack the files into a directory, and then run hatchcoin-qt.exe.

### OS X

Drag Hatchcoin-Core to your applications folder, and then run Hatchcoin-Core.

### Need Help?

* See the documentation at the [Hatchcoin Wiki](https://hatchcoin.info/)
for help and more information.
* Ask for help on [#hatchcoin](http://webchat.freenode.net?channels=hatchcoin) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=hatchcoin).
* Ask for help on the [HatchcoinTalk](https://hatchcointalk.io/) forums.

Building
---------------------
The following are developer notes on how to build Hatchcoin on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Hatchcoin repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/hatchcoin/doxygen/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Travis CI](travis-ci.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [HatchcoinTalk](https://hatchcointalk.io/) forums.
* Discuss general Hatchcoin development on #hatchcoin-dev on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=hatchcoin-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
