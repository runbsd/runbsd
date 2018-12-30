<p><a href="/" alt="avatar" title="home page"><img src="reacharavindh.jpeg" class="avatar"></a></p>

# Aravindh Sampath runs OpenBSD

I was introduced to [FreeBSD] while working for [NetApp] as the
base that runs ONTAP (NetApp's storage OS).

In my current job, I administer a research cluster for a University.
When I got a chance to rebuild the cluster, I relied on [OpenBSD]
and FreeBSD for most of the infrastructure services.

I love using OpenBSD because it gives a minimal, secure, no bloat
system by default. As a bonus, I get excellent documentation,
sensible defaults, and constant audits by remarkable engineers who
not only add features they're interested in, but diligently remove
old/deprecated parts of code.  To hear Theo, and others talk about
[pledge(2)], [unveil(2)], and other features, only emphasises the
passion that goes into making this unique, rather opinionated
software project.

We use OpenBSD for our core DNS ([unbound(8)]), DHCP, SSH & SFTP,
firewall ([pf(4)]) and network gateway. If I'm building a public
facing server, I'll try very best to make it run OpenBSD.

FreeBSD gets my love for its tight integration with ZFS. I recently
build a [ZFS based file server](https://aravindh.net/post/zfs_fileserver/)
for less than half of what an enterprise NAS was going to cost us.

It made me even happier when I learnt that it was able to [munch
data faster than the network it was connected
to](https://aravindh.net/post/zfs_performance/). Now, having used
BSD for serious work stuff, I'm planning to use OpenBSD for my
desktop, and personal firewall on Raspberry Pi. More fun awaits.

Find me on [Twitter](https://twitter.com/reacharavindh).

_7 Aug 2018_

[FreeBSD]: https://www.freebsd.org
[NetApp]: https://www.netapp.com
[OpenBSD]: https://www.openbsd.org
[pf(4)]: https://man.openbsd.org/pf.4
[pledge(2)]: https://man.openbsd.org/pledge.2
[unbound(8)]: https://man.openbsd.org/unbound.8
[unveil(2)]: https://man.openbsd.org/unveil.2
