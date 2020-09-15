# locust-performance-testing
There's simple example about performance testing with Locust

# We need to install
First we need to do the download docker on the machine: https://docs.docker.com/engine/install/ubuntu/ 

# Executing the project
After made the download about docker we need to do the download about this repository and execute docker-compose command:

```sh
$  docker-compose up --scale worker=4
```

# See the Locust application
Open your browse and input there the host about Locust application from Locust: http://localhost:8089/