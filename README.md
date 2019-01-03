# Common Configuration Files #
A collection of common configuration files.

## Docker ##
`/docker/docker-compose.yml`

A simple docker-compose configuration that can be used to start and Elasticsearch and MongoDB instance within a Docker container. This is useful when using Graylog in a development environment, since it eliminates the need for a static install of both Elasticsearch and MongoDB. NOT FOR PRODUCTION GRAYLOG USE

To use, install Docker Compose (https://docs.docker.com/compose/install/
), create a new directory containing the config file, then execute `docker-compose up`to start the container. You should see log messages from both MongoDB and Elasticsearch. 
