# java-web-maven-blade-traefik-hello-world

## Description
A POC for blade framework rendering html page with self signed ssl certs.

## Tech stack
- cors
- ssl

## Docker stack
- alpine:edge
- maven:3-openjdk-17
- traefik:v2.4

## To run
`sudo ./install.sh -u`
Available at https://myapi.docker.localhost

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Blade framework code](https://github.com/eugenp/tutorials/tree/master/web-modules/blade)