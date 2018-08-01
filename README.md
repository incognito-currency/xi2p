xi2p
====

xi2p (eXtended I2P daemon) is a full-featured C++ implementation of I2P client for Incognito currency.  

How to use xi2p (Only For Ubuntu)
-------
1. Download source code and build it.
$git clone https://github.com/incognito-currency/xi2p
$cd xi2p
$make
2. Copy contrib/tunnels.conf to ~/.i2pd/tunnels.conf
3. Execute xi2p
$./xi2p
4. Check Block explorer
$google-chrome-stable --proxy-server="http://127.0.0.1:4444"
Navigate to http://6uyecrdem23rxmsxshnbzpjhf5hkvfv6slxp7qezywoaxe2rahda.b32.i2p
5. Execute incognito-wallet-gui and connect to 127.0.0.1:39005
6. Enjoy your time.


License
-------

This project is licensed under the BSD 3-clause license, which can be found in the file
LICENSE in the root of the project source code. 
