---
title: Frequently Asked Questions
# TODO add links to heise.de news for german translation
---

### Frequently Asked Questions 

#### Which popular projects already use digital signatures?

* [Linux Kernel](https://www.kernel.org/signature.html)
* [VLC Media Player](https://download.videolan.org/pub/videolan/vlc/)
* [Firefox](https://archive.mozilla.org/pub/firefox/releases/)
* [Libre Office](https://download.documentfoundation.org/libreoffice/src/)
* [Arduino IDE](https://github.com/arduino/Arduino/releases)

#### Which projects have been compromised in the past?

* [Perl.com Domain Hijacking (2021)](https://heise.de/-5043116)
* [Canonical Github Account hacked (2019)](https://www.zdnet.com/article/canonical-github-account-hacked-ubuntu-source-code-safe/)
* [Gentoo Github Account hacked (2018)](https://wiki.gentoo.org/wiki/Project:Infrastructure/Incident_Reports/2018-06-28_Github)
* [Handbrake server compromised (2017)](https://forum.handbrake.fr/viewtopic.php?f=33&t=36364)
* [Linux Mint hacked ISOs (2016)](https://blog.linuxmint.com/?p=2994)

Do you know of any other examples? [Let us know!](https://github.com/NicoHood/signyoursoftware/issues/new)

#### Aren't Github projects already sufficiently secured?

Yes and no. It may be less likely that Github servers will be successfully attacked, but it is definitely not impossible that individual Github accounts will be hijacked. The above listing shows very clearly that this can happen even to very reputable projects, so you'd better not rely on it.

#### Does it matter for my (small) project?

As soon as your software is used by other users, it makes sense to secure it accordingly. It doesn't matter if the software is a complex GUI program, a simple script, theme or anything else. Even supposedly "unimportant" projects can cause serious damage to users if malicious files with system privileges are installed.

#### Are hashes (SHA256, SHA1, MD5) sufficient?

No. Hashes only ensure the integrity of the software, but never its authenticity.

#### Can I use my GPG key for email encryption as well?

Yes. Especially if you have been planning to set up email encryption for a long time, now is the right time. By setting up a GPG key, you can sign your software and encrypt your emails from now on.
