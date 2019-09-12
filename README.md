[![License: CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/80x15.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)


Source of the https://odoo-saas.sh website

# How to contribute

## Initialization

* Fork this repo
* Clone to your machine

      git clone --recursive <URL>

* Install hugo:

      cd /tmp
      wget https://github.com/gohugoio/hugo/releases/download/v0.57.2/hugo_0.57.2_Linux-64bit.deb
      sudo dpkg -i hugo*.deb

## Make updates

### To preview updates

      cd doc-src
      hugo server -D

### To update content

* check folder ``doc-src/data/``
* make updates
* preview updates
* send pull request to this repo

### To update theme

* check folder ``doc-src/themes/``
* make updates
* preview updates
* make git commit
* send pull request to theme repo
* wait while the pull request is merged
* update theme version

       # TODO check the instruction
       git submodule update
       git commit -a -m "theme updated"

* send pull request to this repo
