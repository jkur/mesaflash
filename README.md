mesaflash
=========

Configuration and diagnostic tool for Mesa Electronics PCI(E)/ETH/EPP/USB/SPI boards

Quickstart:
-----------

From the top level directory, switch to the source directory:

  cd mesaflash

In the source directory, install dependency and build:

  sudo apt-get install libpci-dev
  make

to get command line syntax:

  ./mesaflash --help


Build Debian Package
--------------------

Building a Debian package quick and dirty in place:

  gbp buildpackage --git-ignore-new --git-upstream-branch=master --git-upstream-tree=BRANCH

TODO: make the package debian compatible (upstream branch, etc.)
