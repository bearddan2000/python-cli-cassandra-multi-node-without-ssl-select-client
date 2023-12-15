# python-cli-cassandra-multi-node-without-ssl-select-client

## Description
POC for multi node without ssl cassandra in python.

- Features
  - multi node cassandra
  - cql
    - create keyspace
    - create table
    - bulk command
      - insert
      - delete
    - single insert
    - create index
    - select
  - pandas dataframe

## Tech stack
- python
  - cassandra-driver
  - padas
- cassandra

## Docker stack
- python:3.8-bullyseye
- cassandra:4.0

## To run
`sudo ./install.sh -u`

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
