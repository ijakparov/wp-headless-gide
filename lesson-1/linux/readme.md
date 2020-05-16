# Lesson 1. MacOS
## Environment setup
[localwp.com](localwp.com)
## composer setup
Paste in terminal
```sh
#update deps
sudo apt update
sudo apt install curl php-cli php-mbstring git unzip
#download composer
cd ~
curl -sS https://getcomposer.org/installer -o composer-setup.php
sudo php composer-setup.php --install-dir=/usr/local/bin --filename=composer
```
