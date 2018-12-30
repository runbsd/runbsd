<p><a href="/" alt="avatar" title="home page"><img src="sethhanford.jpeg" class="avatar"></a></p>

# Seth Hanford runs OpenBSD 

I started my career as a Windows sysadmin in 2001; coincidentally,
I found myself searching the Internet for "most secure operating
system" shortly thereafter. Lots of options appeared, but after
investigating a few, I became enamored with the [OpenBSD] community.
By the end of 2001, I was also dealing with significant spam issues
in my personal email and for some business clients, and began
exploring OpenBSD as a safe front-end for personal and business
use. At the time, this would've been Postfix, Amavisd-new, SpamAssassin,
ClamAV to protect Exchange 5.5 backends. Work insisted that it was
a Windows-only shop and "_Linux_ isn't for us", so I was limited
to using OpenBSD for personal projects instead.

A few years and a job change later, I had transitioned from system
administration to Information Security. I've worked in vulnerability
intelligence, product security, threat intelligence, and security
operations, blue team roles since then. OpenBSD had embedded itself
in my personal life, but work continued to require some form of
commercial OS for key daily tasks. I was fortunate to move to OS X
for a BSD-based daily driver professionally macOS X 10.3, and 2004
setup OpenBSD with [Xfce] as a family computer for a short time.
Still, my use of OpenBSD was primarily restricted to the excellent
[pf(4)] firewall, and powering personal web and email systems. Over the
years I've enjoyed using SparcStation 5 & 20, Ubiquiti EdgeRouters,
old PowerPC systems, and other non-x86 systems particularly.

Recently, I've been dreading making the jump to the latest generation
of Apple hardware. Things like "no physical Escape key" make hardcore
[vi(1)] users like myself get fairly uncomfortable. But Windows 10
and systemd have the other alternatives not looking much better.
As of OpenBSD 6.3, I'm making a concerted effort to transition my
important work tasks to OpenBSD-only. Except for one fairly important
collaboration tool, everything that I need to do can be done in
OpenBSD today. With [pledge(2)] and [unveil(2)], and the fantastic
work in [vmm(4)]/[vmd(8)], [syspatch(8)], and fixing various microcode
flaws, I feel like there's never been a better time to move. 

I'm [@SethHanford] on Twitter.

_[10 Aug 2018](/raw/people/sethhanford.md)_

[OpenBSD]: https://www.openbsd.org
[@SethHanford]: https://twitter.com/sethhanford
[Xfce]: https://xfce.org
[pf(4)]: https://man.openbsd.org/pf.4
[pledge(2)]: https://man.openbsd.org/pledge.2
[syspatch(8)]: https://man.openbsd.org/syspatch.8
[unveil(2)]: https://man.openbsd.org/unveil.2
[vi(1)]: https://man.openbsd.org/vi.1
[vmd(8)]: https://man.openbsd.org/vmd.8
[vmm(4)]: https://man.openbsd.org/vmm.4
