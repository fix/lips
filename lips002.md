# LIP 002 : Best practices for Passphrases Security

##Authors
fixcrypt, fixcrypt@gmail.com

##Rationale
In order to prevent from hacker to gaining access to a lisk account, some practices inspired from database protection about choosing passphrases are recommended.

##Description
### reducing brute force hacking
To prevent from classic technics to invert publickeys like Rainbow Tables[https://www.wikiwand.com/en/Rainbow_table] there are precaution in choosing passphrases that are used to generate keypairs:
- Passphrases should follow BIP39 recommendation
- Alternatively implementations can salt secondary passphrases (ie for second signautres or multi-signatures) with primary public key. The advantage is to keep a simple short passphrase for the user and reduce footprints of copy-pasting passphrase around 

### reducing passphrases footprint
In order to reduce the footprint of complicated passphrases, that would need to be copy-pasted or send by email and stored in different devices to create transactions, it is recommended to use or implement a cryptographic vault to store passphrases

##Example
TODO
