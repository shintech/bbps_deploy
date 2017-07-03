## Backbone Postgres Seed

### Synopsis

Docker Compose file for shintech/backbone_postgres_seed

### Usage

#### create network

If network is not already created...

    docker network create -d bridge --subnet 192.168.0.0/24 --gateway 192.168.0.1 docker_network
    
#### create db

    git clone https://github.com/shintech/database

    # follow instructions in readme for database
    
#### start docker container

    docker-compose pull
    
    docker-compose up -d