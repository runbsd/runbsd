<p><a href="/" alt="avatar" title="home page"><img src="yuki.jpeg" class="w3"></a></p>

# Yuki runs BSD

owo, what's this?

Hewwo everyone, I'm yuki\_is\_bored. You may know me on Twitter or
Fediverse or you may know me for my open source work at [coala][1],
notably [dependency_management][2].

I've been using BSDs since 2016 and I've started using them as my
daily driver in 2017. Like some people, I moved to BSD systems
because of the advent of systemd.

But unlike what most people say about it, I gotta say that I kinda
like the idea of having a complete system layer maintained in a
single repository rather than a compilation of software created by
random people (kinda like BSD, though some people will send me death
threats if I say that).

My dislike of the project is mostly aimed at the poor maintainership
of the project along with the terrible community management thanks
to le terrible, Lennart Poettering. Feedback and suggestions to the
project (especially those related to security concerns) will be
thrown into `/dev/null` or be tagged as "notfix".

After experiencing Debian's first baby steps into systemd along
with the terrible events surrounding of the past `systemd` maintainer
that have lead my laptop into the new world of `libsystemd` hell,
I had enough and decided to move to other distributions which doesn't
use systemd.

Around this time, People thought Devuan was a clever 'troll' in the
Debian mailing list and people were skeptical about the future of
the project. The Anti-systemd movement was on the rise and the debut
of a lot of systemd-free distribution. There wasn't a lot of choices
which I like so I decided to move to Gentoo/Funtoo which seems
promising.

I liked Gentoo because of its flexibility which is granted by its
BSD ports inspired system called Portage and Gentoo also has a lot
of small communities within its community such as the Hardened
Gentoo community which delivers a hardened kernel, userland and
compiler.

During my days of emerging various ports and perfecting my system,
I slowly found its flaws as well. At that time, LibreSSL support
was bad along with some roadblocks with Portage[^1] that ultimately
made me recompile my whole system numerous times. I ultimately
became unsatisfied with Gentoo.

Around this time, I discovered [FreeBSD] and [OpenBSD]. I discovered
OpenBSD mostly because of the Heartbleed incident and its response
to it and I discovered FreeBSD because of the rising popularity of
ZFS. I tried playing with them but back then, I had decided to stay
with my Linux-isms and just keep trying to build the perfect system
out of mismash of different tools.

In 2016, I was helping my school with setting up a new school-wide
WiFi. While I was searching solutions for the main router, I found
a project called pfSense which uses FreeBSD as the base operating
system. It is a Free (as in Freedom) firewall solution that can run
on normal amd64 machines. I thought that this was a great choice
and thus I decided to use it. The school's system administrator was
skeptical about using a free solution instead of using a well-known
solution such as MikroTik's Routerboards. So, We decided to compare
the two. The pfSense setup was very easy and straightforward. I got
my setup running in mere hours. After I got it setup and connected
it to the network, The school sysadmin borrowed a routerboard from
one of his colleague since we didn't have a license nor hardware
for it and tested it.

The "makeshift" pfSense router which was using an old unused machine
was more capable than the routerboard. On top of being a router,
we can easily do other stuff as well such as having an IDS to protect
the network, Windows update caching, etc. So we ultimately decided
to go with the BSD route rather than the MikroTik way.

Thanks to pfSense, I began to fall into this rabbit hole which is
BSD. I learned how it works along with how the project is maintained
and structured. In the end, I fell in love with it. Since pfSense
is using pf, I thought about how helpful it is to learn more about
PF so I read "The Book of PF".

From there, I discovered more about OpenBSD and start to like it.
So, I migrated the router from the pfSense system to OpenBSD because
I believed it was more lighter and I like the pf.conf(5) syntax so
much rather than the GUI editor. After I boot my USB flash drive
that has been flashed with installfs, I was surprised by how beautiful
simplicity can be.

