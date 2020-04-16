# cply-php

Search lyrics and copy them automatically from the terminal

## Requirements
This version is written in PHP and it requires PHP and Composer and a unix system, the song selector of [Climax](https://github.com/tucnak/climax) only works on Unix systems. Tested on Ubuntu (elementaryOS) but should work on others aswell.

## Install 
```bash
git clone https://github.com/asvvvad/cply-php
cd cply-php
composer install
```
Now you can run it using ./cply
To install it to the system it requires root you can use:
```bash
cd ..
sudo mv cply-php /usr/local/
sudo ln -sf /usr/local/cply/cply /usr/local/bin
```

## Usage:
[![asciicast](https://asciinema.org/a/MAxxbsticff0vDwLbioaV1wI4.svg)](https://asciinema.org/a/MAxxbsticff0vDwLbioaV1wI4)
