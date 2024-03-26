# nginx_modsite

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

### Install

#### Create File (recommended)

    $ nano /usr/bin/nginx_modsite

#### Set Permisions
    $ chmod +x /usr/bin/nginx_modsite


### Usage:

#### To list all the sites
    $ sudo nginx_modsite -l

#### To enable site "test_website"
    $ sudo nginx_modsite -e test_website

#### To disable site "test_website"
    $ sudo nginx_modsite -d test_website
  
Original Post for more information
https://serverfault.com/questions/424452/nginx-enable-site-command
