#Security

## Encryption / Decryption

All key generation, plain-text encryption and cipher-text decryption takes place within a user's Chrome browser. We are using the open-source Javascript library [Cryptico](https://github.com/wwwtyro/cryptico) to perform all of these operations.

The key used is an RSA public/private key with a 1024-bit length. 

## Key Storage

The generated public/private key is stored in an encrypted format using the password you set when you first install the extension.

If you have Chrome Sync enabled on your Chrome installation, the key will be stored (in encrypted form) and synced to Google's Chrome Sync cloud storage.

The decrypted key is only ever stored in memory within the extension, and is never stored on disk.

## Closed Source

InCrypt is currently closed source. We understand that peer review of any encryption software is important to validate the security of such a product for end users. 

We intend to open source the relevant elements when the time is right for us.
