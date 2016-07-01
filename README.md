# lockbox
Safe and simple all-platform notepad protected with AES256-GCM

## Setup

1. [download html file](http://pagedemos.com/lockbox_demo/download), run locally in Chrome or Firefox
2. choose a good password (8 chars min), enter it
3. write your message or notes
4. click "Encrypt and Download" to fetch a new password protected copy 

## Projects used

* [SJCL](https://github.com/bitwiseshiftleft/sjcl) - to use AES, 256 bits in GCM
* [download](https://github.com/rndme/download) - to save generated copies
* [js-sha3](https://github.com/emn178/js-sha3) - for key derivation
