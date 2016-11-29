Emerald integration/staging tree
================================

http://EmeraldCrypto.de

Copyright (c) 2009-2014 Bitcoin Developers
Copyright (c) 2011-2014 Litecoin Developers
Copyright (c) 2016- Emerald Developers

What is Emerald?
----------------

Emerald - a fork of Litecoin. Like Litecoin it uses scrypt as a proof of work scheme.

	- Total coins will be 31,499,000.
	- 20 seconds block target
	- Difficulty retargets every hour* (see hardfork info below)
	- 5 emerald per block, halves every 2 block years (3,110,400 blocks)
	- transaction 3 confirmations, which average 1 min.
	- Start 0 emeralds for the first 400 blocks (except 1st block which is used for bounty etc), then 300 blocks each for 1, 2, 3 and 4 emeralds. Starting block 1601 will be 5 emeralds per block. This is to ensure fair start.
	- The default ports are 12127(connect) and 12128(json rpc).
	
---------

Hardfork at block 1600000 to implement Dark Gravity Wave 3. Difficulty will retarget every block instead of 180. 

New checkpoint added.



For more information, as well as an immediately useable, binary version of
the Emerald client sofware, see http://EmeraldCrypto.de

License
-------

Emerald is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.


The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/Crypto-Currency/Emerald/tags) are created
regularly to indicate new official, stable release versions of Emerald.

