<p><a href="/" title="home"><img src="/header.png" class="header__logo"></a></p>

# BSD

This line of operating systems started out life as a series of
patches to AT&T UNIX which was introduced to the University of
Berkeley by Ken Thompson whilst on sabbatical in 1977.  From the
1BSD TAPE file included in the [CSRG archive CD
set](http://www.mckusick.com/csrg/index.html):

	Berkeley UNIX Software Tape
	Jan 16, 1978 TP 800BPI

The first release came with things such as the ex editor, ashell
and Pascal compiler as an add-on for UNIX v7, running on a PDP-11.
Over the life time of the
[CSRG](https://en.wikipedia.org/wiki/Computer_Systems_Research_Group)
they produced releases which included vi, csh, the IPv4 TCP/IP
network stack, the virtual memory subsystem (the kernel being named
vmunix, parodied by Linux as vmlinuz) and UFS.

The distribution tapes were only available to AT&T licensees; over
time the code base of the distribution grew increasingly independent
from AT&T UNIX. At the same time the cost of the AT&T license
continued to increase as well.  Starting out at a cost of $10000
and reaching north of $250000 in the late 80's. According to Kirk
McKusick there was pressure to release the independently developed
components of the CSRG so the community could benefit from the use
of things such as the network stack without purchasing a costly
license. This resulted in several release, comprised mostly of the
code developed outside of AT&T such as 4.3BSD-Net/1, Net/2, 4.4BSD-Lite
& Lite2.  "Mostly" in that with the release of Net/2 [AT&T file a
lawsuit against the University of California for alleged code copying
and theft of trade
secrets](https://en.wikipedia.org/wiki/Berkeley_Software_Distribution#Net.2F2_and_legal_troubles).

During its lifetime, BSD saw itself being run on several CPU
architectures from the DEC PDP-11, VAX to the MIPS, HP 9000 and
Motorola 68000 to name a few.  These ports along with the [Power
6/32](https://en.wikipedia.org/wiki/Computer_Consoles_Inc.#Power_5_and_Power_6_computers)
helped to improve the portability of the code base. The code base
was deemed to be 90% platform independent, the remaining 10% being
mostly related to the VM subsystem which was platform specific. As
with AT&T UNIX, portability & migration between different systems
was part of the nature of the code base, from the beginning.

The 4.3BSD-Net/2 code base was used as the basis for a port to the
Intel 386, resulting in 386BSD (free) & BSD386 (commercial) releases.
