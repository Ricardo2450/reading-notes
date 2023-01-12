# Cryptography

> ## [Encryption, Decryption & Hacking](https://www.khanacademy.org/computing/computers-and-internet/xcae6f4a7ff015e7d:online-data-security/xcae6f4a7ff015e7d:data-encryption-techniques/a/encryption-decryption-and-code-cracking)

* Caesar Cipher is a simple substitution cipher which replaces each original letter with a different letter in the alphabet by shifting the alphabet by a certain amount

* three main techniques to decipher code: 
  * frequency analysis
  * known plaintext
  * brute force.

* Frequency analysis - analyze the frequency of the characters in the message and identify the most likely "E" and narrow down the possible shift amounts based on that.

* Known plaintext - If the enemy already knew some part of the plaintext, it will be easier for them to crack the rest of the encrypted version.

* Brute force - There are only 25 possible shifts. The enemy could take some time to try out each of them and find one that yielded a sensible message

* Encryption: scrambling the data according to a secret key (in this case, the alphabet shift).

* Decryption: recovering the original data from scrambled data by using the secret key.

* Code cracking: uncovering the original data without knowing the secret, by using a variety of clever techniques.

> ## [Cryptography Crash Course](https://www.youtube.com/watch?v=jhXCTbFnK8o)

* AES balances performance and security to provide practical cryptography.

* key exchange - An algorithm that lets two computers agree on a key without ever sending one.

* Diffie-hellman key exchange - uses mathematical one-way functions 

* asymmetric encryption - there are two different keys. one public and one private.

> ### Other reads

* [Ceasar Cipher](https://en.wikipedia.org/wiki/Caesar_cipher)

* [Introduction to Cryptography](https://thebestvpn.com/cryptography/)

* [How Computers Generate Random Numbers](https://www.howtogeek.com/183051/htg-explains-how-computers-generate-random-numbers/)

[Return Home](../README.md)
