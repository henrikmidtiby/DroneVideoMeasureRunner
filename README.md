# DroneVideoMeasureRunner

This repository can be used to install and run a version of [Drone Video Measure](https://github.com/egemose/DroneVideoMeasure/).
For the installation to work, you need to have [Docker](https://www.docker.com/) installed.

In windows the following commands is used for download and run [Drone Video Measure](https://github.com/egemose/DroneVideoMeasure/).
```
docker compose -f docker-compose.windows.yml pull
docker compose -f docker-compose.windows.yml up
```
In MacOS and Linux use these commands instead
```
docker compose -f docker-compose.yml pull
docker compose -f docker-compose.yml up
```
