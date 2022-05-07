MongoDB Config for Tutor
===================================

This is a plugin for
[Tutor](https://docs.tutor.overhang.io) that allows [Open edX](https://openedx.org/) to be
configured with few params that are required for mongodb clusters.

Installation
------------

    pip install git+https://github.com/dphi-official/tutor-mongodb-plugin.git

Then, to enable this plugin, run:

    tutor plugins enable tutormongo

Plugin configuration
--------------------

* `MONGO_REPLICA_SET` (default: `""`)
* `MONGO_AUTH_SOURCE` (default: `""`)

These values can be modified by the `tutor config save --set
PARAM_NAME=VALUE` command, or by setting them in `$(tutor config
printroot)/config.yaml`.

License
-------

This software is licensed under the terms of the AGPLv3.