# groovy-cli-gradle-ssl-postgresql-data-type-array

## Description
Creates a small table `dog` that uses
a text array data type. Arrays can also be
numeric.

A groovy gradle build, that connects to postgresql database.

Uses self-sign ssl.

## Tech stack
- groovy
- gradle
  - log4j
  - postgresql drivers

## Docker stack
- alpine:edge
- postgresql:alpine
- gradle:jdk11

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
