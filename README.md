# PostgreSQL + PostGIS + Docker == Success

PostGIS is a spatial database extender for PostgreSQL, a SQL object-relational database system. Docker is a container system.


# Install

```
docker run --rm -it kelsoncm/postgres_postgis:10.5_2.4-alpine
```

# Sizes

| Image                                     | Size  |
| ----------------------------------------- | ----- |
| kelsoncm/postgres_postgis:10.5_2.4-alpine | 196MB |
| kelsoncm/postgres_postgis:10.5_2.4        | 621MB |
| postgres:9.6-alpine                       |  39MB |
| postgres:10.5                             | 228MB |
