# Summarize

## x) 2.5 communications using public key cryptography
  - In 1976 Hellman and Diffie described public-key cryptography, which enables encryption via public key, and decryption via private key. This was compared to a locked mailbox.
    Anyone can put mail in, but it is very hard to gain access to the letters without the key of the mailbox.
  - Solves the problem of having to decide on a key beforehand or in secret.
  - In most cases public key cryptography is used to secure and distribute session keys which are used in the session and then discarded after.

## 2.6 Digital Signatures
  - Signing documents with public key cryptography solves the problems of pen-to-paper signatures, although they are still the standard when evaluating ownership.
  - Signatures are compelling since they are usually hard to tamper with, or the consequences of tampering with them are usually severe.
  - One of the first proposed applications was to monitor other countries nuclear tests through seismometer data.

## 2.7 Digital Signatures with Encryption
  - Using two different encryptions, two different algorithms or timestamps provide security in digital signing.

## 2.8 Random and Pseudo-Random Sequence Generation
  - There is no truly random within the world of computers.
  - Best you can get is a pseudo-random sequence which: looks random, is unpredictable, and cannot be reproduced. This is referred to as "Real random".

## Chapter 2. Cryptographic hash functions and digital signatures
  - You can derive the public key from a private key but not the other way around, it is a one-way function.
  - Cryptographic hash functions which are used to verify signatures or encrypt messages, are also one-way functions.

# Pubkey today

I've used public key cryptography today by entering a https:// website. Let's take the Cloudflare source I reference here as an example. The website has a SSL/TLS certificate (public key) and a private key in its server. When trying to connect to the website,
a "TLS handshake" occurs. When this happens, the server and the client connecting decide on which version of TLS they use, decide on the cipher suites, authenticate the server via digital signature and public key, and generates the session keys used after the authentication.
After authenticating the server, the client sends a string of bytes encrypted with the server's public key (which was authenticated) so that the server can decrypt it with its private key.
(https://www.cloudflare.com/learning/ssl/what-happens-in-a-tls-handshake/)

# Messaging
Encrypted a message using an online PGP tool. Tried sending emails between two of my old email addresses. Couldn't get it to work.

# Other tool
Tried installing Kleopatra on Virtual Linux and then simulated messaging with two folders and it succeeded. The software was hard to install as a windows user, but it worked fine when I got it running. I think the method's security is good, but all of the keys were
in the same software, so that might present a risk as they weren't scattered in multiple places.

# Eve and Mallory
The security of the system is based on the privacy of the private keys. If Mallory ever gets hold of someone's private key, the system collapses. Don't know how Eve could be able to eavesdrop in through the PGP protocol. The protocol is extremely secure
# References

Tero Karvinen. Trust to Blockchain 2024.
https://terokarvinen.com/trust-to-blockchain/

Schneier 2015: Applied Cryptography: Chapter 2 - Protocol Building Blocks, sections
https://learning.oreilly.com/library/view/applied-cryptography-protocols/9781119096726/10_chap02.html#chap02-sec008

Rosenbaum 2019: Grokking Bitcoin
https://learning.oreilly.com/library/view/grokking-bitcoin/9781617294648/OEBPS/Text/kindle_split_011.html#ch02lev1sec1

Cloudflare. How does public key cryptography work?
https://www.cloudflare.com/learning/ssl/how-does-public-key-encryption-work/

Cloudflare. What happens in a TLS Handshake? | SSL Handshake
https://www.cloudflare.com/learning/ssl/what-happens-in-a-tls-handshake/

Michael Bugbee. What is PGP Encryption and how does it work?
https://www.varonis.com/blog/pgp-encryption

PGP Tool
https://pgptool.org/
