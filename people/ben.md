<p><a href="/" alt="avatar" title="home page"><img src="ben.jpeg" class="w3"></a></p>

# Ben Adams runs OpenBSD

Hello, I'm Ben Adams a 37 year old web developer and system
administrator.

I started using Red Hat Linux 7.0 in 2000. That's not Red Hat
Enterprise Linux, but Red Hat from pre-Fedora era.  For the next
few years I did a good amount of distro hopping. :) I used Linux
until around 2005, where I started to use [FreeBSD], and then I
came across an OS that had _no security holes for over seven years_.
Wondering how this could be I dug in to the system.  At that time
was [OpenBSD] 4.2 released&mdash;November 2007. I found the
documentation very easy to read and pick-up.

At the same time I worked at a hospital as a Clinical Data Manager,
I found a security hole in a enterprise vendor web application where
I could see patient information from other hospitals, for incident
occurrences (med errors, patient falls, lawsuits based on incidents,
etc).  After going back and forth with the company's developers in
India and finding they have trouble fixing the security vulnerability.
My boss challenged me to come up with a safe secure alternative.

I then created my own incident occurrence system that was using PHP
on a small OpenBSD workstation the application was used across two
hospitals and five long term care facilities. Application held this
information and I recorded and calculated core measures information
for tracking by floor/wing.  The system held its own with software
code updates and running on a RAID 1 setup on this small workstation
for over three years at which I left the hospital.

> From there I work primarily on Linux based systems for the next
few years as a Python/Node.js/Erlang developer.  Currently I work
at a company that manages a mix of 18,000 servers using 70% Linux,
20% Windows and others a mix of HP/Solaris boxes.  Using Ansible
development tools for managing systems and keeping track of
certificates.

Back to BSD. My number one BSD without hesitation is OpenBSD followed
by FreeBSD, but I'm more of the _Have a problem?&mdash;Find the
best tool in the box to fix the problem_.  If multi-threading and
bandwidth performance is key use FreeBSD.  If security and business
critical services are required, then OpenBSD without hesitation.

Today at home I have a ThinkPad X270 running OpenBSD.  I use this
system for developing an Erlang application hosted at
[MessageMap](https://MessageMap.io). This is a RabbitMQ type
application with some smarts :) coded in Erlang and deployed on
[Vultr](http://vultr.com).

Still trying to get traction on my project, but hope to open source
it once I have some usage and all my features I wanted included are
built into it.

Find me on [Mastodon] or email me at ben@MessageMap.io.

_10 Aug 2018_

[Mastodon]: https://bsd.network/@MessageMap_io
[FreeBSD]: https://www.freebsd.org
[OpenBSD]: https://www.openbsd.org
