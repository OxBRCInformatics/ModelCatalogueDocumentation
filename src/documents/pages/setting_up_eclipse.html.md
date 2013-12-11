---
title: Setting up Eclipse
layout: page
tags: ['intro','page']
pageOrder: 1
---

The development team uses the [Groovy/Grails Tool Suite(GGTS)](http://grails.org/products/ggts). Here are a few notes on getting it up and running.

## Functional tests

The functional test directory isn't in sources by default. To add it do the following:

* Right-click the project (or press ⌘-I)
* Go to the "Java Build Path" option on the left pane
* Select the "Source" tab if it isn't already
* Add Folder...
* Select test/functional and press 'OK'
* Rejoice!

