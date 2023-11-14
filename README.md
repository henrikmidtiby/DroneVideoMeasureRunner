# DroneVideoMeasureRunner

This repository can be used to install and run a version of [Drone Video Measure](https://github.com/egemose/DroneVideoMeasure/).
For the installation to work, you need to have [Docker](https://www.docker.com/) installed.

To install **DroneVideoMeasure** in windows do the following:
1. Download the **DroneVideoMeasureRunner** repository (code -> download zip).
2. Unpack the downloaded zip file in a suitable location
3. Open powershell and enter the directory where the `docker-compose.windows.yml` file is located.
4. Run this command to download the **Drone Video Measure** programm from dockerhub.com
```
docker compose -f docker-compose.windows.yml pull
```
5. Run this command to start **Drone Video Measure**
```
docker compose -f docker-compose.windows.yml up
```

The installation process is similar in MacOS and Linux, but use these commands instead
```
docker compose -f docker-compose.yml pull
docker compose -f docker-compose.yml up
```
