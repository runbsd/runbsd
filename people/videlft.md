<p><a href="/" alt="avatar" title="home page"><img src="videlft.jpeg" class="avatar"></a></p>

# Vincent Delft runs BSD

My name is Vincent Delft, I'm a project and program manager since
over ten years having managed several complex IT and Telco projects
/ programs in Belgium and Luxembourg. You can find all my professional
life on [LinkedIn](https://www.linkedin.com/in/vincentdelft). But
I'm also an enthusiast user (since 1998) of open source solutions.
Mainly [OpenBSD], Python, and PostgreSQL. In 2016 I've decided to
share some of my stories, this is one of the goal of [my
blog](http://www.vincentdelft.be/).  Last element (I'm proud of it
;-)): with a total score of 87.9%, I'm happy owner of the [BSD
certification](http://www.bsdcertification.org/) since February
2016.

I'm using Linux since 1998. At that time my goal was to develop a
house's alarm server able to send short messages (sema digit). The
detailed story of this machine is
[here](http://www.vincentdelft.be/post/post_20160709).

Since 1998, I've used several Linux distributions, but, for me, the
best one was Gentoo. This was a really funny moment, surely with
the energy that Daniel Robbins put in it.

But in 2009, I was looking for a simpler system than Linux. Easier
to upgrade and easier to maintain release after release. After
having looked at FreeBSD, a little bit of NetBSD, I've selected
OpenBSD.

Since that period, OpenBSD has never disappointed me. 

On the server part, at that time, OpenBSD was a great system. On
desktop it was a little bit more complex. I remind that, at this
time, lot of websites were with Flash (not working on OpenBSD).

The point is that, as of today, all machines in my house are OpenBSD.
From the [NAS](http://www.vincentdelft.be/post/post_20160719) with
a [Time machine](http://www.vincentdelft.be/post/post_20160724),
the [DAC](http://www.vincentdelft.be/post/post_20160726) using the
wonderful [sndio](http://man.openbsd.org/sndio), the
[firewall](http://www.vincentdelft.be/post/post_20160714), and even
my kids have OpenBSD on their PCs (for school's tasks mainly on
libreoffice ).

Back in 2007, during my visits at FOSDEM, I've received a DVD of
FreeBSD. I've install it, but I was not convinced by it. So, as
said just before, OpenBSD is my preferred system.

OpenBSD is not the fastest, with most sexy GUI,.. But it's so simple
to use and maintain it. Moreover, OpenBSD is very well documented,
and one release every six months is a perfect cycle for my needs.

Moreover the [openup](https://www.mtier.org/solutions/apps/openup/)
tool developed by m:tier is very good and complementary to the
OpenBSD patch system. Indeed, openup provide also patches for
applications too.

I also like the [port system of OpenBSD](http://openports.se/). In
fact, most of the time, I find the exact tool I need in this app
store. OpenBSD port's developers are maintaining intelligently this
repository. Most packages are up to date, runs nicely.

As you have understood, I'm using OpenBSD for firewall, NAS, DAC,
laptop. But also for websites via [Vultr](https://www.vultr.com).

On laptop I'm using openbox with Tint2 for the GUI part. I've shared
some Tint2 [snippets](http://www.vincentdelft.be/category/tint2)
which facilitate me in several tasks. I have also developed a
[Network Manager Control](http://www.vincentdelft.be/category/nmctl)
in Python which allows me to easily switch from network interface.

On the firewall side, I've developed a solution on top of PF and
DHCPD which allow me to control outgoing flows based on the users.
For example, I'm able to block all advertising sites for all users
connected on my Wi-Fi network. But I'm also able to cut internet
connections for my kids after 23:00. It's time to sleep, isn't it?
Such filtering can be fined tuned by categories (ads, porn, fishing,
etc), users and hours. At home, this avoid lot of troubles on Android
phones (the only machine where I cannot install OpenBSD).

For websites, I also have developed a system to ban bad visitors
of my websites:
[log2table](https://sourceforge.net/projects/log2table/files/).
This is a small daemon I've developed based on fail2ban principles.
More details
[here](https://sourceforge.net/p/log2table/code/ci/master/tree/).
In short, if someone is not doing good thing on my server (via HTTP
or SSH), log2table will publish his IP address in a PF table.  To
each bad action those users increase their non-popularity. At one
moment they goes to this table for which PK blocks them for several
hours. They idea is to show those guys that, on my web site, they
are loosing their time.

I'm also fan of several componenents of OpenBSD, like httpd(8),
smtpd(8), sshd(8). Those OpenBSD developers are so good.

How do I use BSD at work? That's a very good question. I've no the
answer. I would really like to combine daily job and OpenBSD, but
I haven't yet found how to do it.

If anyone in Belgium is looking for OpenBSD solutions... feel free
to contact me. :-)

- I'll be happy to install a firewall. Tune it for their needs. 
- Why not provide OpenBSD latops to technician always on the roads
  (with encryption, read-only, VPN)? So no more worries when a
  machine is lost or stolen. Moreover, those a very cheap machines.
  OpenBSD does not need lot of HW resources.
- Why not setup a small server interfacing with IoT devices (like I
  did for my alarm's system)?

I have several ideas, but this will only work, if there are customers
on the other side of the table. ;-)

Find me on [Twitter].

_7 Aug 2018_

[Twitter]: https://twitter.com/videlft
