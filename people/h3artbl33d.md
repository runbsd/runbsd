<p><a href="/" alt="avatar" title="home page"><img src="h3artbl33d.jpeg" class="avatar"></a></p>

# h3artbl33d runs OpenBSD

I am h3artbl33d, a 30-ish Dutchie. Day-to-day I am an entrepreneur
and sysop. I manage a lot of systems and networks, for my own company
and clients. Luckily, [I switched to OpenBSD in my
youth](https://h3artbl33d.nl/tech/obsd-love.html).  Out of necessity,
I manage a bunch of Linux boxes, but mostly OpenBSD boxes.

[OpenBSD](https://www.openbsd.org) is my favorite OS due to their
rigorous attitude towards security, neat documentation and proper
coding skills. For me, security is the leading advantage, as I don't
do compromises&mdash;even if it benefits performance, user experience,
etc. As soon as viable, I am switching every hypervisor to
[vmm(4)][vmm]/[vmd(8)][vmd].

> By the way, [Mike Larkin](https://twitter.com/mlarkin2012)
has been making awesome improvements&mdash;soon we can enjoy more
advanced virtualization techniques on OpenBSD&mdash;like resource
limits.

At work, OpenBSD handles the network infrastructure (routing,
firewalling, mail, etc) and safeguarding of sensitive data. New
machines are rolled out with [Ansible][a] and [autoinstall(8)][ai],
monitoring with [zabbix][z], backups with [tarsnap][t].

At home, I have a completely segmented network&mdash;mainly split
into two parts, home and work. On both segments, bad guys are kept
at a safe distance ([pf(4)][pf], [suricata][s], [rbl][r]), privacy
is enforced (known trackers and invasion is blocked on the firewall
and DNS level with pf(4) and [unbound(8)][u]). In the home segment,
I keep no logs to respect the privacy of my partner and our guests,
most traffic is allowed (unless specifically blocked), whereas the
work segment is on a whitelist basis (both port and IP).

And best of all? It is rock solid. Sure, configuring this takes
some time and effort, but it keeps running like nothing else. I
only check the logs every day and run [syspatch(8)][syspatch] and
[openup][ou]&mdash;no crashes or showstopping bugs.

Find me on [Twitter](https://twitter.com/h3artbl33d),
[Mastodon](https://bsd.network/@h3artbl33d), and [my personal
site](https://h3artbl33d.nl).

_6 Aug 2018_

[syspatch]: https://man.openbsd.org/syspatch.8
[vmm]: https://man.openbsd.org/vmm.4
[vmd]: https://man.openbsd.org/vmd.8
[u]: https://man.openbsd.org/unbound.8
[pf]: https://man.openbsd.org/pf.4
[ai]: https://man.openbsd.org/autoinstall.8
[ou]: https://www.mtier.org/solutions/apps/openup/
[a]: https://www.ansible.com/
[s]: https://suricata-ids.org/
[r]: https://github.com/mordak/divert_rbl
[z]: https://www.zabbix.com/
[t]: https://www.tarsnap.com/
