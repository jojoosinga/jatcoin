Jatcoin integration/staging tree
================================


Copyright (c) 2009-2014 Bitcoin Developers
Copyright (c) 2019-2020 Jatcoin Developers



Info
---------------

This is the first node 64.225.64.154
and the block explorer http://167.71.73.163:3001/

What is Jatcoin?
----------------

Jatcoin is a lite version of Bitcoin using scrypt as a proof-of-work algorithm.
 - 2.5 minute block targets
 - subsidy halves in 840k blocks (~4 years)
 - ~350000 total coins

The rest is the same as Bitcoin.
 - 20 coins per block
 - 2016 blocks to retarget difficulty
 
 
 
 Installing
 ----------
 How to install this wallet
 
 Windows
         run the EXE
         
Mac OSX
         run the .app

Linux    
```git clone https://github.com/jojoosinga/jatcoin.git
         cd jatcoin
         cd src
         make -f makefile.unix
         ./jatcoind

```
Linux-qt
``` git clone https://github.com/jojoosinga/jatcoin.git
         cd jatcoin
         qmake
         make
         ./jatcoind-qt
```

License
-------

Jatcoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------

Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the Jatcoin
development team members simply pulls it.

If it is a *more complicated or potentially controversial* change, then the patch
submitter will be asked to start a discussion with the devs and community.

The patch will be accepted if there is broad consensus that it is a good thing.
Developers should expect to rework and resubmit patches if the code doesn't
match the project's coding conventions (see `doc/coding.txt`) or are
controversial.

