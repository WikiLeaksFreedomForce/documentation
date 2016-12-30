# Investigating `insurance.aes256` from 2010

Torrent: `magnet:?xt=urn:btih:ed6fcad4d2ec8086be56e72f37497475bbc137f1&dn=WikileaksWarDiaryInsurance`

Decrypt using


```
$ openssl enc -d [CYPHER HERE] -in insurance.aes256 -out decrypted.file
```

You will be asked for a password.
`ONION` works, but that does not mean it's the correct password.


Available cyphers
```
-aes-256-cbc <---
-aes-256-cbc-hmac-sha1
-aes-256-cbc-hmac-sha256
-aes-256-ccm
-aes-256-cfb <---
-aes-256-cfb1
-aes-256-cfb8 <---
-aes-256-ctr
-aes-256-ecb
-aes-256-gcm
-aes-256-ofb
-aes-256-xts
```

# Scanning the decrypted file for file headers and other information

Install [Binwalk](https://github.com/devttys0/binwalk/), a tool to find file headers, signatures and other pieces of information in raw data.

Follow the installation steps on the github.

After that, you can use the command `binwalk` everywhere.

```
$ binwalk decrypted.file
```

Partial binwalk results for select cyphers:

[-aes-256-cbc](https://github.com/WikiLeaksFreedomForce/documentation/blob/master/insurance-files/binwalks.md#cbc)

[-aes-256-cfb8](https://github.com/WikiLeaksFreedomForce/documentation/blob/master/insurance-files/binwalks.md#cfb8)

[-aes-256-cfb](https://github.com/WikiLeaksFreedomForce/documentation/blob/master/insurance-files/binwalks.md#cfb)

[-aes-256-cfb1](https://github.com/WikiLeaksFreedomForce/documentation/blob/master/insurance-files/binwalks.md#cfb1)


