### Documentation
No matter the flavour, documentation is a key part of the development process
for the BSDs.  Whether it is the Design & Implementation series which started
with covering 4.3BSD in 1989 and more recently FreeBSD 10 in the fourth
instalment of the series, or each projects own set of documentation.
Documentation is important as it distinguishes intent & implementation as well
as save a lot of question and answers emails.  FreeBSD has handbooks, NetBSD
has guides, OpenBSD has FAQs and all projects make their man pages available
online as web pages. There is even a [teaching course](http://teachbsd.org/)
based around the [The Design and Implementation of the FreeBSD Operating
System, 2nd
edition](http://www.informit.com/store/design-and-implementation-of-the-freebsd-operating-9780321968975).

### Frameworks for building embedded images
Each operating system release is a complete, self contained bundle, containing
the documentation and necessary toolchain required for building a copy of the
operating system from source. `release(7)` on
[NetBSD](http://netbsd.gw.com/cgi-bin/man-cgi?release) &
[FreeBSD](https://www.freebsd.org/cgi/man.cgi?query=release), `release(8)` on
[OpenBSD](http://man.openbsd.org/OpenBSD-current/man8/release.8), `nerelease(7)`
on [DragonFlyBSD](https://www.dragonflybsd.org/cgi/web-man?command=nrelease)

For the purpose of embedding the operating system it may not be desirable to
build a full blown release. Depending on the choice of variant, either the
functionality is built in as standard or a project exists to assist with
generating customised images with ease.

NetBSD has a target for generating an image in build.sh, customisations
controlled by variables set in
[mk.conf](http://netbsd.gw.com/cgi-bin/man-cgi?mk.conf).
FreeBSD had [PicoBSD](http://people.freebsd.org/~picobsd/old/picobsd.html)
which is now superseded by
[NanoBSD](http://www.freebsd.org/doc/en/articles/nanobsd/index.html).
OpenBSD has [flashrd](http://www.nmedia.net/flashrd/) and
[resflash](https://stable.rcesoftware.com/resflash/).
DragonFlyBSD has [nrelease](http://gitweb.dragonflybsd.org/dragonfly.git/tree/HEAD:/nrelease).
