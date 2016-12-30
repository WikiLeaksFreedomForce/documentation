# WLFF documentation

Documentation, todos, leads to follow


## Non-coder TODOs

- [ ] Obtain the WL insurance files and check their SHA256 hashes against our list of reference hashes
    - See [this file](https://github.com/WikiLeaksFreedomForce/documentation/blob/master/insurance-files/sha256-hashes.md) for more information.
- [ ] Run `binwalk` on all of the WL insurance files
    - Get binwalk here: <https://github.com/devttys0/binwalk/>
- [ ] Search for interesting transaction chains
    - Use our [local-blockchain-parser](https://github.com/WikiLeaksFreedomForce/local-blockchain-parser)'s `tx-chain` command.  The command will find chains, run an analysis on all of the transactions in a given chain, and output a folder containing the results and the list of transactions.  Add that folder to this repo when you find an interesting chain.

