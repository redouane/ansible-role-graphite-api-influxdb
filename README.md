Role Name Graphite-api-influxdb
===============================

[![Build Status](https://travis-ci.org/redouane/ansible-role-graphite-api-influxdb.svg?branch=master)](https://travis-ci.org/redouane/ansible-role-graphite-api-influxdb)

Installs and configures graphite-api and graphite-influxdb as a finder

Requirements
------------

None

Role Variables
--------------

```yaml

graphite_api_deb_url: https://github.com/brutasse/graphite-api/releases/download/1.1.2/graphite-api_1.1.2-1447943657-ubuntu14.04_amd64.deb
graphite_api_influxdb_archive_url: https://github.com/pkittenis/graphite-influxdb/archive/0.5.1-rc2.tar.gz
graphite_api_influxdb_timezone: UTC
graphite_api_influxdb_db: graphite
graphite_api_influxdb_host: localhost
graphite_api_influxdb_port: 8086
graphite_api_influxdb_user: root
graphite_api_influxdb_pass: root
graphite_api_influxdb_aggregation_functions:
- \.min$ : min
- \.max$ : max
- \.last$ : last
- \.sum$ : sum

```

License
-------

BSD