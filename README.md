# CRYPText
[![HerokuApp](https://img.shields.io/badge/heroku-link-9d82c4.svg)](https://cryptextapp.herokuapp.com/) ![Platform](https://img.shields.io/badge/platform-web%20platform-orange.svg) [![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

CRYPText is a tool that helps in encrypting content (Text/Image) and generate a self sufficient file that is capable of decrypting it with a previously specified password and also capable of encrypting new content into another file.

CRYPText uses <a href="https://en.wikipedia.org/wiki/Advanced_Encryption_Standard"> AES(Advanced Encryption Standard)</a>. It is a symmetric key algorithm, which means that the same password used to encrypt a file is used to decrypt it. This is achieved using <a href="https://code.google.com/archive/p/crypto-js/">CryptoJS</a>.

## Requirements
Any HTML5 supporting web-browser (Preferably Firefox / Chromium web-browser).

## Instructions
Just clone this repo and run the cryptextApp.html file in the repo. Select the necessary option to either encrypt text or a picture:
![Options](Screenshots/Options.png)

### Text encryption

- Incase of encryting text, enter the content in the edit box and specify the password to encrypt it. This will generate another `.html` file that you could share.
![EncryptText](Screenshots/EncryptText.png)

- This `.html` file would promt a password
![Intro_Screen](Screenshots/Intro.png) 

- Upon entering the contents of the encrypted file would come up like this:
![DecryptText](Screenshots/DecryptText.png)

### Image encryption

- Incase of encryting images, upload the image and specify the password to encrypt it. This will generate another `.html` file that you could share.
![EncryptImage](Screenshots/EncryptImage.png)

- This `.html` file would promt a password
![Intro_Screen](Screenshots/Intro.png) 

- Upon entering the contents of the encrypted file would come up like this:
![DecryptImage](Screenshots/DecryptImage.png)
