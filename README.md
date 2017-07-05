Just a bunch of local Portfiles I use with MacPorts that I find useful. I'll
probably try to get these into the official MacPorts repo sometime, assuming
they'll have them.

To bootstrap this, see this page:
https://guide.macports.org/#development.local-repositories .

The TL;DR:

Run `portindex` in the checked out directory in order to create the `PortIndex`
and `PortIndex.quick` files, then add the path to the `sources.conf` file so
MacPorts knows where to find them.

The tools dir has `portfile-gen` and `cpan2port` which are handy for generating
new Portfiles.

