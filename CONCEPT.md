torrone - P2P through Tor hidden services
=========================================
torrone aims to *standardize* and implement a base protocol and various
extensions for P2P usage through Tor hidden services.

The result will be an anonymous and secure P2P network with various
capabilities.

The main area we want to target is instant messanging and other kinds of text
based goods, like a twitter-like status updating extension, a message
broadcasting extension and a search extension.

File sharing will also be possible, but considering the additional overhead and
slowness of hidden services that won't really be good.

Small footprint voice chat with [opus](http://www.opus-codec.org/) will also be
investigated.

Target audience and usage
-------------------------
The idea is to let small communities have a secure and anonymous way to talk
and transfer files with eachother without the need for a server with configured
IRC or XMPP.

It could also be interesting to have a status updating decentralized shim with
an outfacing website for that kind of thing. Decentralized and anonymous
microblogging.

Maybe even a small decentralized forum made of the small known entities of the
community.

**There is no intention to make it a *global* P2P network.**

Protocol design and choices
---------------------------
For the protocol [protobuf](https://developers.google.com/protocol-buffers/)
will be used.

The reason is it's awesome, compact and the protocol definitions are specs
themselves.

How will this affect Tor?
-------------------------
Given the current (28/09/2012) state, if this breaks through and people start
using it (in the hundreds of thousands), the network will die.

We hope that with torrone we will push Tor to make hidden services scale thus
making the network better for everyone and provide what torrone aims to provide
to everyone who may need it.

This choice comes because if we don't do this, someone else will do it anyway
without even caring about the repercussions.
