<p><a href="/" alt="avatar" title="home page"><img src="sivers.jpeg" class="avatar"></a></p>

# Derek Sivers runs OpenBSD

The only operating system I use on my computers is [not Mac], not
Windows, and not even Linux. It's [OpenBSD], and I love it so much.

It's not for people who want to click a button and have the computer
hide the details from you.

If software bloat doesn't bother you &mdash; if every new
Mac/Windows/Linux release you say, "Bring on the features! The more
the better!" &mdash; it's not for you.

But if you're experienced, like to "look under the hood", and prefer
software that does the minimum necessary, OpenBSD is for you.

It's known for its focus on security. But, like a well-engineered
house will also be earthquake-proof, you don't have to be paranoid
about earthquakes to appreciate great construction. To me, the
security features are just a side-effect of [great coding].

OpenBSD comes with a secure minimal [firewall], [webserver],
[mailserver], and an optional graphical [desktop]. So if all you
want is a few of those things, you do the default install, tweak
one config file, and you're done.

It's **uncompromising**. It's not a people-pleaser or vendor-pleaser.
Linux is in everything from Android phones to massive supercomputers,
so has to include features for all of them. The OpenBSD developers
say no to most things. Instead of trying to make it do more, they
keep it focused on doing what it does with more security and
reliability.

They **review and remove** code as often as they add. If something
is unused, unmaintained, or unnecessary, they'll axe it. If it's
unwieldy, they'll make a **small simple replacement**. For examples,
see [doas], [OpenSMTPD], [httpd(8)], and [LibreSSL]. This is great
for security, too. The more code, the more chance of a bug that
could compromise your entire computer. The less code, the better.
Each new release seems to be getting leaner by removing old cruft.
No other operating system does that.

Great **documentation** is a top priority. The built-in [man pages]
are amazing. So if you're stuck on anything, searching the man pages
on your own computer is going to give you a better answer than
[searching] Google. (This makes it nicer to work offline, too.)

The **installers** are amazing. The [initial installation] takes
like five minutes. Hit [Enter] to the defaults, make your username
and password, and it's ready to go. Then the [software installer]
is ideal, too. Just [pkg_info(1)] to search for something and
[pkg_add(1)] to install it in seconds. (Which also installs all of
its documentation, too.)

Everything is rock-solid and **just works**. Hardware I couldn't
get working in Linux just works on a first try with OpenBSD. And
because they don't stay cutting-edge, keeping a cautious pace, it
keeps working and doesn't break. The whole system is carefully
planned and consistent, instead of a hodge-podge of bits and pieces.

It's all free and run by helpful volunteers. If you [searched ports],
but some application you need is missing or out of date, just contact
the maintainer and offer some assistance or money to help get it
updated or added. I've donated $3500 to the developers to help
improve the OpenBSD port of [Node.js], [Elixir], [Erlang], [Anki],
[Ledger], and [Qutebrowser].

Find me on [Twitter].

_8 Aug 2018_

[Anki]: https://apps.ankiweb.net/
[Elixir]: http://elixir-lang.org/
[Erlang]: http://www.erlang.org/
[Ledger]: http://www.ledger-cli.org/
[LibreSSL]: https://www.libressl.org/
[Node.js]: https://nodejs.org/
[OpenBSD]: https://www.openbsd.org/
[OpenSMTPD]: https://www.opensmtpd.org/
[Qutebrowser]: https://www.qutebrowser.org/
[Twitter]: https://twitter.com/sivers
[desktop]: http://www.xenocara.org/
[doas]: http://www.tedunangst.com/flak/post/doas
[firewall]: https://www.nostarch.com/pf3
[great coding]: https://www.openbsd.org/security.html
[httpd(8)]: https://man.openbsd.org/httpd.8
[httpd]: https://man.openbsd.org/httpd.8
[initial installation]: https://www.openbsd.org/faq/faq4.html
[mailserver]: https://www.opensmtpd.org/
[man pages]: https://en.m.wikipedia.org/wiki/Man_page
[not Mac]: https://sivers.org/itunes
[pkg_add(1)]: https://man.openbsd.org/pkg_add.1
[pkg_info(1)]: https://man.openbsd.org/pkg_info.1
[searched ports]: https://cvsweb.openbsd.org/cgi-bin/cvsweb/ports/
[searching]: https://man.openbsd.org/apropos.1
[software installer]: https://www.openbsd.org/faq/faq15.html
[webserver]: https://www.romanzolotarev.com/openbsd/httpd.html
