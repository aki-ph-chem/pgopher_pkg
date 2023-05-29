# pgopher_pkg

pgopher_pkg is a project that provides a script to build a package for Arch Linux x86_64 
specifically for [pgopher](https://pgopher.chm.bris.ac.uk), a program used for rotational, vibrational, and electronic spectra.

## Installation

1. Install the dependencies:

```bash
$ sudo pacman -S base-devel
```

2. clone thid project:

```bash
$ git clone  git@github.com:aki-ph-chem/pgopher_pkg.git # by SSH   
$ git clone  https://github.com/aki-ph-chem/pgopher_pkg.git # by HTTPS 
```

3. build & install package:

build package:

```bash
$ cd pgopher_pkg/pgopher_pacman
$ makpkg -s 
```

install package:

```bash
$ sudo pacman -U *.pkg.tar.zst
```

## LICENSE

This project is lincensed under GPL.
