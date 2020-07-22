# Awesome Code Signing

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

This list contains a bunch of helpfull resources related to Code signing. E.g. Docker Content Trust and Notary.

## Presentations

* [Intro TUF/Notary - Justin Cappos, NYU & Justin Cormack, Docker](https://www.youtube.com/watch?v=76S7ZAwM0h4) - Introduction to TUF and Notary which implements TUF
* [Introduction to Notary - Justin Cormack, Docker](https://www.youtube.com/watch?v=Hnzc6va4l6k) - Introduction to Notary
* [A Docker Image walks into Notary - Diogo Mónica](https://www.youtube.com/watch?v=JvjdfQC8jxM) - Howto use notary in conjunction with Docker

## Articles / Blogs

* [Guarding against supply chain attacks—Part 3: How software becomes compromised](https://www.microsoft.com/security/blog/2020/03/11/guarding-against-supply-chain-attacks-part-3-how-software-becomes-compromised/)
* [Signing Docker images using Docker Content Trust](https://marcofranssen.nl/signing-docker-images-using-docker-content-trust/) - Howto use Docker Content Trust to sign your images

## Repositories

* [The Update Framework - Specification](https://github.com/theupdateframework/specification) - The Update Framework specification
* [The Update Framework - Notary](https://github.com/theupdateframework/notary) - A Go implementation of TUF
* [Docker - CLI](https://github.com/docker/cli) - Contains the `docker trust` cli implementation
* [DCT Notary admin](https://github.com/philips-labs/dct-notary-admin) - A tool to manage signing certificates and TUF delegations.
* [CNAB.io - Signy](https://github.com/cnabio/signy) - Implementation of CNAB security spec using Notary and in-toto
* [in-toto - in-toto](https://github.com/in-toto/in-toto) - Framework to protect integrity of software supply chain

## PGP

* [Keybase GPG Git](https://github.com/pstadler/keybase-gpg-github) - Guide to manage gpg with keybase and setup Git commit signing
* [Backup your PGP keys with GPG](https://msol.io/blog/tech/back-up-your-pgp-keys-with-gpg/) - Blog explaining backup and restore of PGP keys
