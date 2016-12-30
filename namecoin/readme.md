Investiagtion into the namecoin chain


Binwalk for namecoin blk0001.dat returned 

'''
1523126569 0x5AC91129 Private key in DER format (PKCS header length: 4, sequence length: 5141
'''

After cutting the file like so:

'''
$ dd bs=1 count=5145 skip=1523126569 if=blk0001.dat of=extracted
'''

The extracted file gets picked up at a Private Key in DER format. Please investigate
