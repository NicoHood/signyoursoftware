# Sign your Software

## Secure your software releases by adding digital signatures.

### What is signed Software?
Option 1:
Digital signatures can be used to digitally sign software using public-key cryptography.
A valid digital signature can be used to confirm the authenticity of the issuer and thus the integrity of the software.
The most common software used to create digital signatures is GPG.
     
Option 2:
Signed software carries a unique digital signature of the developer. This signature can be used by anyone at any time to verify that the software actually originated from the developer.

### Why sign your Software?
Option 1:
Digitally signed software prevents attackers from manipulating your software on the way between you and the user.
For example, by hacking the web space or manipulating the transport (download) of your software.
     
Option 2:
A lot of things can go wrong when distributing your software. File errors can occur during download. Malware can attach itself to your software. Someone else can offer your software for download on their homepage but with different content. With a signature you ensure that it can be checked whether the software is also from you.

### Who needs signed Software?
Option 1:
Digital signatures are not only important for security-conscious users, but especially for software packagers.
The packaged software is distributed to a large number of users, therefore the security of the software is especially important.
     
Option 2: 
You. Me. Everyone. Signed software secures the supply chain from developer to end user. In popular Linux distributions, your software can be securely included and then rolled out to thousands of end users.

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
 * technical error at download
 * malware attached to downloaded files
 * manipulated software

### Frequently Asked Questions

#### Which popular projects already use digital signatures?
VLC, Firefox, Thunderbird, Linux Kernel, etc... https://github.com/WoLpH/python-progressbar

#### Which projects have been compromised in the past?
{link_to "Canonical Github Account hacked (2019)", canonicalhack}
{link_to "Gentoo Github Account hacked (2018)", gentoohack}
{link_to "Handbrake server compromised (2017)", handbrakehack}
{link_to "Linux Mint hacked ISOs (2016)", linuxminthack}
Do you know of any other examples? Let us know!

#### Aren't Github projects already sufficiently secured?
As seen as in 'Which projects have been compromised in the past?', also github accounts had been hacked. Even with a hacked Github account but signed software, you can verify that the software is detached from this hack. 

#### Can I use my GPG key for email encryption as well?
Yes. Especially if you have been planning to set up email encryption for a long time, now is the right time. By setting up a PGP key, you can sign your software and encrypt your emails from now on. 

#### Does it matter for my (small) project?
 Yes. I matters for all projects. 

#### Where do I get help?
 Here you can find a [github discussion](https://github.com/NicoHood/signyoursoftware)
 link sammlung (google https reasons)
 npm imaginaere hacker story -> passt das?
    
#### How can I contribute?
You can find this github project [here](https://github.com/NicoHood/signyoursoftware)

### What are you waiting for? Sign your software now!
