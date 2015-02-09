# Incrypt
Incryption *you* control

##What is Incrypt?
Incrypt aims to make end to end encryption easy. Content should be encrypted before leaving your browser, so that it's impossible that anyone else can see it. 

Currently we provide an experiemental Chrome extension which automatically encrypts and decrypts content on certain sites. 

We have currently added support for:

* http://pastebin.com
* http://gist.github.com
* http://gmail.google.com (Although you can only send emails to yourself).

Anybody can build a site which works with the extension.

##

##Warnings

Currently the extension is in early alpha, and is intended as a demo to get feedback rather than a product.

Please don't use it to store any data you'd be upset to lose.

##What's planned for the future?

In future we'd like to stablise the API to enable people to build applications which take advantage of InCrypt for end-to-end encryption on their sites.

We'd also like to implement communication encryption so that communications with others can be encrypted and decrypted. For example emails and instant messages.

We'd like to add support for multiple browsers and mobile operating systems.

##Technical
###How it works
When the extension detects InCrypt markup in HTML e.g. `<input incrypted="true"> </input>`. It automatically goes to work encrypting and decrpting content in those elements.

##About us



