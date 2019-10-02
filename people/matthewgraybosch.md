<p><a href="/" alt="avatar" title="home page"><img src="matthewgraybosch.jpeg" class="w3"></a></p>

# Matthew Graybosch Runs BSD

I'm a novelist you probably haven't read, I code for a living (using
mainly Microsoft tech, [for my
sins](https://www.macmillandictionary.com/us/dictionary/american/for-my-sins)),
and I've been running [OpenBSD](https://openbsd.org) on my personal
computers since 2017. If you're familiar with the various [BSD
operating systems](https://runbsd.info) you might raise an eyebrow
at my choice, since OpenBSD is the preferred OS of security-conscious
system administrators.

One would think that it isn't an OS for long-haired metalheads who
write crappy sf on their lunch breaks. Nevertheless, it's the OS
with which I'm most comfortable. Nor is it my first Unix. My first
Unix, if you're willing to count experience gained in a college
computer lab, was SunOS 3.x on a SPARCstation.

Exposure to Unix while learning C was a revelation, and while I
never became a systems programmer, I got familiar enough with Unix
that I soon chafed against the limitations of the PC DOS that came
with my first PC (a secondhand IBM PS Value/Point) and the various
incarnations of Windows with which I had to cope at school and later
at work.

Once I left school and got a job as a developer, I built a new
computer and ran a variety of Unix systems at home. Before I finally
got around to trying OpenBSD on a secondhand Lenovo Thinkpad, I ran
FreeBSD for a while, used Intel Macbooks, and did entirely too much
distro-hopping.

If I learned anything, it was the following:

- GNU/Linux is for people who loathe Microsoft
- OSX is for people who dislike Windows and are OK with throwing money at problems
- The BSDs are for people who actually *like* Unix

For a while I thought I was just somebody who loathed Microsoft.
For a while, I was somebody who loathed Windows and preferred to
throw money at problems to avoid spending time. It was only recently
that I remembered how much I had actually *enjoyed* having access
to an Unix system in college, and that memory came to me the first
time I installed OpenBSD.

I was lucky; I had picked a laptop that had good hardware compatibility
for little other reason than that I liked typing on it and that I
could get a refurbished model for less than $300. Thus it was easy
to just plug in a network cable so my Thinkpad could pull packages
from the network and just follow the instructions on every step of
the boot screen. The only point I lingered over was partitioning,
since I wanted to use all of my drive's space instead of settling
for the defaults and growing disklabel partitions later.

I had "Money for Nothing" by Dire Straits on the stereo while the
installer carried out my instructions, and found myself singing
along in anticipation...

> I want my...<br>
> I want my BSD...

Once it was done I logged in as root, read the
[`afterboot(8)`](https://man.openbsd.org/afterboot) man page, set
up [`doas.conf(5)`](https://man.openbsd.org/doas.conf) so I could
do admin stuff without logging in as root, and started breaking in
my new system. The first thing that struck me was the breadth of
documentation provided by [OpenBSD man pages](https://man.openbsd.org/).
The dev team does *not* do a half-assed job of documenting the
system. If it's in base, it's got a man page, and that man page is
*comprehensive*. Even config files have man pages (in section 5).
I've never seen a GNU/Linux distribution as thoroughly documented
as OpenBSD.

The next big surprise was the sheer generosity of the software
included with the base system when you install every set. Need a
text editor? Take your pick from `vi(1)`, `mg(1)` (an Emacs clone),
or the venerable standard Unix editor `ed(1)`. Need simple version
control for personal projects? Why not `rcs(1)`?  Want a graphical
session? Just enable `xenodm(1)` in `rc.conf.local(5)`; Xenocara
(OpenBSD's custom X.org build) even comes with three window managers:
`twm(1)`, `fvwm(1)`, and `cwm(1)`. Want to run simple websites or
send email?  `httpd(8)` and `smtpd(5)` are there. Need a software
firewall?  `pf(4)` is there and running by default. Hell, if you're
old-school enough to still prefer music on CDs and have your computer
hooked up to a good pair of speakers, try `cdio(1)`.

Naturally, OpenBSD comes with the classic BSD games collection,
with [all your old favorites](https://man.openbsd.org/intro.6).
Like text adventures? Try `adventure(6)`. Fancy a dungeon crawl?
`hack(6)` away. Enjoy simulations? Try `atc(6)` for a taste of an
air traffic controller's duties (union-busting not necessarily
included). We've even got `tetris(6)`.

There's *plenty* you can do with the base system and its included
tools and utilities. If the included public-domain Korn shell
(`ksh(1)`) isn't your cup of tea, you can always install `bash`,
`zsh`, or `fish` using the [package
manager](https://man.openbsd.org/?query=pkg&apropos=1&sec=1&arch=default&manpath=OpenBSD-current).
Need a web browser? Pick a package. Need to do graphics editing?
There's a package for that. Musician or moviemaker? We've got
packages for you. Setting up a industrial-strength home office PC?
We've got LibreOffice, graphical email clients, and everything else
you need. Want to typeset your own documents? TeX Live is in the
packages collection, and so are GNU Emacs, vim, and neovim if the
editors in base aren't fancy enough for you. If you're a developer
working with languages not supported by the dev tools provided in
base, or you're using a more recent SCM than `cvs(1)`, then the
package manager is your friend.

If you want something that isn't provided by the OpenBSD base system,
chances are there's a package or a port available. If you want to
build another machine and install the same packages that you have
on the first, you can dump a list of installed packages to a file.
If you want to remove all of your installed packages and start over
with a clean base system, you can do that without reinstalling the
entire OS.

However, it's not the documentation, the robust and capable base
system, or the package management that sold me on OpenBSD. It's the
fact that OpenBSD wasn't made for me. The developers made it for
themselves, and it just happens to be available if I want it and
am willing to put in the time and effort to make it work for me.
This isn't to say that the community surrounding OpenBSD is rude
or standoffish. I've found other BSD fans on social media friendly
and patient -- as long as you treat them like adults and act like
an adult yourself. They'll even help if you make it clear that
you've tried to solve your problems on your own.

However, I don't think you'll see the core development team worrying
about how make OpenBSD more appealing to the general public. It
suits me because the system doesn't cater to my ignorance or try
to anticipate my requirements. It's a rock-solid general-purpose
toolkit, and what I do with it is entirely up to me.

Admittedly, my life as a writer would probably be easier if I were
content to run Windows or use a Mac like the vast majority of
authors, but I can't help it. I want my BSD! It's not like Unix
hasn't leaked into my writing. For example, in *Silent Clarion* the
computer controlling an orbital weapons platform codenamed GUNGNIR
is powered by OpenBSD, and its protagonist runs into a bit of trouble
because she's familiar with POSIX shells, but not Multics.

Rather than take the easy way out, I run OpenBSD on a Thinkpad
T430s, a Thinkcentre M92P, and an Apple iMac G4 *because I can*. I
do it because Unix is fun to run on secondhand hardware, and because
I don't think it's a coincidence that both Unix and heavy metal
date back to 1969.

You can find me [on Mastodon](https://mastodon.sdf.org/@starbreaker)
and [on the open Web](https://www.matthewgraybosch.com).

_[2 Oct 2019](/raw/people/matthewgraybosch.md)_
