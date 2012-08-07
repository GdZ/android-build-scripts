About
=====

Personal scripts for working with Android at Linaro

Requirements
============

Currently the script assumes that you have repo and other host prerequisites
for android. It has been tested on Ubuntu 12.04 and Ubuntu 10.04

Usage
=====

Once you are good to go run this:

```
$ git clone git://github.com/zyga/android-build-scripts.git
$ cd android-build-scripts
$ make CONFIGURATION=panda-ics-gcc47-tilt-tracking-blob sync
$ make CONFIGURATION=panda-ics-gcc47-tilt-tracking-blob all -j 8
```

To flash that to a bootable SD card run:

```
$ make CONFIGURATION=panda-ics-gcc47-tilt-tracking-blob flash
```

To start a development shell

```
$ make CONFIGURATION=panda-ics-gcc47-tilt-tracking-blob shell
```
