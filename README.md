# RAT project repository

This is a Debian repository for the [RAT (Rot A in Tesla)
project](https://gitlab.com/Project-Rat), an open source software for
modelling coil geometries and their respective field calculation.

This repository can be used with Debian `bullseye` and later (as well as
Ubuntu, Mint equivalents, etc).

## Installation

To user this repository, run the following a root:

```sh
echo "deb https://samangh.github.io/rat bullseye main" >> /etc/apt/sources.list
apt-key adv --keyserver "hkps://keys.openpgp.org" --locate-key saman@saman-gh.co.uk
apt update
```

To list the packages available from this repository, run

```sh
grep Package /var/lib/apt/lists/samangh.github.io_rat_dists_bullseye_main_binary-amd64_Packages
```

To install a package (for example `libratmodels`), run as root:

```sh
apt update
apt install libratmodels
```

## Source

The GitHub repository behind this site be browsed at
[https://github.com/samangh/rat](https://github.com/samangh/rat)

## Acknowledgments

The RAT libraries are written by Jeroen van Nugteren. Debian packages
created by Saman Ghannadzadeh.
