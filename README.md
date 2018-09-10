# gitian.sigs
This repository is for deterministic build results for AXE releases. It should be updated on each release.

See the [release process](https://github.com/AXErunners/axe/blob/master/doc/release-process.md)
in the AXE repository for how to
deterministically build binaries and then pgp-sign them.

If you have 2FA on your github account, you'll need an auth token to push your sigs from within the vagrant VM. Another way is to copy them into a clone of this repo on your local computer before pushing:

`vagrant scp :/home/vagrant/gitian.sigs/v1.1.5 ~/axerunners/gitian.sigs/`

[Instructions for setting up a virtual machine](https://github.com/AXErunners/axe/blob/master/doc/gitian-building.md) in which you can
gitian build can also be found there.
