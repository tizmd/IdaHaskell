# IdaHaskell

Allows to execute haskell code in Ida Pro.

![alt text](https://raw.githubusercontent.com/kvnesterov/IdaHaskell/master/screenshot.png "Example")


### Requirements
* Windows version of Ida Pro (tested on version > 6.5)
* Haskell Platform (tested on HaskellPlatform-7.10.3-i386) or ghc(tested on 7.10.2) + cabal

### Build
* Copy your idasdk into cabal directory with name idasdk
* Set env variable IDA_PATH to your Ida Pro installation
* cabal build
* cabal install
* suffer
