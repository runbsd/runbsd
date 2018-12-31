<p><a href="/" alt="avatar" title="home page"><img src="ogmaconnect.jpeg" class="avatar"></a></p>

# Tom Smyth runs BSD

My name is Tom, I'm the CTO  of Wireless Connect Ltd. My first
exposure to Unix was Solaris back in the year 2000, I got an
educational discount for Solaris for x86 systems, I also got to use
it by sneaking into the Telecoms Lab in my University, Dublin City
University. Around the same time I was a member of Redbrick and had
a shell account on mother.redbrick.ie which was running FreeBSD at
the time.

My current favourite BSD is [OpenBSD], I was first exposed to it
back in 2006. I fell foul of the Em64T Intel Xeons not being supported
by OpenBSD (amd64) due to the hardware execute disable bit, not
being available in 64 bit on those processors. (At the time I was
not happy... but since realised it was the right call by OpenBSD
project).  I also used [FreeBSD] + Dummynet for WAN link Simulation
and Testing.at around 2007. I had better success with OpenBSD around
2009 where I used it as a DNS (BIND) server, and as an SSL terminator
using _stunnel_ ahead of a reverse proxy. As DNS servers and as a
SSL reverse proxy we found OpenBSD to be very reliable, unfortunately
because they just worked...  the opportunity to learn about OpenBSD
was mostly confined to the setup. My favourite feature of OpenBSD
is rdomains/VRFs, the syntax of PF and rdomains, is concise yet it
has profound capabilities... roll on approx ten years we are using
OpenBSD more and more in our organisation.

Currently in 2018, we use OpenBSD for a variety of roles in our company,<br>
0) BGP Route Reflectors for our ISP using OpenBGPD,<br>
1) DNS recursive resolvers using Unbound,<br>
2) DNS authorititive DNS servers for reverse DNS PTR records using NSD,<br>
3) TLS termination using relayd,<br>
4) load balancing using relayd,<br>
5) NTP for our ISP and our clients using OpenNTPD,<br>
6) mail relay servers for our ISPs and our clients using OpenSMPTD,<br>
7) website hosting&mdash;we are rolling out OHMP OpenBSD + httpd + MariaDB + PHP based servers,<br>
8) OpenVPN VPN terminators for our client WANs,<br>
9) BGP looking glasses for our helpdesk staff to diagnose internet routing issues using BGPLG CGI + OpenBGPD + httpd,<br>
10) internal ISP certificate authority infrastructure,<br>
11) filtering DNS infrastructure for business clients (Optional&mdash;opt-in service) using Unbound,<br>
12) we are using OpenBSD as our preferred CPE OS (client premises equipment), for business firewalls and fail-over devices.

I'm on [Twitter](https://twitter.com/ogmaconnect1) and
[Mastodon](https://bsd.network/@ogmaconnect).

_[31 Dec 2018](/raw/people/ogmaconnect.md)_

[FreeBSD]: https://www.freebsd.org/
[OpenBSD]: https://www.openbsd.org/
