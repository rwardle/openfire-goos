# README #

Dockerfile to create a Docker container image for Openfire that is suitable to use with the worked example in [Growing Object-Oriented Software Guided by Tests](http://www.growing-object-oriented-software.com).

Based on [https://github.com/sameersbn/docker-openfire](https://github.com/sameersbn/docker-openfire).

The Openfire data directory is initialised with these configuration changes:

* Set XMPP domain to 'localhost'.
* Set Resource Conflict policy to 'Never kick'.
* Create user 'sniper'.
* Create user 'auction-item-54321'.
* Create user 'auction-item-65432'.
