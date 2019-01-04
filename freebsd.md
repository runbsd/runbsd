<a href="/" title="home"><img src="/header.png" class="w3"></a>

# FreeBSD

Forked from the Net/2 & 386BSD code base, 6 months after NetBSD was
started.  The focus of FreeBSD was performance on i386 systems.
Over time support was added for the DEC Alpha as this meant porting
the code base to a 64bit systems and addressing any bugs which would
prevent the code base from running on a 64bit system. Many years
later the project branched out and introduced support for additional
platforms. Today the project boasts support for CPUs such as ARMv8,
[RISC-V](http://riscv.org/) and
[BERI](http://www.cl.cam.ac.uk/research/security/ctsrd/beri/).

FreeBSD is the home to many innovations, such as:

## Ports

Ports is a framework for building software. It abstracts away
different build systems to provide a common workflow to the user,
regardless of the software being built and installed. This frees
the user to request the software they desire and for the system to
compute dependencies and ensure they are built and installed as
well.

Developers and contributors create recipes to install different
pieces of software. These recipes or ports as they are called contain
such information as where the source code is hosted, which dependencies
the software requires to build and run, patches to ensure the
software integrates correctly with the operating system. Ports for
each piece of software are stored in individual directories of their
own, organised in categories of the functionality they provide.

For a user to build and install one of these packages they would
change into the relevant directory & run make install.  This can
be a consuming process depending on the system being built on but
binary packages are of course offered as standard, allowing this
process to be bypassed entirely unless desired. While such functionality
may be a given on operating systems of today, this has been a
standard feature since the early 1990s.

## Jails

The jail mechanism, a form of [operating system level
virtualisation](https://en.wikipedia.org/wiki/Operating-system-level_virtualization),
allows partitions to be created on a system where a binary and
associated dependencies or a full copy of the base OS and
[more](https://wiki.freebsd.org/VIMAGE/Linux/CentOS55) can run in
isolation, hence the title jail. Over the years jail has grown new
features such as the ability to nest jails within each other,
creating a [Matryoshka doll](https://en.wikipedia.org/wiki/Matryoshka_doll)
like effect with jails.
