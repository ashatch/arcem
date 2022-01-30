# arcem

This is a clone/fork of [arcem on sourceforge](http://arcem.sourceforge.net) just so I can build and run it on Mac OSX on whatever version I happen to be running.

## Build

```bash
make clean arcem
```

## Getting ready to Run it

### Prerequisites

Requires XQuartz to be running. The most convenient way of installing is:

```bash
brew install --cask xquartz
```

This will install XQuartz as an application. Run this first before launching `arcem`.

### ROM

You will need a RISCOS rom file. Obtain one (legally), name it `ROM` and keep it in the project root. It is ignored by `git`.

### Hard Disk Image

Unzip the blank disk image in `hdd-images` and move `HardImage1` to the project root.

Copy `arcemrc` to your home folder as `.arcemrc`:

```bash
cp arcemrc ~/.arcemrc
```

## Run arcem

```bash
DISPLAY=:0 ./arcem
```
