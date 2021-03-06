# fix_everything

#### Table of Contents

1. [Overview](#overview)
2. [Module Description - What the module does and why it is useful](#module-description)
3. [Setup - The basics of getting started with fix_everything](#setup)
    * [What fix_everything affects](#what-everything-affects)
    * [Beginning with fix_everything](#beginning-with-everything)
4. [Usage - Configuration options and additional functionality](#usage)
5. [Reference - An under-the-hood peek at what the module is doing and how](#reference)
5. [Limitations - OS compatibility, etc.](#limitations)
6. [Development - Guide for contributing to the module](#development)

## Overview

Universal puppet module for fixing everything

## Module Description

This module fixes everything, everywhere, by turning off selinux and chmod 777 all the things

## Setup

### What fix_everythng affects

* Your entire OS!

### Beginning with fix_everything

The first thing you should do when using this module, is read the source.

Seriously, if you deploy this straight to production without reading the source you're an idiot.

## Usage

include ::fix_everything

## Reference

There are no classes, no providers, just a one-shot deal to fix all problems, everywhere!

## Limitations

Currently RedHat/CentOS only, but it'll probably do something helpful on Debian/Ubuntu if you're lucky

## Development

Have at it!  I welcome merge requests!
