# monitoring-template
## Description
This project is a template for a monitoring system. It is used to monitor the performance of the application.

## Getting started
Set the following CI/CD variables:
- [ ]  `GF_SECURITY_ADMIN_PASSWORD` : [ project variable ] The password of the Grafana admin.
- [ ]  `POSTGRES_USER` : [ project variable ] The user of the Postgres.
- [ ]  `POSTGRES_PASSWORD` : [ project variable ] The password of the Postgres.
- [ ]  `POSTGRES_DB` : [ project variable ] The database name of the Postgres.

## Create containers
```
docker-compose up -d
```

## Connect to Grafana
```
http://<host>:3000
```

## Connect to Prometheus
```
http://<host>:9090
```

## Set up Grafana dashboard
```
# connect to Prometheus
http://prometheus:9090

# Import dashboard
ID: 1860
Title: Prometheus 2.0 Stats
```
