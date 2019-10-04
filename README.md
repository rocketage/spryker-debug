Spryker Debug
=============

[![Build Status](https://travis-ci.org/inviqa/spryker-debug.svg?branch=master)](https://travis-ci.org/inviqa/spryker-debug)

Collection of debug and development tools for Spryker:

Installation
------------

```
composer require inviqa/spryker-debug
```

Each feature needs to be enabled individually. Instructions provided in the
documentation.

Features
--------

Follow the link for documentation:

- [Config Dump](doc/config_dump.md): Introspect configuration.
- [Database Shell](doc/database_shell.md): Launch a postgres shell.
- [Redis Shell](doc/redis_shell.md): Launch a Redis shell.
- [Queue Overview](doc/queue_overview.md): Show queue statuses.

Developing
----------

Run the tests:

```
composer integrate
```
