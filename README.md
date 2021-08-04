Build: [![pipeline status](https://git.peek1e.eu/peek1e/dokuwiki-docker/badges/master/pipeline.svg)](https://git.peek1e.eu/peek1e/dokuwiki-docker/-/commits/master) 
Release: [![pipeline status](https://git.peek1e.eu/peek1e/dokuwiki-docker/badges/release/pipeline.svg)](https://git.peek1e.eu/peek1e/dokuwiki-docker/-/commits/release) 

### DokuWiki Containerized

This is an containerized version of [DokuWiki](https://www.dokuwiki.org/dokuwiki) on top of [TrafeX/docker-php-nginx](https://github.com/TrafeX/docker-php-nginx)

#### Prerequisites
You will need to install `docker` and `docker-compose`

#### Setup
- To start the service run `docker-compose pull && docker-compose up -d`

- Visit [http://machineip/install.php](http://localhost/install.php) to setup your instance of DokuWiki

If you need any assistance to upgrade, maintain etc. see the [DokuWiki](https://www.dokuwiki.org/dokuwiki) documentation
