<p><a href="/" alt="avatar" title="home page"><img src="mischapeters.jpeg" class="w3"></a></p>

# Mischa Peters runs BSD

I am Mischa Peters. I am running a hosting and co-locating company
out of Amsterdam as a out-of-hand hobby and my $dayjob is leading
a team of Systems Engineers for a security startup. I recently
kicked off [OpenBSD Amsterdam].

I started in the wonderful world of Unix (SunOS) while in university
and I wanted to run something at home that had the same feel to it.

I bumped into Linux, Slackware and later RedHat, and I even was a
beta tester for RedHat 5.2 on SPARC at one point. After that I saw
the light and moved to FreeBSD 2.x, been running BSD ever since.
Also used OpenBSD and DragonflyBSD a couple of times in those days.
Around 5 years, or so, ago I added OpenBSD to the mix again, full
time.

What is my favorite BSD? I actually have two favorites, [OpenBSD]
and [FreeBSD]. With OpenBSD everything just makes sense for me. The
defaults are sane, hardly anything to install to have a desktop,
server or router running.  My intial draw to OpenBSD was networking.
It just works and is easy to configure: [pf(4)], [vlan(4)], [vxlan(4)],
[carp(4)], [trunk(4)], [OpenBGPd], [pppoe(4)], and the list goes
on.

Other things I am a big fan of are: [relayd(8)], [httpd(8)],
[OpenSMTPd], [spamd(8)], [OpenSSH], of course, and more recently
[vmd(8)]/[vmm(4)].

With FreeBSD I really enjoy [jail(8)], [zfs(8)], [bhyve(8)], [pkg(8)]
together with pourdriere.

When I started with BSD all my servers where FreeBSD with jails.
Today I have a mix of OpenBSD and FreeBSD running on my servers.
FreeBSD is running on a couple of dedicated jails machine for
customers, couple of ZFS machines for storage and streaming. OpenBSD
is running on a couple of dedicated relayd machines, couple of
routers in different locations (home, $dayjob, DC), dedicated DNS
servers with [unbound(8)]/[nsd(8)], couple of machines
running dedicated vmd(8)/vmm(4) for OpenBSD Amsterdam. And things
like OpenSMTPd, spamd(8), [OpenVPN], [cgit], web hosting
on httpd(8) (sometimes in combination with relayd(8)). Lastly using
OpenBSD on my laptop ([ThinkPad X270]) with [cwm(1)].

For my own company and at home that is easy. I am using OpenBSD on
my desktop, servers and routers and FreeBSD on servers and storage.
As much as possible out of base, I adjust my workflow if I can
replace a tool with something out of base.

Find me on [Twitter](https://twitter.com/mischapeters) and
[Mastodon](https://bsd.network/@mischa).

_7 Aug 2018_

[OpenBGPd]: https://man.openbsd.org/bgpd.8
[bhyve(8)]: https://www.freebsd.org/cgi/man.cgi?bhyve
[carp(4)]: https://man.openbsd.org/carp.4
[cgit]: https://git.zx2c4.com/cgit/about/ 
[cwm(1)]: https://man.openbsd.org/cwm.1
[FreeBSD]: https://www.freebsd.org
[httpd(8)]: https://man.openbsd.org/httpd.8
[jail(8)]: https://www.freebsd.org/cgi/man.cgi?jail
[nsd(8)]: https://man.openbsd.org/nsd.8
[OpenBSD]: https://www.openbsd.org
[OpenBSD Amsterdam]: https://openbsd.amsterdam
[OpenVPN]: https://openvpn.net/
[pf(4)]: https://man.openbsd.org/pf.4
[pkg(8)]: https://www.freebsd.org/cgi/man.cgi?pkg
[pppoe(4)]: https://man.openbsd.org/pppoe.4
[relayd(8)]: https://man.openbsd.org/relayd.8
[OpenSMTPd]: https://man.openbsd.org/smtpd.8
[spamd(8)]: https://man.openbsd.org/spamd.8
[OpenSSH]: https://man.openbsd.org/sshd.8
[trunk(4)]: https://man.openbsd.org/trunk.4
[unbound(8)]: https://man.openbsd.org/unbound.8
[vlan(4)]: https://man.openbsd.org/vlan.4
[vmd(8)]: https://man.openbsd.org/vmd.8
[vmm(4)]: https://man.openbsd.org/vmm.4
[vxlan(4)]: https://man.openbsd.org/vxlan.4
[ThinkPad X270]: https://www.lenovo.com/us/en/laptops/thinkpad/thinkpad-x/ThinkPad-X270/p/22TP2TX2700
[zfs(8)]: https://www.freebsd.org/cgi/man.cgi?zfs
