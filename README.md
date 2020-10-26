This a Debian repository for the RAT project. This repository is to be used with Debian bullseye and later.

To use, run the following a root:

```sh
echo "deb https://samangh.github.io/rat bullseye main" >> /etc/apt/sources.list
apt-key adv --keyserver "hkps://keys.openpgp.org" --locate-key saman@saman-gh.co.uk
apt update
```

If you are interested in seeing what packages are available from this repository, run

```sh
grep Package /var/lib/apt/lists/samangh.github.io_rat_dists_bullseye_main_binary-amd64_Packages
```
