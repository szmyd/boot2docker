# Boot2SDS

Boot2SDS is a lightweight Linux distribution forked from
[Boot2Docker](https://github.com/boot2docker/boot2docker) made specifically to
run [Docker](https://www.docker.com/) containers with SCST kernel support. It
runs completely from RAM, is a small ~57MB download and boots in ~10s.

## Features

* Kernel 4.4.115 with AUFS and SCST, Docker v18.02.0-ce - using libcontainer
* Container persistence via disk automount on `/var/lib/docker`
* SSH keys persistence via disk automount

> **Note:** Boot2SDS uses port **2376**, the [registered IANA Docker TLS
> port](http://www.iana.org/assignments/service-names-port-numbers/service-names-port-numbers.xhtml?search=docker)
