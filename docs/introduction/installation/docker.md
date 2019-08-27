# Docker

The recommended way of getting PolyHome up and running, is by using Docker along with Docker-Compose.

## Install using script

You will find the script is located at https://get.polyhome.io. You can either download it and execute it yourself, or simply copy the following command into a terminal and run it.

You will be asked a few questions, like where you want to save the configuration, whereafter it should be up and running, and you can access PolyHome at `http://localhost:8422`

### curl

`curl -fsSL https://get.polyhome.io | sh`

## Install manually

Setting up PolyHome works like any other Dockerized application. You can find a docker-compose.yaml example [here](https://hub.docker/r/polyhome/polyhome)
