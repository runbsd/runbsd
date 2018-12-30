<p><a href="/" alt="avatar" title="home page"><img src="mgiunti.jpeg" class="avatar"></a></p>

# Maurizio Giunti runs FreeBSD

I'm Maurizio Giunti ([@mgiunti]) and I met freeBSD back in 2003.
It was [FreeBSD] release 5!

At the time I was a Windows and web developer for a company here
in Italy, but also spent a lot of my free time developing my own
stuffs and having fun with system configuration.

In particular, I used to run my own server in my house basement:
Internet was very young at the time and it was not unusual having
people run in-house mail servers and web servers, just they usually
did it for companies, while I did it for fun!

I used to run it on a Windows 2000 server first, and I migrated it
to a Linux server later. I always had a crush for Unix-like systems
since I met Aix and the beautiful Solaris workstations back at the
Uni, but unfortunately at the time the company I worked for wasn't
very interested about making stuffs on Unix.

Anyway, when I decided to switch my home server from Windows to
Linux, I had a go with several distros, but they looked to me way
too cluttered: too many configuration files and no real standard
about their names and contents.  Than I remember that a couple of
friends were great fans of FreeBSD, so I decided that I could try
it too. I also decided to buy a book about it, and I was so lucky
to get a printed copy of the first edition of "Absolute FreeBSD"
by [Michael W. Lucas]. It was one of the best tech book I ever read:
clear, accurate and even very fun to read. It made me understand
and love FreeBSD.

I found FreeBSD was exactly the work environment I was searching
for: it was clean and consistent. User programs are separate from
base operating system files, for example os system config files are
in `/etc` while user programs configuration files are in `/usr/local/etc`.

I also loved the way the system could handle RAID in a easy way,
with GMIRROR back then, and also with ZFS now, and how easy was
keeping both system and programs up to date.

What I liked most was the fact that I could easily install a
full featured net server without burden of a graphical interface:
it was great not having to deal with hundreds of libraries and
programs just to have a GUI which is nonsense on a headless server.

I loved everything about FreeBSD, so between 2003 and 2004 I switched
my basement server system to it. At the time the services it run
were Samba server (to share files to Windows PCs), Postfix mail
server plus The Courier IMAP as IMAP/POP3 server, Apache, PHP and
MySQL.  Basically I had a top notch (for the time) server which run
on non-expensive, mainly recycled, hardware.

Now fast forward up to 2018: many things changed from those sweet
times, I even changed house, but in my basement there still is a
FreeBSD server. It is version 11.1 now, with a couple of ZFS tanks.
It no more runs a mail server, but it now works mainly as media
server and backup station.

In the meanwhile I also changed work: I left the old company and
funded [my own software company](https://www.codeguru.it), where I,
with my colleagues, develop software and solutions for ecommerce
and web marketing companies.  And I use FreeBSD for business too:
my company main server is FreeBSD powered, it runs ZFS and hosts a
number of jails each one specialized on some task.

We have a Postfix,  Dovecot, SpamAssassin mail system, and also MySQL
server, Memcahed, Apache and HAProxy instances.  One of our SaaS
platforms, [EZAlert](https://ezalert.me), is fully run on FreeBSD
servers.

We also moved some of our clients' systems to FreeBSD: the last
one, few months ago, is a famous sport-related, Italian  e-commerce.
We migrated from a all-in-one Linux server config, to a FreeBSD
multi-jail/ZFS configuration that solved a number of problems they
had to handle traffic spikes, and with ZFS we let them back up
everything with no downtime.

Thanks FreeBSD, you really own the power to serve!

_8 Aug 2018_

[@mgiunti]: https://twitter.com/mgiunti
[FreeBSD]: https://www.freebsd.org/
[Michael W. Lucas]: https://www.michaelwlucas.com
