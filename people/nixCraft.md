<p><a href="/" alt="avatar" title="home page"><img src="nixCraft.jpeg" class="avatar"></a></p>

# Vivek Gite runs FreeBSD

I am Vivek Gite (aka [nixCraft](https://twitter.com/nixCraft)).
I am a professional sysadmin and working in IT industry since 1994.
I learn the basics of networking, sysadmin, and Unix in school but
due to some personal reasons, I dropped out of school. 

I first learned about Solaris Unix. I have fallen in love with Unix
and related tech ever since. I quickly took a job as a Linux and
Unix sysadmin. Around 2000 I was introduced to FreeBSD (FreeBSD
version 4 was extremely popular with ISP during 2000 for mass shared
hosting and email hosting/routing.) and later to OpenBSD for firewall
purpose.

I also created popular [Linux, *BSD and Unix sysadmin
blog](https://www.cyberciti.biz/) and [Linux/Unix and shell scripting
forum](https://www.nixcraft.com/). I also maintian [Linux bash shell
scripting wiki](https://bash.cyberciti.biz/guide/Main_Page). I have
written tons of tutorial on both
[FreeBSD](https://www.cyberciti.biz/faq/category/freebsd/) and
[OpenBSD](https://www.cyberciti.biz/faq/category/openbsd/).

## What is your favorite BSD system?

FreeBSD. It has a rock-solid foundation along with impressive tech
such as:

- It is Unix. It is Free. It is robust. It pays my bills and put
  food on table too. ;)
- FreeBSD is the complete operating system. Everything comes from
  one source.
- Out of box software collection in both base and ports system.
- Documentation &mdash; [The FreeBSD
  Handbook](https://www.freebsd.org/doc/handbook/).
- Awesome support via FreeBSD forum.
- Jails (much more secure as compared to Linux containers).
- ZFS (never lost a single file on ZFS based NAS or backup system).
- Bhyve.
- Powerful networking stack.
- Friendly developer and BSD sysadmin community. Often I interact
  with devs online and everyone friendly and treat each other with
  respect.
- Easy to manage configuration due to KISS and Unix philosophy.
- FreeBSD based products such as [pfSense](https://www.pfsense.org/)
  (enterpise grade BSD licensed firewall) and
  [FreeNAS](http://www.freenas.org/) (enterpise grade software dNAS)
  saves me lots of time while working with my clients. Software
  built on top of FreeBSD are stable and provide GUI based option
  to configure firewall and NAS server respectively.
- Stability and updates &mdash; The whole FreeBSD box can be simply updated
  and patched by running freebsd-update and pkg commands.
- Privacy and security. Your private data is not sent or phoned
  back home when you use FreeBSD.
- Good amount of DevOps and developer tools. I mostly use Perl and
  the Python-based tool to manage a bunch of servers.

I used OpenBSD on my older MacBook (Late 2006) for a long time
before it died out. OpenBSD has a reputation for being extraordinarily
secure and robust code auditing for the base system.  These days
my OpenBSD usage is mostly limited to firewall and router though.

## How do you use BSD today?

FreeBSD internet server (www/proxy/pgsql/mysql/nginx/apache).

FreeBSD as Intranet (LAN) server such as DHCP, NFS.

Jails + Rsnapshot to keep backups of nixCraft projects.

pfSense firewall to protect corporate infrastructure.

FreeNAS server as NAS for home and backup system for nixCraft and
my clients project.

Ansible is an IT orchestration engine. It automates configuration
management, application deployment and many other IT needs for
Linux (mostly Centos/RHEL/SUE and Debian/Ubuntu), BSD boxes.

## How to use BSD at work?

I have been using FreeBSD for about 18 years and some of my client
for about 17 years. Based on my experience and my clients need I
suggest FreeBSD when you need: stable network stack, pure Unix
experience, microservices/API using nginx, BSD license, a well-defined
path for operating system updates, timely security patches.

FreeBSD means job security for you too. Pay is good as compared to
Windows or other IT pros. BSD is often needed some sysadmin knowledge,
ability to read documents, a bit of coding in sh, Perl, python, C,
etc.

You can run FreeBSD on everything. Most of my clients use it on AWS
EC2 and GCP. We use it for a variety of purposes in a single user
mode or in a clustered mode where a bunch of FreeBSD servers scales
out web applications or support mobile applications:

- Nginx server or Apache server
- Static and dynamic asset caching
- TLS/SSL acceleration and termination
- Database server
- VPN (IPSec or OpenVPN)
- Firewall
- NAS, CIFS, NFS server, etc

I use Ubuntu Linux 18.04 LTS on the desktop as many of my clients
use [KVM on
Ubuntu/CentOS](https://www.cyberciti.biz/faq/category/linux-kvm/)
and Linux containers. Ubuntu also supports remote server management
tools such as Intel AMT/ME, impitool, and other legacy IT stuff
that need Java, Flash and old stuff that only supported over a
serial console. It is better than using Windows 10. ;)

I also have a company issued MacBook Pro (Mid 2014), that I used
when compliance in enteprise IT needed where only supported options
are Windows 7/10 or macOS.

_6 Aug 2018_
