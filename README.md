# Jamulus4Linux
This repository contains shell scripts for compilation of [Jamulus  Server and Client on Linux](https://github.com/jamulussoftware/jamulus) as an alternative to the [Ubuntu repository add and install(https://github.com/jamulussoftware/jamulus) process as mentioned by Jamulus Homepage. The [Jamulus Homepage](https://jamulus.io) does not contain binary packages, so that the provided script should help you getting Jamulus running on your Linux PC.

The respository contains the following scripts:
* `jamulus_install4debian.sh` download and install source code from [jamulussoftware](https://github.com/jamulussoftware/jamulus) on `Debian` 
* `jamulus_install4fedora.sh` download and install source code from [jamulussoftware](https://github.com/jamulussoftware/jamulus) on `Fedora`
* `jamulus_install4ubuntu.sh` download and install source code from [jamulussoftware](https://github.com/jamulussoftware/jamulus) on `Ubuntu`
* `service4jamulus.sh` is a script that starts or stops the Jamulus Service with `sudo sh service4jamulus.sh start` or `sudo sh service4jamulus.sh stop`

Jamulus was created and implemented by Volker Fischer (corrados). His respository of Jamulus existed in parallel to a fork does not exist anymore a
