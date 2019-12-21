## Example

To encrypt

```
$ ./aes.py
[WARNING] This cipher script is only for educational purpose. It should NOT be used in production!
[NOTE] This cipher script operates in deterministic counter mode with 128 bit key
Do you want to encrypt or decrypt?
  e] Encrypt
  d] Decrypt
>>> e
Is your input data encoded in utf-8 string or hex representation of the binary data?
  u] UTF-8
  h] Hex
>>> u
Please enter the data to encrypt:
>>> This is the test message :)
Please enter the key in hex (leave empty to randomly generate a key):
>>> 
Generated random key: 5b32beb6e97596f3d0ec723d747d00ff

[Your Encrypted Data]
0e481dd991b11a9271fe3b8c9027929035752db77989cf11af7294

```
To decrypt

```
$ ./aes.py
[WARNING] This cipher script is only for educational purpose. It should NOT be used in production!
[NOTE] This cipher script operates in deterministic counter mode with 128 bit key
Do you want to encrypt or decrypt?
  e] Encrypt
  d] Decrypt
>>> d
Do you want to encode output your data in utf-8 string or hex representation of the binary data?
  u] UTF-8
  h] Hex
>>> u
Please enter the data to decrypt:
>>> 0e481dd991b11a9271fe3b8c9027929035752db77989cf11af7294
Please enter the key in hex:
>>> 5b32beb6e97596f3d0ec723d747d00ff

[Your Decrypted Data]
This is the test message :)
```
