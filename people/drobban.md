<p><a href="/" alt="avatar" title="home page"><img src="drobban.jpeg" class="w3"></a></p>

# David Bern runs OpenBSD

You know me as ([@_drobban]) on Twitter or drobban on IRC.  I work
as a developer in a Linux environment.  In my spare time, I like
to fiddle with my UAV / Drones and Software Defined Radio

Been a long time user of Linux and Mac OS X at home, but recently
got my eyes open for [OpenBSD]. I have followed the OpenBSD project
since the Heartbleed bug, I noticed an increase of OpenBSD
recommendations when the Specter/Meltdown bug was discovered which
led me to test OpenBSD. To further increase my feeling of making
the correct decision came after watching [this talk] with Theo.

It was love at first sight and I have not encountered a single
problem since my first installation (okey, one problem, I tried to
install OpenBSD with the wrong image for my CPU).

My goal with OpenBSD is to use it with my hobby-projects, so for
the UAV I started pushing patches upstream to the Ground Control
Software &mdash; APM Planner 2, there is now a working version
available for OpenBSD 6.2.

I also started writing software that is aimed to be used primarily
on OpenBSD, a kernel driver for a AC51-card from Opto22 and software
for giving joystick inputs to a drone via TCP/IP.

What I have discovered while working on my projects, is that the
documentation is awesome and that the source code is clean and well
thought out in the OpenBSD project.  It is also simple to write/test
new fixes when something is broken in base and all you have to do
when the fix is done is to send an email to the maintainer

To break it down into why I use OpenBSD:

- The awesome documentation.
- The source is simple/clean, so it's easy to understand most parts
  of the system.
- It seems like the primary objective for the OpenBSD project is
  to keep its users safe and they are doing a fine job doing so.

Machines running OpenBSD at home:

- Dev machine: an AMD system
- Ground Control System for UAV: Lenovo R400
- Router: PC Engines APU 2

_[10 Aug 2018]_

[10 Aug 2018]: https://www.bsdjobs.com/raw/people/drobban.md
[OpenBSD]: https://www.openbsd.org/
[this talk]: https://www.reddit.com/r/openbsd/comments/8pwwma/bsdcan_theo_de_raadts_speculation_on_intel_talk/
[@_drobban]: https://twitter.com/_drobban
