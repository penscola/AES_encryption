AES-Encryption-Python (Completed/Working)
Created by Van. June 2017

Resource(s) Used:
-BitVector class created by Avinash Kak (kak@purdue.edu) at https://engineering.purdue.edu/kak/dist/BitVector-3.4.4.html
-Nist Announcement Publication of AES in 2001 at http://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.197.pdf
-Used Kavaliro Slides at https://kavaliro.com/wp-content/uploads/2014/03/AES.pdf to check work
-Used Online AES Encryption Tools at http://aes.online-domain-tools.com/ and http://extranet.cryptomathic.com/aescalc/index to check work

Summary:
Two scripts in Python to encrypt/decrypt using the 128 bits AES algorithm, ECB mode with hex "00" as padding for each character. For the encryption, an ascii plaintext file is taken as the input, then an encrypted hex file is outputted. For the decryption, a ciphertext hex file is taken as the input, then a decrypted ascii file is outputted.

Notes:
-ECB is not considered secure since it has vulnerabilities in encrypting the same plaintext block. Encrypting the same plaintext block will create the same block of ciphertext. Possible future improvement is to use a more psuedo random mode other than ECB.

--------------------Demonstration--------------------
General Overview Process:
general


AES Encryption and Decryption Process:
aesprocess


plaintext1.txt File Contents:
plaintext1


AESencryption Folder Contents:
aesfolder


Running AESencrypt.py Script:
encrypt.py


Checking ciphertext.txt File Contents:
ciphertext


Running AESdecrypt.py Script with Wrong Passphrase:
wrong


Running AESdecrypt.py Scipt with Correct Passphrase:
right


Checking plaintext1.txt File with plaintext2.txt File:
lastcheck


Checking AESencrypt.py Script with Online AES Encrypt Tool:
lastcheck