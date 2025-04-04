Projectxcl Core
=============

Setup
---------------------
Projectxcl Core is the original Projectxcl client and it builds the backbone of the network. It downloads and, by default, stores the entire history of Projectxcl transactions, which requires approximately 22 gigabytes of disk space. Depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download Projectxcl Core, visit [projectxcl.org](https://projectxcl.org/).

Running
---------------------
The following are some helpful notes on how to run Projectxcl Core on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/projectxcl-qt` (GUI) or
- `bin/projectxcld` (headless)

### Windows

Unpack the files into a directory, and then run projectxcl-qt.exe.

### macOS

Drag Projectxcl Core to your applications folder, and then run Projectxcl Core.

### Need Help?

* See the documentation at the [Projectxcl Wiki](https://projectxcl.info/) for help and more information.
* Ask for help on [#projectxcl](https://webchat.freenode.net/#projectxcl) on Freenode. If you don't have an IRC client, use [webchat here](https://webchat.freenode.net/#projectxcl).
* Ask for help on the [ProjectxclTalk](https://projectxcltalk.io/) forums, in the [Technical Support board](https://projectxcltalk.io/c/technical-support).

Building
---------------------
The following are developer notes on how to build Projectxcl Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [macOS Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [FreeBSD Build Notes](build-freebsd.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [NetBSD Build Notes](build-netbsd.md)
- [Gitian Building Guide (External Link)](https://github.com/bitcoin-core/docs/blob/master/gitian-building.md)

Development
---------------------
The Projectxcl repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Productivity Notes](productivity.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://doxygen.bitcoincore.org/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [JSON-RPC Interface](JSON-RPC-interface.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [ProjectxclTalk](https://projectxcltalk.io/) forums.
* Discuss general Projectxcl development on #projectxcl-dev on Freenode. If you don't have an IRC client, use [webchat here](https://webchat.freenode.net/#projectxcl-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [bitcoin.conf Configuration File](bitcoin-conf.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Memory](reduce-memory.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)
- [PSBT support](psbt.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
