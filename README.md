# java-cli-buildr-ssl-postgresql-data-type-array

## Description
Creates a small table `dog` that uses
a text array data type. Arrays can also be
numeric.

A java buildr build, that connects to postgresql database.

Uses self-sign ssl.

## Tech stack
- java
- buildr
  - log4j
  - postgresql drivers

## Docker stack
- alpine:edge
- postgresql:alpine
- vanto/apache-buildr:latest-jruby-jdk8

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
