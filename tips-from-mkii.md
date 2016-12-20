
# tips from MkII

## Re: building a crawler

- **MkII:** "might be good to have a person or group tinker with those torrents and try to get them working. crawler will be important soon too. some of those files might need combination. if someone could make a zip file with all the data from those txs that would be good too. nice if they have the txid as filename"
- **MkII:** "was that list made looking at inputs too?"
- **MkII:** "test it on cablegate. if you hit a gpg file your crawler is good enough. also, use this strategy: <https://www.youtube.com/watch?v=7rdyrtEf2Jk>"
- **MkII:** "take one tx you know that has a file and find another one in the future that you know also has a file, then align them and have the crawler try to meet in the middle. tip to tip efficiency TM"
- **MkII:** "first test for cralwer is start at first cablegate tx and get all the other tx ids automatically. second test, start at cablegate first tx and crawl all the way to the first gpg file. once the second test works, you can then align"
- **MkII:** "more tips, if only one address spends the money follow that one. if more than one spend money start following the ones in order of who got the most. when you follow addresses, try finding another trans that has multiple people. if they are now addresses that have multiple people, see where the money goes and follow those instead."
- **MkII:** "you can start by only considering transactions that have anything encoded in any part, that should be enough for you to find the gpg files from cablegate. if you ran the crawler backwards from cablegate you will find satoshi uploads like the bitcoin paper and code. if you the start with staoshi's uploads and tip to tip you can get a lot more"

## Re: duplicate Tx data

- **MkII:** "dupes and fees fambam"
- **MkII:** "dupes+fee+header+crawled = KEKing"
- **MkII:** "you gotta look at all the pieces at the same time"
- **MkII:** "not just dupes alone, if dupe and also high and also date, and laksdlfdk then"
- **MkII:** "make sure you got this one "dupes+fee+header+crawled = KEKing""
- **X:** so would a series of tx same time same fee same header be the dank shit
- **MkII:** "same data too"
- **MkII:** "multiple txs that have the same data in them plus high fee"
- **X:** think it'll be sufficient to represent the data being checked (for dupes) as a sha256 hash and just compare hashes?  is there a more efficient hash that'll suffice?
- **MkII:** "sha256sum is ok. you can use diff if you don't care about time. advanced way is to use XOR"
- **MkII:** "sha256sum needs a good hash table"
- **MkII:** "bitwise stuff is the fastest but easier to get bugs intot he code"
- **MkII:** "if skills don't matter, just make a giant list of everything that keeps all detections with fees compared to average fee of that day, dupe count, a crawler that shows what addresses interacted with the, offline scripts that run commands on the outputs to see if they are compressed files or encrypted files, code that dump it all into memory image and uses rsakeyfind and aeskeyfind, etc."
- **MkII:** "just everything in one thing I guess"
- **MkII:** "lot of things will probably have to be offline"
- **MkII:** "crc is used to detect errors in data, but if you use it 'backwards' you can detect data in garabe"
- **MkII:** "what's hard is to run it while you scan. it's easy to check crc at the end of a file if you have the whole file. but in this case we don't know where files end/start"
- **MkII:** "it can be used to detect data mainly, and then if that works, you can detect where the files continue even if it's in other txs"
- **MkII:** "but that's a bit advanced and not necessary"

## misc.

- **MkII:** "fall of cassandra maymay before jan 20"

