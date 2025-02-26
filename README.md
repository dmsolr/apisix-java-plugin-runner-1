apisix-java-plugin-runner
=================

Runs [Apache APISIX](http://apisix.apache.org/) plugins written in Java.
Implemented as a sidecar that accompanies APISIX.

![apisix-java-plugin-runner-overview](./docs/images/apisix-java-plugin-runner-overview.png)

Status
------

This project is currently considered experimental.

Why apisix-java-plugin-runner
---------------------

APISIX offers many full-featured plugins covering areas such as authentication,
security, traffic control, serverless, analytics & monitoring, transformations, logging.

It also provides highly extensible API, allowing common phases to be mounted,
and users can use these api to develop their own plugins.

APISIX supports writing plugins in multiple languages in version [2.6.0](https://github.com/apache/apisix/blob/master/CHANGELOG.md#260),
this project is APISIX Java side implementation that supports writing plugins in java.


How it Works
-------------

See [How it Works](./docs/how-it-works.md) to learn how apisix-java-plugin-runner collaborate
with APISIX to run plugins written in java.

The Internal of apisix-java-plugin-runner
---------------------------------

If you're interested in the internal of apisix-java-plugin-runner, we recommend you
to read the [the-internal-of-apisix-java-plugin-runner](./docs/the-internal-of-apisix-java-plugin-runner.md),
it explains the details of communication and protocol conversion with APISIX.

Get Involved in Development
---------------------------

Welcome to make contributions, but before you start, please check out
[development.md](./docs/development.md) to learn how to run and debug apisix-java-plugin-runner
in your own environment.

License
-------

[Apache 2.0 LICENSE](./LICENSE)