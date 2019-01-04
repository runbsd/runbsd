<p><a href="/" alt="avatar" title="home page"><img src="pcarboni.jpeg" class="w3"></a></p>

# Pablo Carboni runs FreeBSD

I'm Pablo Carboni. 41 years old from Argentina. Have been working
and having fun for the latest two decades as a {Unix,DNS,Net}
admininistrator. I'm in amateur Unix coding and little bit of
infosec.

In particular, I worked with [FreeBSD] as my main platform and the
core of this story.

Started with Unix by learning Linux at university, then quickly
moved to FreeBSD (2.2.x) due to my first paid job.

First times were tough, because of differences from what I'd learned
before.  (No, I don't like those silly OS wars).  Then I realized
that everything is at the same place in a file system, in the same
directories. I mean, binaries, configs, third party software (ports
and packages: no matter what version, maintainer).

Things that caught my attention from FreeBSD at the earliest years:

- By default, the CLI doesn't have colors (csh, sh). The included
  [vi(1)] is nvi (has no colors too).
- The base install&mdash; the whole OS&mdash;is one thing.
- A file system layout comes in an uniform fashion. 
- No additional services installed and started by default.  
- Rock solid? Yes, in part because of planned releases, in part
  because of a well tested code.
- Good network performance.

---

Let me tell you a story how I recovered an old Compaq Proliant with
FreeBSD.<br>
_[Same in Spanish]_

> There was an international geek 3-day event,
[Nerdearla](http://nerdear.la), which takes place every year: tech
talks and workshops, coworking places, challenges, and much more!

> This time, one of those challenges, was to boot old Compaq Proliant
G1, donated by [Museo de la
inform&aacute;tica](http://museodeinformatica.org.ar/), where they
had a booth inside the event.

> CD reader was ok. Memory check ok. RAID 1 was ok.

> However, everyone who attended the event during the first and
second days tried to recover the server by using Linux CDs with no
success at all. See _the note about CD reader speed_.

> When I attended the third (last) day, I had a couple of CDs and
hardware to donor to this museum through the booth, I find out about
the challenge.

> What was my thought? The hardware is working fine. Why not to
give a try by booting with my FreeBSD 4.x CDs?

> Then, inserted those CDs, and it's booted immediately! In particular,
the CD reader lens was not clean enough for installing X Window
System (CRC error), but the whole installation went fine, including
networking, Lynx accessing Google Search. :-)

> _Note about CD reader speed_: I think that my CDs worked fine
because they were burnt with 2x or 4x speeds&mdash;maximum for this
oldie Compaq&mdash; and those Linux CDs, I guess, were written at
8x or higher. ;-)

---

Things I developed in the past, just to have fun and learn FreeBSD.

- Some (non-official) ports because I needed them. One port was
  meant to be official, but needed a little polish with poudriere.
- An Apache module for my job.
- A Socks v4 PoC, pthreads only. Unfortunately, no kqueue or libevent.
- A LKM module PoC.
- My latest piece of code was for Net-SNMP: it enables support for
  multi-core CPU usage (merged with 5.7.3): on OID
  `HOST-RESOURCES-MIB::hrProcessorLoad`.

I provided services based on FreeBSD, with high performance in mind
like: for example, setup, tweak, fine-tune [Unbound] DNS resolver
to hold 54Kqps per box.

Find me on 
[Twitter](https://twitter.com/pcarboni) and
[Mastodon](https://bsd.network/@pcarboni)

_11 Aug 2018_

[Same in Spanish]: https://sysarmy.wordpress.com/2017/08/15/como-levante-un-viejo-proliant-o-la-espada-del-rey-arturo/
[Unbound]: https://nlnetlabs.nl/projects/unbound/about/
[FreeBSD]: https://www.freebsd.org/
[vi(1)]: https://man.openbsd.org/vi.1
