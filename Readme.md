# BitCard Google Chrome Extension
Bitcard enables Coinbase users to instantly use their bitcoins to purchase items on non-Bitcoin websites. 

This repository contains the code used in our Google Chrome extension.

Winner of the Capital One HackMIT 2016 prize for best use of their [Nessie API](http://api.reimaginebanking.com).
Also check out our [Devpost Submission](http://devpost.com/software/bitcard-backend).
## How it works
1. When initializing,
    1. Initializes OAuth2.0 Login to Coinbase
    1. Provides customer Info to [Capital One's Nessie API](http://api.reimaginebanking.com)
1. When making a purchase,
    1. Instantly sends a specified amount of Bitcoin from your Coinbase account to ours
    2. Provides a virtual VISA card # on demand, loaded with the specified amount of BTC in USD
    

## How to use
Unfortunately, the Capital One Nessie API does not allow for real transactions. But, if you still want to try it out:
1. `git clone` this repository
1. Load this folder into Google Chrome via the extension developer tools
1. Enjoy!

_Note that all transactions will NOT generate a usable card number and instead will be considered as donations. Thank you!_