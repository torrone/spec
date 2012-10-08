torrone - anonymous, decentralized and resilient communities
============================================================
torrone aims to make it easy for people to create decentralized, anonymous and
resilient communities with *just* Tor, torrone and a browser.

It will provide a forum, instant messanging, file sharing, microblogging, voice
chat and other kind of goodies.

Everything will be **crumb** centric, a crumb is basically a circle with a
certain UUID, if you know the UUID and aren't banned by consensus, you can
interact with the other parties being part of that crumb.

There will also be the chance to put stuff under no crumb at all, which will
make it publically accessible, this will be used to support web accessible
microblogging and the like.

Multiple identities (onion IDs and profiles) will be usable, but discouraged.

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

**To be clear, the plan is to help in fixing the issues.**
