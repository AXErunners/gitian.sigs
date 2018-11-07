# gitian.sigs
This repository is for deterministic build results for AXE releases. It should be updated on each release.

See the [release process](https://github.com/AXErunners/axe/blob/master/doc/release-process.md) in the AXE repository for how to deterministically build binaries and then sign them.

If you have 2FA on your GitHub account, you will need an auth token to push your sigs from within the Vagrant VM. Another way is to copy them into a clone of this repo on your local machine before with [vagrant scp](https://github.com/AXErunners/axe-gitian#copying-files) plugin.
