# Rewind - A termux backup/restore tool


Simple bash script to backup and
restore home directory and packages installed manually.
Works across devices.

![rewind](rewind.png)


### created by [trhacknonimous](https://github.com/trhacknonimous)

## Installation

Just copy paste this in your termux.


```bash
wget https://raw.githubusercontent.com/trhacknonimous/TermBack/master/rewind && chmod u+x rewind && mv rewind $PREFIX/bin/
```

or

```bash
curl -O https://raw.githubusercontent.com/trhacknonimous/TermBack/master/rewind && chmod u+x rewind && mv rewind $PREFIX/bin/
```

## Usage

Usage : **rewind**  [-hv] [-b|-r [home|pkgs]]

option           |   Description
:---------------:|:---------------------------:
 -h              |    print this usage
 -v              |    print version
 -b [home\|pkgs] |    backup home and/or packages
 -r [home\|pkgs] |    restore home and/or packages
