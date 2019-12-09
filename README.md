# One click run/install for Athina and Athina Web

## Prerequisites
* docker
* docker-compose

### Ubuntu (18.04+)
`apt install docker.io docker-compose pwgen`

or install the latest versions

## Run and auto-install
`sudo su` # run as root

`./run.sh`

The first time execution will install and configure athina and athina-web. Subsequent runs will just startup the services in your system.
