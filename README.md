# Balena.io mosquitto server
You can use this project to run your mosquitto server on a balena.io (formerly resin.io) registered device.

It uses balena's Dockerfile.template specification, which allows us to build from the alpine architecture of our device (eg: armv7hf for raspberry pi).

You can rename the Dockerfile.template to Dockerfile and just use your own base image of alpine if you are not using balena.io. 

## Mosquitto Credentials
The main feature of this very simple container is that you can configure the mosquitto credentials with environmental variables.
Other repo's I have seen either [don't configure credentials](https://github.com/TrafeX/docker-alpine-mosquitto) or they are [way too complex](https://github.com/woahbase/alpine-mosquitto)

## TODO:
* Add volume storage 