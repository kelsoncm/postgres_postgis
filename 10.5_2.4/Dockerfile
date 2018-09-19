FROM postgres:10.5
MAINTAINER Kelson da Costa Medeiros "kelsoncm@gmail.com"

RUN apt-get update \
  && apt-get install --no-install-recommends -y postgresql-10-postgis-2.4 postgresql-10-postgis-2.4-scripts \
  && apt-get clean \
  && rm -rf /var/lib/apt/lists/* \
  && echo "CREATE EXTENSION postgis;" > /docker-entrypoint-initdb.d/00-postgis.sql
