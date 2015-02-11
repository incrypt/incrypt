# InCrypt
> Encryption *you* control

## What is InCrypt?
InCrypt makes end-to-end encryption easy. Your sensitive data is encrypted before leaving your browser and sent to the website *in it's encrypted form*. This means only you, with your key and password, can decrypt it. It's impossible for anyone else to intercept and read it. 

When you visit the page later, the content is then automatically decrypted.

## Chrome Extension

Currently we provide an experimental [Chrome extension](https://chrome.google.com/webstore/detail/incrypt/dpjkdfkiiifaeandmfhdklbfiljjippf) which automatically encrypts and decrypts content on certain sites. 

The extension currently supports automatic encryption and decryption on:

* [Pastebin](http://pastebin.com)
* [Gist](http://gist.github.com)
* [Gmail](https://mail.google.com/mail/#inbox?compose=new) (Although you can only send emails to yourself).

## Installation

* Visit the [Chrome Web Store](https://chrome.google.com/webstore/detail/incrypt/dpjkdfkiiifaeandmfhdklbfiljjippf) to install the extension 
* Once installed, a pop-up will appear to enter your password
* You'll be prompted to set up a password, enter your password.
  * **NOTE**: If you forget this password, you will not be able to recover your data
* Your personal private key will be generated and stored in encrypted form on your machine
  * If you have Chrome Sync enabled, the key will be available on all your Chrome installations

## Using InCrypt

### Pastebin 

* Go to [Pastebin](http://pastebin.com) and enter some text into the input box. 
* Upon leaving the box the text you entered will be InCrypted.
* Click 'Publish' - you'll see the decrypted version of your text.

## Warnings

Currently the extension is in early alpha, and is intended as a demo to get feedback rather than a product.

Please don't use it to store any data you'd be upset to lose.

## What's planned for the future?

In future we'd like to stabilise the API to enable people to build applications which take advantage of InCrypt for end-to-end encryption on their sites.

We'd also like to implement communication encryption so that communications with others can be encrypted and decrypted. For example emails and instant messages.

We'd like to add support for multiple browsers and mobile operating systems.

## Technical
### How It Works
When the extension detects InCrypt markup in HTML e.g. `<input incrypted="true"> </input>`. It automatically goes to work encrypting and decrypting content in those elements.

If you want to included InCrypt support on your site, simply ensure that any `<input>` or `<textarea>` have this attribute applied. The InCrypt extension will then take care of the rest!

## Contact Us

We'd love to hear from you! 

If you have any thoughts / improvements or would like to build an application / example which uses InCrypt you can:

* [Create an issue](https://github.com/incrypt/incrypt/issues/new)
* [Email us](mailto:incrypt@googlegroups.com)
* Reply to us on [Reddit](http://reddit.com)
