<p><a href="/" alt="avatar" title="home page"><img src="filis.jpeg" class="w3"></a></p>

# FiLiS runs FreeBSD

I'm a sysadmin-by-accident since about 1998. I co-founded
[netzkommune.de] in 2000 and now we mostly specialize in managed
hosting and consulting.

I kinda stumbled into the whole Internet business pretty much after
high school, while working part time at a dotcom-startup in 1998.
Being the only person who "knew" Linux (I had installed some Linux
distro from floppy in ~1995 on my 486), I was tasked with all things
non-Windows, running stock qmail back when it was pretty new.

When starting _netzkommune_, we ran some Slackware and/or Red Hat
(I don't quite recall), hosted on an AMD K6 at Rackspace. When
talking to a friend about qmail and how complicated patching and
installing it, he showed me the [FreeBSD] ports system and how
installing qmail there was just cd `/usr/ports/mail/qmail && make
install`.  The next box I set up was FreeBSD 4.3 and I never looked
back. Today, all of our servers run FreeBSD, its main benefits for
us are ZFS, jails and poudriere. Being able to prepackage and test
things with our own/multiple configs, takes the edge off of most
of packaging tasks, knowing there are replicated snapshots of pretty
much everything as an addition to offsite backups for quick recovery
of a fatfingered file modification, is invaluable to us.

Not being a developer, I still feel I can grasp most of the OS's
processes and architecture, that simplicity a huge plus that most
people seem to have forgotten about.

Find me on [Twitter](https://twitter.com/FiLis)
and [Mastodon](https://mastodon.social/@FiLiS).

_[12 Aug 2018](/raw/people/filis.md)_

[FreeBSD]: https://www.freebsd.org/
[netzkommune.de]: https://www.netzkommune.de/
