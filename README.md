# Python-Useful-Links
This Repository is dedicated to python Useful links
## To check all your installed existed libraries 
```console
$ pip freeze
```
## Upgarde all python Packages with PiP 
 or Check [==>](https://stackoverflow.com/questions/2720014/upgrading-all-packages-with-pip)
 or Check [==>](https://hackernoon.com/a-pip-hack-to-upgrade-all-your-python-packages-492658c49681)
```console
$ pip freeze --local | grep -v '^\-e' | cut -d = -f 1  | xargs -n1 pip install -U
```
* Version with root privileges:
```console
$ sudo pip2 freeze — local | grep -v ‘^\-e’ | cut -d = -f 1 | xargs -n1 sudo pip2 install -U
```
## Newer versions of pip allow you to list outdated packages:
```console
$ pip list --outdated --format=freeze
```
