<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRbgsg-LEnF3j_K6yrP0HyZxZe_hR4rpks8LQ&usqp=CAU" align="right" width="90" height="80">

# WpCrack Tool

![Python](https://img.shields.io/badge/Python-3.9.2-blue)
![License](https://img.shields.io/badge/License-MIT-brightgreen)

> WordPress Brute Force Super Fast Login

```
      .---.        .-----------
     /     \  __  /    ------
    / /     \(  )/    -----
   //////   ' \/ `   ---
  //// / // : ★★ : ---
 // /   /  /`    '--
//          //..\   WpCrack Brute Froce Tool™
       ====UU====UU==========================
           '//||\`
             ''``
https://github.com/Kedjaw3n


usage: python WpCrack.py [options]                              
optional arguments:
  -h, --help        show this help message and exit
  -V, --version     show program's version number and exit
  -d, --debug       debugging mode

target arguments:
  -t , --target     url of the target
  -u , --username   username of the target (default: admin)
  -p , --password   password of the target (change -p to --p to use a wordlist)

  --timeout         timed out for requests
  --thread          numbers of threading multiproccesor (default: 5)
  --proxy           using a HTTP proxy (ex: http://site.com:8000)

Copyright © 2021 Defacer Hurt.id- Powered by Indonesian Darknet
```

## Instalasi
<p>
$ git clone https://github.com/Kedjaw3n/WpCrack
<p>
$ cd WpCrack
<p>
$ python WpCrack.py
<p>

## How To Use

Using a single password
```bash
python WpCrack.py -t http://site.com/wp-login.php -u admin -p password
```

Using a multiple password / wordlist
```bash
python WpCrack.py -t http://site.com/wp-login.php -u admin --p wordlist.txt
```

## About
WpCrack is a tool used to force login into the WordPress CMS web application and is built in the Python programming language

## Features
- Very fast login
- Use of HTTP proxies
- Multithreading or Multiprocessor
