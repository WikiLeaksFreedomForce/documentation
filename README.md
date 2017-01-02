# WLFF documentation

Documentation, todos, leads to follow


## Non-coder TODOs

- [ ] Contact Peter Todd about finding verification of torrents and files using OpenTimestamp
- [ ] Find all copies of the WL torrent files on the internet and compare them to see if any appear to have been tampered with
- [ ] Try to verify our WL torrent files using OpenTimestamp
- [ ] Obtain the WL insurance files and check their SHA256 hashes against our list of reference hashes
    - See [this file](https://github.com/WikiLeaksFreedomForce/documentation/blob/master/insurance-files/sha256-hashes.md) for more information.
- [ ] Run `binwalk` on all of the WL insurance files
    - Get binwalk here: <https://github.com/devttys0/binwalk/>
- [ ] Search for interesting transaction chains
    - Use our [local-blockchain-parser](https://github.com/WikiLeaksFreedomForce/local-blockchain-parser)'s `tx-chain` command.  The command will find chains, run an analysis on all of the transactions in a given chain, and output a folder containing the results and the list of transactions.  Add that folder to this repo when you find an interesting chain.

## Informational links and articles

- [Hidden surprises in the Bitcoin blockchain and how they are stored: Nelson Mandela, Wikileaks, photos, and Python software](http://www.righto.com/2014/02/ascii-bernanke-wikileaks-photographs.html)
- [WikiLeaks insurance file torrent mirror](https://ftwtech.us/wikileaks/)
- [WikiLeaks insurance file torrent mirror #2](https://wiki.installgentoo.com/index.php/Wiki_Backups)
- [How the Bitcoin protocol actually works](http://www.michaelnielsen.org/ddi/how-the-bitcoin-protocol-actually-works/)
- [Peter Todd's article on OpenTimestamps](https://petertodd.org/2016/opentimestamps-announcement#fn:hello-world-address)
- [How to use GPG on the command line](http://blog.ghostinthemachines.com/2015/03/01/how-to-use-gpg-command-line/)
- [GPG cheat sheet](http://irtfweb.ifa.hawaii.edu/~lockhart/gpg/gpg-cs.html)
