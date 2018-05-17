# docker-unifi

[![Build Status](https://travis-ci.org/coaxial/docker-unifi.svg?branch=master)](https://travis-ci.org/coaxial/docker-unifi)

Unifi controller in a docker container

## Usage

`docker-compose up -d`

Access the GUI at `http://localhost:8080`

## Notes

To point a new device to the controller for adoption, ssh into the Ubiquiti
device with `ssh ubnt@<device ip>` with password `ubnt`. Then issue `set-inform
http://<container ip>:8080/inform`
