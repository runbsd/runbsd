### HardenedBSD
HardenedBSD started in 2014 as a "spork" of FreeBSD. It's not a
traditional fork in that it syncs with upstream FreeBSD every six
hours. HardenedBSD implements exploit mitigations and system hardening
technologies, with an initial goal of porting the grsecurity Linux
patchset.

To date, HardenedBSD has implemented PaX ASLR, PaX NOEXEC, grsecurity
TPE, non-Cross-DSO-CFI, SafeStack, among various other enhancements.
The HardenedBSD core team actively tests on amd64 and arm64.
