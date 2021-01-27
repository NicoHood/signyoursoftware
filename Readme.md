# Sign your Software

## Secure your software releases by adding digital signatures.

### What is signed Software?

Digital signatures can be used to digitally sign software using public-key cryptography.
A valid digital signature can be used to confirm the authenticity of the issuer and thus the integrity of the software.
The most common software used to create digital signatures is GPG.

### Why sign your Software?

Digitally signed software prevents attackers from manipulating your software on the way between you and the user.
For example, by hacking the web space or manipulating the transport (download) of your software.

### Who needs signed Software?

Digital signatures are not only important for security-conscious users, but especially for software packagers.
The packaged software is distributed to a large number of users, therefore the security of the software is especially important.

### What do I need to do to sign my Software?

* Create and/or use a 4096-bit RSA/Ed25519 ECC keypair for the file signing
* Use a strong, unique, secret passphrase for the key
* Upload the public key to a key server and publish the full fingerprint on your project site
* Sign every new Git commit and tag
* Create signed, compressed release archives
* Upload a strong message digest of the archive
* Configure HTTPS for your download server

### How can I sign my Software?

Signing your software is as easy as making a git commit.

We recommend that you work through the entire process once manually and then integrate it into your workflow using automated tools.

* [GPG Quick Start Guide](https://github.com/NicoHood/gpgit#gpg-quick-start-guide) (manual)
* [GPGit Script](https://github.com/NicoHood/gpgit) (automated)

### What are the risks of unsigned Software?

### Frequently Asked Questions

#### Which popular projects already use digital signatures?

#### Which projects have been compromised in the past?

#### Aren't Github projects already sufficiently secured?


#### Can I use my GPG key for email encryption as well?

#### Does it matter for my (small) project?

#### Where do I get help?

#### How can I contribute?

### What are you waiting for? Sign your software now!
