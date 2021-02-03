---
title: Security Threats
---

### When is signed software helpful, when not?

Signed software can significantly reduce the damage caused by infiltrating malicious software. Here you will find the most common attack scenarios, against which signed software does and does not help.

#### ✓ Server/Mirror Hack

The most obvious attack to spread manipulated software is to hack the software download server or its mirrors. Package maintainers who already know your GPG key will notice the manipulated software when checking its GPG signature.

#### ✓ User Account Hack

Even if you are already using a reasonably secure server (e.g. Github), it is still possible for an attacker to gain access to your user account. An attacker can then inject malicious code into your Git repository and create new software releases.

#### ✓ Man-in-the-Middle-Attack

A more complex and less likely way to inject tampered software is to manipulate the up- or download to/from the server. For example, a so-called man-in-the-middle intercepts an unsecured upload (ftp) or download (http). That' s why it is so [important to use additional secure protocols (https, ssh, etc.) for up- and downloading software.](https://web.dev/why-https-matters/)

#### ✗ Leaking the private GPG key

It is very important to keep your GPG key private. Make sure to use a strong passphrase and never publish it on untrusted devices or external servers. If the initial GPG key exchange is intercepted (by one of the threats above), the user likewise has no chance to verify the software authenticity.

#### ✗ Security issues within the software itself

Of course, digital signatures do not protect against vulnerabilities in the software itself [(or its dependencies).](https://medium.com/hackernoon/9a8cb347c5b5) Make sure you trust the publisher of the software and review any code changes e.g. through an independent security audit.
