swupd-client
-------

[![Build Status](https://travis-ci.org/bryteise/swupd-client.svg?branch=master)](https://travis-ci.org/bryteise/swupd-client)
[![Coverage Status](https://coveralls.io/repos/github/bryteise/swupd-client/badge.png?branch=master)](https://coveralls.io/github/bryteise/swupd-client?branch=master)

The swupd-client package provides a reference implementation of a software
update client which performs file level updates of an OS, preferentially
using binary deltas whenever possible for efficiency under an assumption
that the OS develops with a release process aimed at rapidly deploying
small incremental changes.
