# prometheus-grafana-setup
This repository contains a Prometheus and Grafana service dockerised for quick access 


## Getting started
- Pull down repository
- Setup prerequisites
- Run `docker-compose up`
- Visit [local-prometheus-9090](http://localhost:9090/graph) 
- Visit [local-grafana-3000](http://localhost:3000/login)
- You should have a service that exposes metrics to the path `../admin/metrics` and prometheus will pick up this service [here](http://localhost:9090/targets) 


## Prerequisites
These steps should be familiar if you're familiar with Docker

- Install [Docker](https://docs.docker.com/docker-for-mac/)

## Additional
This is only needed if you don't want to run prometheus and grafana in a dockerised container

- Install [Prometheus](https://prometheus.io/)
- Install [Grafana](https://grafana.com/)

## Terminate service
- Destroy docker images `docker-compose down -v` 

## Source
[Monitoring with prometheus grafana docker](http://opencapacity.co/news/2016/5/12/dev-talk-monitoring-with-prometheus-grafana-docker-part-1)