To me, OpenBSD is the very definition of consistent quality. It
feels like a proper complete operating system made by very talented
developers. It never once felt like a compilation of different tools
rather it feels more like a whole experience that has been crafted
to perfection. At that point, I started to understand how beautiful
a true UNIX system can be. With that, I believe the OpenBSD project
has raised the barrier of quality that other operating systems
should follow.

At that point, I decided to move to OpenBSD. I read the second
edition of Absolute OpenBSD by Michael W. Lucas, the FAQs, the
beautiful manpages and I subscribed to the mailing lists (announce,
misc, tech and ports) and joined the IRC channel.

Before this, I couldn't imagine how beautiful an operating system
can be. OpenBSD is the perfect example of that. It is a great
example of thriving towards correctness, consistency and overall
perfection. Each line of code is crafted along with the documention
which are made with love. Suggestions and feedback are taken
seriously. However, it is not for everyone. They wrote the operating
system for themselves and its users. Thus, it lacks the fancy bells
and whistles which the community deemed to be unimportant or harmful.

Okay, how about FreeBSD?

After I got a new laptop to replace my Thinkpad E430 which had a
broken case due to chemicals eating away the plastic case (whoops),
I decided that I need a server to store and sync my files along
with an always on torrent machine.

First, I tried using OpenBSD. It did pretty well but I wouldn't say
it was a really good experience. OpenBSD's FFS2 file system is
pretty good for the most part but lacks the performance, the shiny
bells and whistles. fsck is very basic, I regularly have to scour
through lost+found every time there's a power failure.

So, I decided to give FreeBSD a go. While it doesn't have the same
consistent quality as OpenBSD, it is a decent operating system with
some quirks. However, once you know its quirks (and how to fix
them), it's a really great operating system. Thanks to the amazing
technologies which is shipped by FreeBSD like Jails and ZFS, I was
able to have a great experience.

It was able to handle all of my ~~hentai~~ anime collection that I
throw at it without a sweat. High workloads like streaming HD videos
while downloading gigabytes upon gigabytes of data wasn't a problem
for it. I began experiencing technological nirvana where I don't
have to worry about loosing data (thanks to file synchronization
with Syncthing) and I don't have to worry about the whole operating
system taking a 180 degree turn without advanced notice. I started
to worry less and just focus on my work.

Thanks to my BSD experience, I started to have experience in other
UNIX opearting systems and interoperability between them and I was
able to do rigourous testing on cross UNIX compatibility for
[coala][1].

As of the time I'm writing this which is my 2nd year of daily driving
BSD, I'm a happy camper that won't go back to lennart-ware infested
penguin land . Thanks to the warmth of the BSD community along with
the friends and people I met along the way, I was able to get an
experience that is incomparable to the one I had with Linux.

The BSD community feels more like a family rather than a huge bazzar
filled with millions of people. I feel like I'm on the same boat
as the whole BSD community rather than "some random user".

I'm hoping to be able to contribute back to the BSD project in the
future.

Right now, I'm rocking a beefed up X220 with FreeBSD, an Android
phone that is totally degoogled and I'm starting to use BSD systems
at work.

Anyway, if you want to follow me in my adventures (well, not
*physically*, please don't *literally* follow me), You can follow
me on [Fediverse][3] or [Twitter][4] (though, I'm more active on
Fediverse now).

You can also go to my [blog][5] where I write about my adventures
with computers, my hobbies and (mostly) random thoughts.

[^1]: Have you experienced how fun it is to update gcc? :^)

[1]: https://github.com/coala/coala
[2]: https://gitlab.com/coala/package_manager
[3]: https://bsd.network/@yuki_is_bored
[4]: https://twitter.com/yuki_is_bored
[5]: https://blog.yukiisbo.red

_[30 Apr 2019](/raw/people/yuki.md)_

[FreeBSD]: https://www.freebsd.org/
[OpenBSD]: https://www.openbsd.org/
