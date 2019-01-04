<p><a href="/" alt="avatar" title="home page"><img src="brnrd.jpeg" class="w3"></a></p>

# Bernard Spil runs FreeBSD 

I've used [FreeBSD] since version 5.x and have been active on irc
for a long time and never thought that I could actually contribute
much to the project. Initially I submitted PRs for things that were
broken for me (one maybe two every year). Later on I started
submitting PRs including patches to fix the problem (as a non-committer
that's very much appreciated) but again very few per year.

As I got more sophisticated in fixing things in ports, the number
of PRs and patches increased.

At some point I decided that the [MariaDB
10.0](https://bugs.freebsd.org/193539)
[port](https://www.freshports.org/databases/mariadb100-server) was
due. So I started copying the 5.5 port, and failing time and again
to get it to work but ultimately hacked it to build with 10.0! Along
the way I interacted with the MariaDB community to solve some of
the issues and after a while it was added to Ports. Suddenly I was
a port maintainer (scary!).

In this time-frame [Kubilay (koobs)
Kocak](https://wiki.freebsd.org/KubilayKocak) enlisted me in his
wiki-army.

## The LibreSSL thing

I was using LibreSSL about as soon as the Portable version was
released and added to ports. This required me to patch some ports
(Apache, Python,..) so they would build and run with LibreSSL.  That
got noted and some guys on IRC were nagging and motivating (and
helping!) me to do more patches. At some point Ken Moore (PC-BSD,
BSDNow.tv) reached out to me because he wanted to do an EDGE (cutting
edge PC-BSD) build with LibreSSL for ports. This was something I
was looking for as it would surface all, well... most I was later
to find out, problems with using LibreSSL as libssl/crypto provider.
That was a very intense couple of weeks where a poudriere run would
uncover problems with LibreSSL, after patching these problems more
problems would surface, etc. Most issues could be binned into
[categories](https://wiki.freebsd.org/LibreSSL/PatchingPorts) (EGD
removal, deprecated des_ methods, SSLv2 removal). All this resulted
in [LibreSSL/Ports#PC-BSD\_10.1.2\_ports\_build][libressl] and a
large load of patches for ports as PRs in [BugZilla].

When the initial fixing and patch creation was done, Kubilay spurred
me on to upstream the patches which resulted in quite some changes,
usually small, to all kinds of Open Source projects. And boy am I
proud of the trivial changes that made it into these upstream
projects! I can now truthfully say that changes I supplied to
[Python] are part of software running on many millions of systems.
It's only me that knows that that's factually untrue right?

At some point [BSDnow.tv] interviewed me on the LibreSSL story.
Yup, that's scary but a confidence builder as well!

After summer I was contacted by the LibreSSL devs from OpenBSD if
I'd be willing to come to their LibreSSL Hackathon in Croatia 3
weeks later. That was an intense and fruitful week out there with
some great guys! Exchanging information on how LibreSSL is used "in
the wild", what challenges that that poses and learning on the
development of LibreSSL.

Around that time I learned that I was proposed to become a committer
(or cursed with a commit bit?). This then takes some very confusing
weeks to get through the process and get mentors assigned.

Know what's awesome about spending all the effort? It's so immensely
appreciated even though you don't often hear that directly. Sitting
chatting in the hotel lounge during EuroBSDcon you suddenly hear
the guy behind you shout out "What?!? YOU are that LibreSSL guy!?!".

## Moral to this story

- Do NOT be afraid. No-one knows everything already, everyone's
  learning always...
- Do NOT hesitate to ask. Yet be aware that you'll be requested to
  do your part as well!
- GET STARTED. I've long thought I was not capable enough to
  contribute in this way (even though I wanted to).

The FreeBSD community is awesome and full of helpful people! (and
some trolls that you must not let put you down!)

If anything I started this way too late. Imagine the damage I
could've done when I had dug in earlier!

Find me on [Mastodon] or Barnerd@Freenode/FENet<br>
(or on [Twitter] if you're old-school).

> P.S. Haven't managed to mention the awesome [Johannes Meixner] in this
story, yet his support was invaluable!

_[20 Aug 2018](/raw/people/brnrd.md)_

[BSDnow.tv]: http://www.bsdnow.tv/episodes/2015_03_25-ssl_in_the_wild
[BugZilla]: https://bugs.freebsd.org/bugzilla/buglist.cgi?bug_status=__open__&content=LibreSSL
[FreeBSD]: https://www.freebsd.org
[IRC]: https://twitter.com/Sp1l
[Johannes Meixner]: https://wiki.freebsd.org/JohannesMeixner
[Mastodon]: https://bsd.network/@brnrd
[Python]: http://bugs.python.org/issue21356
[Twitter]: https://twitter.com/Sp1l
[libressl]: https://wiki.freebsd.org/LibreSSL/Ports#PC-BSD_10.1.2_ports_build
