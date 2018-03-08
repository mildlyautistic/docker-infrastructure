# Docker infrastructure

Proof of concept on how Docker can be used to set up a local development environment within minutes.

## Install

```bash
> git clone https://github.com/mildlyautistic/docker-infrastructure.git
> cd docker-infrastructure
> docker volume create mongodata
> docker volume create rabbitmq
> docker-compose up
```

That's it. Services should be up and running on default port:

* MongoDB, port 27017
* RabbitMQ port 15672 (mgmt) and 5672

## Feedback

Register an issue!
