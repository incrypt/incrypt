#Security

## Encryption method
We use [Cryptico](https://github.com/wwwtyro/cryptico) a javascript encryption library for encryption. We're using a currently using a key private/public key pair of length of 1024.

## Key storage
Your private/public key pair is stored encrypted with a passphrase that you set. It is currently stored in chrome sync, but later we may make this flexible e.g. storage on local disk. The decrypted key is in memory, but never stored on disk decrypted.

## Closed source encryption

InCrypt is currently closed source. We understand that encryption is not secure unless it's open source and we intend to open source the relevant elements when the time is right for us.




