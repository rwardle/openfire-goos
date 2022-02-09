# Openfire-GOOS

[Openfire](http://www.igniterealtime.org/projects/openfire) Docker image configured for the worked example in [Growing Object-Oriented Software Guided by Tests](http://www.growing-object-oriented-software.com).

Based on [sameersbn/docker-openfire](https://github.com/sameersbn/docker-openfire).

## Configuration

The Openfire data directory is initialised with these configuration changes:

* Set admin user password to 'admin'.
* Set XMPP domain to 'localhost'.
* Set Resource Conflict policy to 'Never kick'.
* Create user 'sniper/sniper'.
* Create user 'auction-item-54321/auction'.
* Create user 'auction-item-65432/auction'.

## Builds

Builds are available on Docker Hub: [rwardle/openfire-goos](https://hub.docker.com/r/rwardle/openfire-goos).