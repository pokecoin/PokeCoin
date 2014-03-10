# Pokécoin [POKÉ, Ð] Integration/Staging Tree
http://pokécoin.com/ (website to come)

## What is PokéCoin?
Pokécoin is like Bitcoin, but based on Litecoin, and also much more wow.
http://pokécoin.com/

## License
PokéCoin is released under the terms of the MIT license. See [COPYING](COPYING)
for more information or see http://opensource.org/licenses/MIT.

## Development and contributions
Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

## Frequently Asked Questions

### How much poké can exist?
To be calculated

### How to get poké?
Scrypt Proof of Work

1 Minute Block Targets, 4 Hour Diff Readjustments

Special reward system: Random block rewards

1-100,000: 0-1,000,000 Pokécoin Reward

100,001 — 200,000: 0-500,000 Pokécoin Reward

200,001 — 300,000: 0-250,000 Pokécoin Reward

300,001 — 400,000: 0-125,000 Pokécoin Reward

400,001 — 500,000: 0-62,500 Pokécoin Reward

500,001 - 600,000: 0-31,250 Pokécoin Reward

600,000+ — 10,000 Reward (flat)

### Wow plz make pokécoind

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
