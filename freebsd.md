### FreeBSD
Forked from the Net/2 & 386BSD code base, 6 months after NetBSD was started.
The focus of FreeBSD was performance on i386 systems. Over time support was
added for the DEC Alpha as this meant porting the code base to a 64bit systems
and addressing any bugs which would prevent the code base from running on a
64bit system. Many years later the project branched out and introduced support
for additional platforms. Today the project boasts support for CPUs such as
ARMv8, [RISC-V](http://riscv.org/) and
[BERI](http://www.cl.cam.ac.uk/research/security/ctsrd/beri/).

FreeBSD is the home to many innovations, such as

#### Ports
Ports is a framework for building software. It abstracts away different build
systems to provide a common workflow to the user, regardless of the software
being built and installed. Developers and contributors create recipes to install
different pieces of software. Recipes or ports as they called contain such
information as where the source code is hosted, which dependencies the software
requires to build and run, patches to ensure the software integrates correctly
with the operating system. The port for each piece of software are stored in
individual directories of their own, organised under directories named after
categories.  For a user to build and install one of these packages they would
change into the relevant directory & run make install.  The system would then
evaluate what is required and what is already present on the system being built
on and proceed to build and install any dependencies before embarking on
building the requested piece of software.  This can be a time consuming process
depending on the system being built on but binary packages are of course offered
as standard, allowing this process to be bypassed entirely unless desired.
