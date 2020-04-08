<img src="logo.png" style="width:20px;"/>


# InfluxDB

InfluxDB is a time series database designed to handle high write and query loads.

This repo contains the Docker files of the unofficial "influxdb" image found on dockerhub jrpamid repo. jrpamid/influxdb:1x_alpine

The image is based on the latest alpine as base image. 

InfluxDB currently has two  versionx 1.x and 2.x

InfluxDB 2.x is in beta stage and rolls up the TICK (Telegraf, InfluxDB, Chronograf, Kapacitor) stack into one bundle. 


<strong>Current Versions</strong> - version=1.7.10  image=jrpamid/influxdb:1x_alpine
<strong>Current Versions</strong> - 2.0.0-beta  image=jrpamid/influxdb:2x_alpine


Image is provided “as is” without warranty of any kind, extensive testing has not been doen yet.


<br>

## Image Details (jrpamid/influxdb:1x_alpine)

influxdb_home = /opt/influxdb
config file   = /opt/influxdb/influxdbv1.ini
influxdb_data = /influxdb/data
influxdb_wal = /influxdb/data/wal
influxdb_meta = /influxdb/data/meta
influxdb_http_port =8086

## Image Details (jrpamid/influxdb:2x_alpine)

influxdb_home = /opt/influxdb
config file   = /opt/influxdb/influxdbv1.ini
influxdb_data = /influxdb/data
influxdb_wal = /influxdb/data/wal
influxdb_meta = /influxdb/data/meta
influxdb_http_port= 9999
<br>


## How to use the image ?


