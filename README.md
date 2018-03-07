# Docker infrastructure

Proof of concept on how Docker can be used to set up a local development environment within minutes.

## Install

```bash
> git clone https://github.com/mildlyautistic/docker-infrastructure.git
> cd docker-infrastructure
> docker volume create mongodata
> docker volume create rabbitmq
> docker volume create mssql
> docker-compose up
```

That's it. Services should be up and running on default port:

* MongoDB, port 27017
* Kibana, port 5601
* Elastic Search, port 9200 and 9300
* RabbitMQ port 15672 (mgmt) and 5672
* MSSQL, port 1433

## Read more

Original author wrote a [blog post](http://fellowdeveloper.se/2017/05/21/local-setup-in-minutes-with-docker/) about this.

## Feedback

Register an issue!
