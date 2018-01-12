# My Learning Place for Ethereum
---

+ `solcjs` is a Solidity compiler, but has less features than other Solidity compilers.

+ `solc` is a good compiler installed through PPA's (Personal Package Archive) on Ubuntu.

+ An update to date docker build for the compiler: `docker run ethereum/solc:stable solc --version`. Currently, the docker image only contains the compiler executable, so you have to do some additional work to link in the source and output directories.
