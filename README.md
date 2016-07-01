# lockbox
Safe and simple all-platform notepad protected with AES256-GCM


## What / How
The app runs as a single self-contained local HTML file, no installs, perms, servers, or config needed.


## Why
I needed a safe way to store passwords and contacts on a thumb drive, without any software, autorun capability, OS lock-ins, etc.

## Setup

1. [download html file](http://pagedemos.com/lockbox_demo/download) (or [save raw](https://raw.githubusercontent.com/rndme/lockbox/master/create-lockbox.html)), run locally in Chrome or Firefox (maybe others)
2. choose a good password (8 chars min), enter it
3. write your message or notes
4. click "Encrypt and Download" to fetch a new password protected copy 

## Projects used

* [SJCL](https://github.com/bitwiseshiftleft/sjcl) - to use AES, 256 bits in GCM
* [download](https://github.com/rndme/download) - to save generated copies
* [js-sha3](https://github.com/emn178/js-sha3) - for key derivation
