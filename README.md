# wordpress-docker-compose

Running Wordpress with mysql-8.0 using docker-compose include Nginx & SSL with Letsencrypt.

## Installation

Clone repository

```bash
git clone https://github.com/invaleed/wordpress-docker-compose.git
```

## Install docker-compose

```bash
sudo curl -L "https://github.com/docker/compose/releases/download/1.25.4/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
docker-compose --version
```

## Usage

```bash
docker-compose up -d
docker ps

```

