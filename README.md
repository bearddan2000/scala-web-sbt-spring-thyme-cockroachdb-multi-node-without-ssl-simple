# scala-web-sbt-spring-thyme-cockroachdb-multi-node-without-ssl-simple

## Description
A thyme springboot scala sbt build,
that connects to cockroach database

A scala sbt build, that connects to 3 node cluster
cockroach database without ssl.

## Tech stack
- springboot
  - thymeleaf
- sbt
  - postgres drivers
  - lombok
- bootstrap
- jquery
- dataTable

## Docker stack
- cockroachdb/cockroach:v19.2.2
- hseeberger/scala-sbt:11.0.2-oraclelinux7_1.3.5_2.12.10

## To run
`sudo ./install.sh -u`
- [web app](http://localhost)
- [Master node webui](http://localhost:8000)
- [Slave node 1 webui](http://localhost:8001)
- [Slave node 2 webui](http://localhost:8002)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Cockroach setup](https://github.com/s0rg/cockroach-compose)
