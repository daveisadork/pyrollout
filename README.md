# pyrollout
Python feature flagging

[![Build Status](https://travis-ci.org/brechin/pyrollout.svg?branch=master)](https://travis-ci.org/brechin/pyrollout)

Inspired by the [rollout](https://github.com/FetLife/rollout) Ruby gem by [James Golick](https://github.com/jamesgolick)
and a Python port of it called
[proclaim](https://github.com/asenchi/proclaim) by [Curt Micol](Curt Micol) which I found after reading 
[Using Feature Flags to Ship Changes with Confidence](http://blog.travis-ci.com/2014-03-04-use-feature-flags-to-ship-changes-with-confidence/) 
by [Mathias Meyer](https://github.com/roidrage).

Both of these use redis, and I don't like that requirement. I seek to support multiple storage/persistence mechanisms.

Some feature ideas
------------------

* Flag by user 
* Flag by group (including special groups _ALL_ and _NONE_)
* Flag on percentage
* Flag on user property
* Flag on lambda passed the user object
* Use memory
* Use file
* Use memcache, e.g. in Google App Engine
* Use some other persistent database
