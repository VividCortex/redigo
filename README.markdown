Redigo
======

<<<<<<< HEAD
[![Build Status](https://travis-ci.org/garyburd/redigo.svg?branch=master)](https://travis-ci.org/garyburd/redigo)
[![GoDoc](https://godoc.org/github.com/VividCortex/redigo/redis?status.svg)](https://godoc.org/github.com/VividCortex/redigo/redis)
=======
[![Build Status](https://travis-ci.org/gomodule/redigo.svg?branch=master)](https://travis-ci.org/gomodule/redigo)
[![GoDoc](https://godoc.org/github.com/gomodule/redigo/redis?status.svg)](https://godoc.org/github.com/gomodule/redigo/redis)
>>>>>>> 9352ab68be133885e31a43661cc42a220cb8e821

Redigo is a [Go](http://golang.org/) client for the [Redis](http://redis.io/) database.

Features
-------

<<<<<<< HEAD
* A [Print-like](http://godoc.org/github.com/VividCortex/redigo/redis#hdr-Executing_Commands) API with support for all Redis commands.
* [Pipelining](http://godoc.org/github.com/VividCortex/redigo/redis#hdr-Pipelining), including pipelined transactions.
* [Publish/Subscribe](http://godoc.org/github.com/VividCortex/redigo/redis#hdr-Publish_and_Subscribe).
* [Connection pooling](http://godoc.org/github.com/VividCortex/redigo/redis#Pool).
* [Script helper type](http://godoc.org/github.com/VividCortex/redigo/redis#Script) with optimistic use of EVALSHA.
* [Helper functions](http://godoc.org/github.com/VividCortex/redigo/redis#hdr-Reply_Helpers) for working with command replies.
=======
* A [Print-like](http://godoc.org/github.com/gomodule/redigo/redis#hdr-Executing_Commands) API with support for all Redis commands.
* [Pipelining](http://godoc.org/github.com/gomodule/redigo/redis#hdr-Pipelining), including pipelined transactions.
* [Publish/Subscribe](http://godoc.org/github.com/gomodule/redigo/redis#hdr-Publish_and_Subscribe).
* [Connection pooling](http://godoc.org/github.com/gomodule/redigo/redis#Pool).
* [Script helper type](http://godoc.org/github.com/gomodule/redigo/redis#Script) with optimistic use of EVALSHA.
* [Helper functions](http://godoc.org/github.com/gomodule/redigo/redis#hdr-Reply_Helpers) for working with command replies.
>>>>>>> 9352ab68be133885e31a43661cc42a220cb8e821

Documentation
-------------

<<<<<<< HEAD
- [API Reference](http://godoc.org/github.com/VividCortex/redigo/redis)
- [FAQ](https://github.com/VividCortex/redigo/wiki/FAQ)
=======
- [API Reference](http://godoc.org/github.com/gomodule/redigo/redis)
- [FAQ](https://github.com/gomodule/redigo/wiki/FAQ)
- [Examples](https://godoc.org/github.com/gomodule/redigo/redis#pkg-examples)
>>>>>>> 9352ab68be133885e31a43661cc42a220cb8e821

Installation
------------

Install Redigo using the "go get" command:

<<<<<<< HEAD
    go get github.com/VividCortex/redigo/redis
=======
    go get github.com/gomodule/redigo/redis
>>>>>>> 9352ab68be133885e31a43661cc42a220cb8e821

The Go distribution is Redigo's only dependency.

Related Projects
----------------

- [rafaeljusto/redigomock](https://godoc.org/github.com/rafaeljusto/redigomock) - A mock library for Redigo.
- [chasex/redis-go-cluster](https://github.com/chasex/redis-go-cluster) - A Redis cluster client implementation.
- [FZambia/sentinel](https://github.com/FZambia/sentinel) - Redis Sentinel support for Redigo
- [mna/redisc](https://github.com/mna/redisc) - Redis Cluster client built on top of Redigo

Contributing
------------

See [CONTRIBUTING.md](https://github.com/gomodule/redigo/blob/master/.github/CONTRIBUTING.md).

License
-------

Redigo is available under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html).
