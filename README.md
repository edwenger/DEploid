
<img src="docs/_static/deploid.png" width="180">


[![License (GPL version 3)](https://img.shields.io/badge/license-GPL%20version%203-brightgreen.svg)](http://opensource.org/licenses/GPL-3.0)
[![Build Status](https://travis-ci.org/mcveanlab/DEploid.svg?branch=master)](https://travis-ci.org/mcveanlab/DEploid)
[![CircleCI](https://circleci.com/gh/mcveanlab/DEploid.svg?style=shield)](https://circleci.com/gh/mcveanlab/DEploid)
[![Coverage Status](https://coveralls.io/repos/github/mcveanlab/DEploid/badge.svg)](https://coveralls.io/github/mcveanlab/DEploid)
[![Documentation Status](http://readthedocs.org/projects/deploid/badge/?version=latest)](http://deploid.readthedocs.io/en/latest/)

`dEploid` is designed for deconvoluting mixed genomes with unknown proportions. Traditional ‘phasing’ programs are limited to diploid organisms. Our method modifies Li and Stephen’s algorithm with Markov chain Monte Carlo (MCMC) approaches, and builds a generic framework that allows haloptype searches in a multiple infection setting.

Please see the [documentation](http://deploid.readthedocs.io/en/latest/) for further details.

Installation
------------

You can also install `dEploid` directly from the git repository. Here, you will need `autoconf`, check whether this is already installed by running:
```bash
$ which autoconf
```

On Debian/Ubuntu based systems:
```bash
$ apt-get install build-essential autoconf autoconf-archive libcppunit-dev
```

On Mac OS:
```bash
$ port install automake autoconf autoconf-archive cppunit
```

Afterwards you can clone the code from the github repository,
```bash
$ git clone git@github.com:mcveanlab/DEploid.git
$ cd DEploid
```

and build the binary using
```bash
$ ./bootstrap
$ make
```

Usage
-----

Please see the [documentation](http://deploid.readthedocs.io/en/latest/) for further details.


Licence
-------

You can freely use all code in this project under the conditions of the GNU GPL Version 3 or later.


Citation
--------

If you use `dEploid` in your work, please cite the program:

Zhu, J. S. J. A. Garcia G. McVean. (2017) Deconvoluting multiple infections in *Plasmodium falciparum* from high throughput sequencing data. *bioRxiv* 099499. doi: https://doi.org/10.1101/099499


