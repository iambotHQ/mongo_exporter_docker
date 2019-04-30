# Dockerized Prometheus Mongo exporter

Based on [Percona Mongo Exporter](https://github.com/percona/mongodb_exporter)

## Usage

```
docker run -e MONGO_URI="mongodb://mongo:27017" iambothq/mongo_exporter
```