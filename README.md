# Installers

This repository hosts one-line install scripts that you can download without
signing in. Run each script with the prerequisites listed in the app's install guide.

## PersoDB

- [Linux x86-64 script](persodb/install_from_github.sh)
- [Windows x86-64 script](persodb/install_from_github.ps1)

The scripts fetch the latest stable PersoDB setup and its SHA-256 manifest
by default. Use `--beta` (`-b`) or `--release-candidate` (`-rc`) to install
the latest release in that channel as PersoDB Preview.
Run `gh auth login` with an account that can access the private PersoDB releases,
then follow the install command for your platform. [PersoDB installation guide](https://github.com/HisQu/persodb#1-install-or-update-persodb)
