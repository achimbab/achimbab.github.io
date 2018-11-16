---
layout: post
title: Click House
---


# Build

### Environment
debian 8

### Errors

`sudo apt-get update` shows `404 Not Found` errors.

Some packages does not support debian jessie distributions.

So you have to rename the name of distbutions in the sources files in `/etc/apt/sources.list` to trusty

> deb http://ppa.launchpad.net/george-edison55/cmake-3.x/ubuntu ~~jessie~~ main
> deb http://ppa.launchpad.net/george-edison55/cmake-3.x/ubuntu trusty main

