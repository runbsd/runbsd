<a href="/" title="home"><img src="/header.png" class="w3"></a>

# HardenedBSD

[HardenedBSD] is a derivative of FreeBSD, officially founded in 2014,
that implements exploit mitigations and security hardening
technologies. The primary goal of HardenedBSD is to perform a
clean-room re-implementation of the grsecurity patchset for Linux to
HardenedBSD.

Work on HardenedBSD began in 2013 when Oliver Pinter and Shawn Webb
started working on an implementation of Address Space Layout
Randomization (ASLR), based on PaX's publicly-available documentation,
for FreeBSD. At that time, HardenedBSD was meant to be a staging area
for experimental development on the ASLR patch. Over time, as the
process of upstreaming ASLR to FreeBSD became more difficult,
HardenedBSD naturally became a fork.

HardenedBSD completed its ASLR implementation in 2015 with the
strongest form of ASLR in any of the BSDs. Since then, HardenedBSD has
moved on to implementing other exploit mitigations and hardening
technologies. OPNsense, an open source firewall based on FreeBSD,
incorporated HardenedBSD's ASLR implementation in 2016.

## Features

HardenedBSD has successfully implemented the following features:

- PaX-inspired ASLR
- PaX-inspired NOEXEC
- PaX-inspired SEGVGUARD
- Base and ports compiled as Position Independent Executables (PIEs)
- Base and ports compiled with full RELRO (RELRO + BIND_NOW)
- Hardening of certain sensitive sysctl nodes
- Network stack hardening
- Executable file integrity enforcement
- Boot process hardening
- procs/linprocfs hardening
- LibreSSL as an optional crypto library in base
- Trusted Path Execution (TPE)
- Randomized PIDs
- SafeStack in base
- SafeStack available in ports
- Non-Cross-DSO CFI in base
- Non-Cross-DSO CFI available in ports
- Retpoline applied to base and ports

[HardenedBSD]: https://hardenedbsd.org/
