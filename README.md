##What is Kratom?
Kratom is an open source peer-to-peer cryptocurrency.
https://kratom.pw/

##License
Kratom is released under the terms of the MIT license. See [COPYING](COPYING)
for more information or see http://opensource.org/licenses/MIT.

##Development and contributions
Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

##Rewards
Rewards are soft capped at 19,450,000,000. After that every block generate 500 IDC.<br>
1-500,000 = 20,000 IDC<br>
500,001-1,000,000 = 10,000 IDC<br>
1,000,001-1,500,000 = 5,000 IDC<br>
1,500,001-2,000,000 = 2,500 IDC<br>
2,000,001-2,500,000 = 1,400 IDC<br>
2,500,000+ = 500 IDC

##Specifications
Scrypt Proof of Work. 1 Minute Block Targets, 4 Hour Diff Readjustments.

##How to build `kratomd`
```bash
sudo apt-get install build-essential \
                     libssl-dev \
                     libdb5.1++-dev \
                     libboost-all-dev \
                     libqrencode-dev \
                     libminiupnpc-dev

cd src/
make -f makefile.unix USE_UPNP=1 USE_IPV6=1 USE_QRCODE=1
```
##Ports
RPC Port: 19451<br>
P2P Port: 19457<br>
-Testnet RPC: 19458<br>
-Testnet P2P: 19459<br>


Additional Linux Build Instructions:
https://bitcointalk.org/index.php?topic=3018550.msg31608461#msg31608461

