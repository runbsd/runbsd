<p><a href="/" alt="avatar" title="home page"><img src="cfenollosa.jpeg" class="w3"></a></p>

# Carlos Fenollosa runs BSD

Maybe you have been reading about the release of [OpenBSD] 6.5 and
wonder: _What are the differences between Linux and OpenBSD?_ And, to
some extent, other BSDs?

I've also been there at some point and these are my conclusions.

> *Mandatory disclaimer*: this list is aimed at people who are used to Linux
and are curious about OpenBSD. It is written to highlight the most
important changes from *their* perspective, not the *absolute* most
important changes from a technical standpoint. Please bear with me.

The first thing to realize is that, on the surface, the changes are
minimal. Both are Unix-like. You get a terminal, X Window System,
Firefox, LibreOffice. Most free software can be recompiled, though some
proprietary software isn't on OpenBSD. Don't expect any visual changes.

Under the hood, there are _some big differences_ with relatively little
practical impact:

- _BSD licensing_ vs GNU licensing.
- _Whole OS_ model where some _base packages are treated as first-class
citizens_ with the kernel vs bare kernel and everything is
third-party.
- _Documentation is considered as important as code_ vs good luck with
Stack Overflow and reading mailing lists.
- Whenever a decision has to be made, _security and correctness is
prioritized_ vs general-purpose and popularity and efficiency.

---

Do these make little sense to you? I know, I was there. They're
philosophical distinctions which ramifications are not immediately
visible. They can't be explained, you need to understand them by usage.
That's why the typical recommendation is **just try OpenBSD and see**.
So, what are some of the actual, tangible, practical differences? Not
many, really. Some are _features_ and some are _undesired_ side effects.
With every decision there is a trade-off. Let's see some of them:

**OpenBSD is a simpler system**. It's very comfortable for sysadmins.
All pieces are glued together following the UNIX philosophy, focusing on
simplicity. Not sure what this means? Think rc VS systemd

**OpenBSD has excellent man pages** with practical examples. Use `man`.
Really.

OpenBSD has different default daemons/servers/defaults than Linux.

    apache/nginx      httpd
    postfix/sendmail  opensmtpd
    ntp               openntpd
    bash              ksh

...and so on.

These cover 90% of the use cases, while being robust and simpler to
admin. Some Linux-kernel-specific software does not work either. Namely,
docker.

The same for drivers: OpenBSD has excellent drivers, but a smaller
number of them. This includes compatibility drivers: modern/third-party
file systems, for example, are not so well supported.

Because of the focus on security and simplicity, and not on speed or
optimizations, software runs a bit slower than on Linux. In my
experience [and in some
benchmarks](https://www.phoronix.com/scan.php?page=article&item=8-linux-bsd&num=1)
about 10%-20% slower.[^1]

Battery life on laptops is also affected.[^2] My x230 can run for 5 hours on
Linux, 3:30 on OpenBSD. More modern laptops and bigger batteries are a
practical solution for most of the people.

_Are you telling me that the positives are intangible and the negatives
mean a slower system and less software overall?_

At the risk of being technically wrong, but with the goal of empathizing
with the Linux user, I'll say yes.

In reality: it means that the intangibles are intangible *for you*. For
other people, these features are what draws them to OpenBSD. For me, the
system architecture, philosophy, and administration is 10x better than
Linux's.

Let me turn the question around: can you live with these drawbacks if it
means you will get a more robust, easier to admin, simpler system?

But wait! My goal with this thread was to pique your interest! Go ahead
and spin up a VM or install OpenBSD on an old machine and see for
yourself.

Life isn't black or white. Maybe OpenBSD can not be your daily OS, but
it can be your _travel-laptop OS_.
That is exactly my case.

Actually, my daily driver is macOS, not Linux, because I need to use MS
Office and other software which is Windows or Mac only for work.
However, I enjoy using OpenBSD much more. The day I retire I will make
the full switch.

Well, did I catch your eye or what? What are you waiting for? It's a
fantastic Saturday morning, you have the whole weekend in front of you.
Download OpenBSD and learn what all the fuzz's about! Thanks for
reading! Here are more references:

[OpenBSD's website](https://www.openbsd.org/)<br>
[Project goals](https://www.openbsd.org/goals.html)<br>
[Download instructions](https://www.openbsd.org/faq/faq4.html#Download)<br>
[Official FAQ](https://www.openbsd.org/faq/index.html)<br>
[My first OpenBSD impressions from 2015](https://cfenollosa.com/blog/openbsd-from-a-veteran-linux-user-perspective.html)

You can find me on [Twitter].

_[29 Apr 2019](/raw/people/cfenollosa.md)_

[OpenBSD]: https://www.openbsd.org/
[Twitter]: https://twitter.com/cfenollosa

---

[^1]: Test both Linux and OpenBSD on your hardware. Your millage may vary. --Ed
[^2]: ThinkPad X1C5 on OpenBSD 6.5 and Ubuntu 19.04 show similar results: 9&nbsp;hours from 100% to 5%. --Ed
