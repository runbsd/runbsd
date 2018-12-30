<p><a href="/" alt="avatar" title="home page"><img src="fr0xk.jpeg" class="avatar"></a></p>

# Nikolai Lvovich runs BSD

Hi! I am Nikolai from Ukraine.

What I do? I work as a soil researcher, and part time school teacher
in my hometown. Besides, I am a university student, pursuing post
graduation in Mathematics currently. I used to be a shitty gamer,
messed with digital audio, I still bang my head with Ibanez RGD
2127z.

## Linux Period

I first encountered Linux with Ubuntu 10.04. I bought an HP laptop,
which had Ubuntu installed. I didn't even know what is an OS or
GUI, or package manager at that time. Windows was the OS by that
time for me.

I played with Ubuntu a few days, installing PPAs, random commands
copy pasted from the Internet until the system went to hell. Having
the only OS broken, I needed to do a fresh install of it. Honestly,
I never installed an OS before, so I decided to do this time, ended
up installing Ubuntu 12.04 LTS. It took me few a bit time to figure
out that I screwed my data of whole hard drive during installation
as I chose "Use the whole disk for Ubuntu!".

That's the hell of my UX experience with Ubuntu. And since then,
understood what it likes to be a member of GNU/GPL church, anti
evil corporate, distro hopping from Linux Mint, elementary, Arch,
to Gentoo and so and so. But I honestly, never liked this kinda
socialism in technology myself.

When I realized, I have spent enough time on this, decided to stick
to something stable. I stayed in Debian 7 to Debian 9 release, but
something always bugged me, debian 9 was completely strange for me.
so I started to keep scratching my hipster head within new cool
kinds of stuff vs stability. I even worked with Debian Project as
a [Wiki Maintainer](https://wiki.debian.org/Nikolai%20Lvovich).

## BSD Period

I was learning to program as a hobby. I was getting into bourne
shell already. I was heavily influenced by the simplicity of C.
These days, languages are bloated all over the places, trying to
solve various problems. Be it Go, Rust, JavaScript and what not.
While I was learning about space-time complexity, I got introduced
into LLVM. Chasing it, I landed up in [OpenBSD]. I was running
OpenBSD as a guest inside Void Linux host. It's a simple operating
system, as you all know. To be honest, I got screwed by BSD userland.
Commands were not the same, doing things were different, different
init system (not systemd, or SysVinit, etc, etc).

But...

The OpenBSD community of /r/openbsd helped me a lot. I able to get
familiar with OpenBSD tools and userland, learned basic system
administration for casual desktop use cases. Clang was really helpful
at teaching me common mistakes.

By the time, I had a MacBook, where I used dtrace a lot for my
programming practices which [FreeBSD] includes into. Another things
I considered about FreeBSD system is..

- It actually looks and works like an OS. An operating system should
be a platform to run applications on top of it. I always used to
frustrated by all packages being thrown into `/usr/bin`, from
*dhcpcd*, to *LibreOffice* in Linux userland. This always bugged
me. In fact, if a distro comes with a full-blown DE, and a user try
to uninstall it, most of the time, it uninstalls *NetworkManager*,
*Xorg* etc too (unless user pin that as manual install).

- I always needed a dirty backup solution. I have been using
Clonezilla, fsarchiver in Linux, but It was very time-consuming.
ZFS can be used to work around here. I tried btrfs, and I failed
to understand the concept of subvolume, and practically taking
snapshot/rollbacks. Snappy on btrfs works in a way that makes me
go nuts.

- Clang+LLVM, obviously, my go to. Autocomplete with company inside
Emacs works great.

- BSD license. Yes... I am sure, GPLv2/v3 both are good licenses,
but the world doesn't work that way now. Right? Besides, as Neil
says, "What is more important is that more people run our *BSD code
than we have control of what other people can do with it! "

So, I decided to go with FreeBSD. I started with FreeBSD 11.0, now
running FreeBSD 12. I have no plan to go back into Linux, till
FreeBSD go really nuts. And I don't believe that's going to happen
with a very well engineered Operating System. I also encourage my
students to try out FreeBSD or OpenBSD with various boot environments.

So this is my story of Unix, Linux, and BSD. What's yours? I am
eager to hear...

You can find me on [Twitter](https://twitter.com/fr0xk).

_[30 Dec 2018](/raw/people/fr0xk.md)_

[OpenBSD]: https://www.openbsd.org/
[FreeBSD]: https://www.freebsd.org/
