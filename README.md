freecoin integration/staging tree
================================

http://www.freecoin.org

Copyright (c) 2009-2014 Bitcoin Developers
Copyright (c) 2011-2014 Litecoin Developers
Copyright (c) 2017 Freecoin Developers

What is freecoin?
----------------

freecoin is a test version of Litecoin using scrypt as a proof-of-work algorithm.
 
The rest is the same as Litecoin with small modifications such as the genesis block.

For more information, as well as an immediately useable, binary version of
the freecoin client sofware, see http://.

License
-------


Development process
-------------------


Testing
-------


### Automated Testing


Unit tests for the core code are in `src/test/`. To compile and run them:

    cd src; make -f makefile.unix test

Unit tests for the GUI code are in `src/qt/test/`. To compile and run them:

    qmake BITCOIN_QT_TEST=1 -o Makefile.test bitcoin-qt.pro
    make -f Makefile.test
    ./freecoin-qt_test

