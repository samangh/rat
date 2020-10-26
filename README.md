# RAT project repository

This a Debian repository for the [RAT project](https://gitlab.com/Project-Rat). This repository can be used with Debian `bullseye` and later (and Ubuntu, Mint equivalents, etc).

To use, run the following a root:

```sh
echo "deb https://samangh.github.io/rat bullseye main" >> /etc/apt/sources.list
apt-key adv --keyserver "hkps://keys.openpgp.org" --locate-key saman@saman-gh.co.uk
apt update
```

To list the packages avilable from this repository, run

```sh
grep Package /var/lib/apt/lists/samangh.github.io_rat_dists_bullseye_main_binary-amd64_Packages
```

## Source

The GitHub repository behind this site be browsed at [https://github.com/samangh/rat](https://github.com/samangh/rat)

## Acknowledgments

The RAT libraries are written by Jeroen van Nugteren. Debian packages created by Saman Ghannadzadeh.
