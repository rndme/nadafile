# nadafile
Safe and simple all-platform notepad protected with AES256-GCM


## What / How
The app runs as a single self-contained local HTML file, no installs, perms, servers, or config needed.


## Why
I needed a safe way to store some text on a thumb drive without any software, autorun capability, drivers, etc.

## Setup

1. [download html file](https://pagedemos.com/new_nadafile/download) (or [save raw](https://github.com/rndme/nadafile/blob/master/new_nadafile.html)), run locally in Chrome or Firefox (maybe others)
2. choose a good password (8 chars min), enter it
3. write your message or notes
4. click "Encrypt and Download" to fetch a new password protected copy 

## Projects used

* [SJCL](https://github.com/bitwiseshiftleft/sjcl) - to use AES, 256 bits in GCM
* [download](https://github.com/rndme/download) - to save generated copies
* [js-sha3](https://github.com/emn178/js-sha3) - for key derivation
