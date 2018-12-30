<p><a href="/" alt="avatar" title="home page"><img src="lattera.jpeg" class="avatar"></a></p>

# Shawn Webb runs HardenedBSD

As a teenager, I immersed myself in learning the art of computer
exploitation. Wading through buffer overflows and format string
vulnerabilities, I learned the importance of exploit mitigations
and system hardening practices.

To illustrate, free dial-up ISPs required the use of adware as the
method of connecting to the internet. The adware would dial in,
authenticate, and show you ads via an always-in-focus window. Since
my family didn't have the means by which to pay for internet access,
we were left to use these free dial-up ISPs. Fed up with the waste
of precious 33.6Kbps bandwidth, I learned how to reverse engineer
the adware and devised a solution for always-on, banner-free, and
cost-free internet.

Back then, I used Red Hat Linux 6. Not RHEL, but Red Hat. The Red
Hat distribution that you found attached to a geeky magazine at
your local Barnes and Noble. By this time, I learned how to script
and would auto-connect to the internet whenever the dial-up connection
disconnected. Having only one phone line, my parents surely missed
out on countless important calls.

Fellow hackers taught me the beauty of [FreeBSD] 4.0. Jails made
their debut. I instantly fell in love with how coherent and organized
FreeBSD was (and still is). During this time, I studied exploitation
deeply on Linux and FreeBSD. I learned the importance of exploit
mitigations, especially since software written by imperfect humans
will always have imperfections.

Fast forward a few years. It's now 2005. I left the hacking scene
for a couple of years to focus on religious studies and serve a
mission.  After coming back in 2007, I resumed computering.

Inspired by Andrew Griffiths' Binary Protection Schemes paper, I
worked on a project called libhijack, a post-exploitation tool to
make runtime process infection via ptrace abuse easy. Originally
developed against Linux, I eventually ported the project to FreeBSD.
The project is still active and now only targets FreeBSD amd64 and
arm64 systems.

A few more years passed, and I felt the need to help increase the
security of FreeBSD. In 2013, I set out to implement Address Space
Layout Randomization (aka, ASLR). Oliver Pinter, who happened to
be already working on an ASLR patch, caught wind of my desire for
ASLR in FreeBSD. Oliver and I joined forces. [HardenedBSD] was
officially formed in 2013, with the website being launched in 2014.

Originally, my efforts in HardenedBSD were meant to simply be a
staging area. All features were to be merged upstream to FreeBSD.
Unfortunately, that idea didn't pan out. Instead, HardenedBSD
continues to this day to innovate with unique implementations and
integrations of various exploit mitigations. ASLR was only the
beginning and HardenedBSD has moved on to other exploit mitigations
and security enhancements. The primary goal, yet to be achieved,
is a clean-room reimplementation of the grsecurity patchset for the
BSD community.

All of my systems (laptops, desktops, servers) run either HardenedBSD
-CURRENT or HardenedBSD 11-STABLE. The only systems that don't run
HardenedBSD are his Android devices (phone and tablet). My home is
wired for multiple networks, including a fully Tor-ified network.
To be behind Tor, all I have to do is plug in to a special network
jack in the wall. All traffic automagically gets routed through Tor
without any special configuration on the connected system.  HardenedBSD
is the only operating system I feel comfortable with in doing
something like that.

I am currently researching Cross-DSO CFI (applying Control Flow
Integrity to applications and shared objects alike) on amd64 and
am porting SafeStack to arm64. I am also setting up the HardenedBSD
Foundation, a 501(c)(3) not-for-profit, tax-exempt organization in
the US. The Foundation will help ensure HardenedBSD remains successful
and has the resources it needs to live on.

Find me on 
[Twitter](https://twitter.com/lattera) and
[Mastodon](https://bsd.network/@lattera).<br>
Contact me via Tor-ified Signal (_subject to change_) +1&nbsp;443-546-8752

_9 Aug 2018_

[HardenedBSD]: https://www.hardenedbsd.org/
[FreeBSD]: https://www.freebsd.org/
