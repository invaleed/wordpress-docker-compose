# wordpress-docker-compose

Running Wordpress with mysql-8.0 using docker-compose include Nginx & SSL with Letsencrypt.

## Installation

## Install docker & docker-compose

```bash
$ sudo apt-get update
$ sudo apt-get install \
    apt-transport-https \
    ca-certificates \
    curl \
    gnupg-agent \
    software-properties-common
$ curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
$ sudo apt-get update
$ sudo apt-get install docker-ce
```

```bash
$ sudo curl -L "https://github.com/docker/compose/releases/download/1.25.4/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
$ sudo chmod +x /usr/local/bin/docker-compose
$ sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
$ docker-compose --version
```

## Usage

Clone repository

```bash
$ git clone https://github.com/invaleed/wordpress-docker-compose.git
```

```bash
$ cd wordpress-docker-compose
$ docker-compose up -d
$ docker ps
```

## Access your Wordpress
```
https://[YOUR_DOMAIN_NAME]
```
