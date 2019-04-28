<a href="/" title="home"><img src="/header-white.png" class="w3"></a>

# Berkeley Software Distribution

This line of operating systems started out life as a series of patches
to AT&amp;T UNIX which was introduced to the University of Berkeley by
Ken Thompson whilst on sabbatical in 1977.

The development of BSD is closely tied with that of the internet.
BSD&#39;s modern variants are some of the oldest communities who have
collaborated over the internet to develop a software project which
continues to today. The workflow of the projects has transpired to
become the standard way of developing open source software on the
internet, whether it&#39;s <a
href="https://en.wikipedia.org/wiki/Kernel_Normal_Form">adhering to a
style guide</a>, <a
href="https://en.wikipedia.org/wiki/OpenBSD#Open-source_and_open_documentation">developing
with a publicly accessible source repository</a>, or <a
href="https://en.wikipedia.org/wiki/Hackathon#Origin_and_history">holding
a hackathon</a>.

For a newcomer interested in an operating system to run on your
hardware, it is a great opportunity to be a part of a tech savvy
community working to evolve an idea started almost 40 years ago.

As a business, each project produces a mature and robust operating
system that has seen many applications from running on devices such as
<a
href="https://en.wikipedia.org/wiki/PlayStation_4_system_software">game
consoles</a>, <a
href="http://undeadly.org/cgi?action=article&amp;sid=20140506132000">mobile
phones</a>, <a href="http://imgur.com/a/SMVdp">cars</a>, <a
href="https://en.wikipedia.org/wiki/NetBSD#Examples_of_use">satellites
and the international space station</a>. Nearly all projects are backed
by a non-profit foundation which can act as a liaison for businesses and
assist with enquiries regarding development.

You&#39;ll find the various <a href="bsd.html">BSD&#39;s</a> listed on
the side menu in chronological order, starting from the <a
href="bsd.html">oldest</a> to the <a href="dragonfly.html">newest</a>.
All but the original BSD project are actively developed.

## Documentation

No matter the flavour, documentation is a key part of the development
process for the BSDs. Whether it is the Design & Implementation
series which started with covering 4.3BSD in 1989 and more recently
FreeBSD 10 in the fourth instalment of the series, or each projects
own set of documentation. Documentation is important as it
distinguishes intent & implementation as well as save a lot of
question and answer emails. FreeBSD has
[handbooks](https://www.freebsd.org/docs.html), NetBSD has
[guides](http://www.netbsd.org/docs/#guides), OpenBSD has
[FAQs](http://www.openbsd.org/faq/index.html), DragonFly BSD has a
[handbook](http://www.dragonflybsd.org/docs/handbook/) and all
projects make their man pages available online as web pages. There
is even a [teaching course](http://teachbsd.org/) based around the
[The Design and Implementation of the FreeBSD Operating System, 2nd
edition](http://www.informit.com/store/design-and-implementation-of-the-freebsd-operating-9780321968975).

## Frameworks for building embedded images

Each operating system release is a complete, self contained bundle,
containing the documentation and necessary toolchain required for
building a copy of the operating system from source. `release(7)`
on [NetBSD](http://netbsd.gw.com/cgi-bin/man-cgi?release) &
[FreeBSD](https://www.freebsd.org/cgi/man.cgi?query=release),
`release(8)` on
[OpenBSD](http://man.openbsd.org/OpenBSD-current/man8/release.8),
`nerelease(7)` on
[DragonFlyBSD](https://www.dragonflybsd.org/cgi/web-man?command=nrelease)
cover the release build process for each operating system.

For the purpose of embedding the operating system it may not be
desirable to build a full blown release. Depending on the choice
of variant, either the functionality is built in as standard or a
project exists to assist with generating customised images with
ease.

NetBSD has a target for generating an image in build.sh, customisations
controlled by variables set in
[mk.conf](http://netbsd.gw.com/cgi-bin/man-cgi?mk.conf). FreeBSD
had [PicoBSD](http://people.freebsd.org/~picobsd/old/picobsd.html)
which is now superseded by
[NanoBSD](http://www.freebsd.org/doc/en/articles/nanobsd/index.html).
OpenBSD has [flashrd](http://www.nmedia.net/flashrd/) and
[resflash](https://stable.rcesoftware.com/resflash/). DragonFlyBSD
has
[nrelease](http://gitweb.dragonflybsd.org/dragonfly.git/tree/HEAD:/nrelease).
