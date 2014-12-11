# Build Guide

## Announcement

I only have built it on Ubuntu. It should works on Debian, you have to install dependency by your-
self. If you have successfully built this on another distro, please share your build note.

## Install dependency

``` shell
# apt-get install gcc build-essential autoconf automake libncurses-dev texinfo byacc flex
```

## Build

``` shell
$ ./autogen.sh
$ ./configure
$ make # this will fail, but it's normal.
$ make htdoc.h
$ make
# make install # optional, if you want `hte` available system-wide
```
