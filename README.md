# Kong_Dock

## Set Up
``` bash
# step 1
$ git clone https://github.com/POPPROJECT/Kong_Dock

# step 2
$ docker network create webproxy
$ docker network create kong_network

# step 3
$ docker-compose up -d
