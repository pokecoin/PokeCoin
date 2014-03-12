# Pokécoin [POKÉ] Integration/Staging Tree
http://pokecoin.info/ (website to come)

## What is PokéCoin?
Pokécoin is like Bitcoin, but based on Litecoin, and much more.
http://pokecoin.info/

## License
PokéCoin is released under the terms of the MIT license. See [COPYING](COPYING)
for more information or see http://opensource.org/licenses/MIT.

## Development and contributions
Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

## Frequently Asked Questions
no questions have been asked yet... wow!

### How much poké can exist?
To be calculated

### How to get poké?
Scrypt Proof of Work

1 Minute 30 seconds Block Targets, 1 Hour Diff Readjustments

Special reward system: Random block rewards

Blocks				Reward (Poké)
1-100,000			0-500,000

100,001-200,000		0-250,000

200,001-300,000		0-125,000

300,001-400,000		0-62,500

400,001-500,000		0-31,250

500,001-700,000		0-15,625

700,001+			5,000 (flat)

### pokécoind

    sudo apt-get install build-essential \
                         libssl-dev \
                         libdb5.1++-dev \
                         libboost-all-dev \
                         libqrencode-dev \
                         libminiupnpc-dev

    cd src/
    make -f makefile.unix USE_UPNP=1 USE_IPV6=1 USE_QRCODE=1

### Ports
RPC 22555
P2P 22556
