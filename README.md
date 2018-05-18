PHP Copy/Paste Detector container
=================================

[![Build Status](https://travis-ci.org/Gwerlas/phpcpd.svg?branch=master)](https://travis-ci.org/Gwerlas/phpcpd)

What is PHP Copy/Paste Detector
-------------------------------

`phpcpd` is a Copy/Paste Detector (CPD) for PHP code.

Github project : [sebastianbergmann/phpcpd](https://github.com/sebastianbergmann/phpcpd)

Usage
-----

```sh
docker run --rm oxeva/phpcpd phpcpd --help
```

The entrypoint has not been changed from the PHP official container, so you can run PHP interactively as you'll do usually..

Sample of project scanning :

```sh
docker run --rm -v $PWD:/project oxeva/phpcpd phpcpd /project/
```
