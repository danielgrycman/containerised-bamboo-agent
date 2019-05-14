![Docker Pulls](https://img.shields.io/docker/pulls/danielgrycmancc/containerised-bamboo-agent.svg)

## Quickstart

To run:

    docker run -e BAMBOO_SERVER=123.45.67.89 -t bamboo-agent

## Setting this up locally in order to contribute

To build:

    git clone https://github.com/danielgrycman/docker-bamboo-agent.git
    cd docker-bamboo-agent
    docker build -t bamboo-agent .

## Docker Pull

docker pull danielgrycmancc/containerised-bamboo-agent