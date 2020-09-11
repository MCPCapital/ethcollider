2020 Updated Ethereum Collider 
==============================================================

The Ethereum Collider, origonally developed by Trent Pierce, is a python script created to repeatedly create ethereum wallet addresses in search of a match.
The collider first creates an address and private key. Next it sends a request to etherscan.io to check for a balance. 
If the balance is 0, the collider loops back to the top and restarts this process. If a balance is found, the program 
will stop and print the address, private key, and balance.

* Pure Python code
* Cross-platform code
* No-dependencies
* Generates addresses quickly


Using Ethereum Collider
===============================================================

You need Python 2.7 (not tested on 3.x).

Just launch ethcollider.py to begin generating addresses and their private keys; and checking them for balances in etherscan.

The console will update as addresses are generated. If you find a match, the program will stop and print out
the wallet balance, address, and private key.


Random source for key generation :

* CryptGenRandom in Windows
* /dev/urandom   in Unix-like


If you like this program, and would like me to continue development, please send a donation to this address:
N/A

License :
----------
This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, version 3 of the License.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
# ethcollider
