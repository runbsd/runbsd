<p><a href="/" alt="avatar" title="home page"><img src="flipchan.jpeg" class="w3"></a></p>

# Flipchan runs BSD

I had been glancing at [OpenBSD] and had it running in several VMs
for a while when I had systemd destroy a production build by deleting
what it thought was junk files but in reality was production
configuration files. 

After a lot of cursing I knew it was time to take the red pill of
BSD and I have now turned to OpenBSD for all my VMs and servers.

My company that I work for (Firo Solutions) is more then happy to
have the entire infrastructure running puffy!  

OpenBSD comes with everything you need to build it! relayd(8),
smtpd(8), and so on, and rcctl(8) is exactly what an init/daemon
handler shall be. The user handling in OpenBSD is much better than
in Debian. OpenBSD makes me sleep at night knowing and our production
build is not going to be destroyed by some unexpected slip up made
by an operating system.  OpenBSD is secure by default.

I'm [@flipchan@bsd.network](https://bsd.network/@flipchan) on
Mastodon and [@filipsweet](https://twitter.com/filipsweet) on
Twitter.

_[23 Jan 2019](/raw/people/flipchan.md)_

[OpenBSD]: https://www.openbsd.org/
