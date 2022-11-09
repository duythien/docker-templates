# Docker-templates

###  Docker energi

To build docker image  Energi with specify version, you can use used arg ENERGI_VERSION, for example to build Energi with version v3.1.3 do following the command below

```
docker build --build-arg ENERGI_VERSION=v3.1.3 . -t energi/node:v3.1.3

```
If you do not add that option ENERGI_VERSION, it will be got default version v3.1.2