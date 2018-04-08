# A Better Debian Image on Docker #
[![Ducker Hub: ghifari160/debian](https://img.shields.io/badge/docker%20hub-ghifari160%2Fdebian-%23ABD8EB.svg)](https://hub.docker.com/r/ghifari160/ubuntu)

Because the official image is lacking.

## Why this image is better than the official image ##
Like [ghifari160/ubuntu][g16-ubuntu], this image adds many utilities that is
lacking on the official image. The added packages on this image parallels the
ones on [ghifari160/ubuntu][g16-ubuntu]. Packages can be requested via the
[Issue Tracker][g16-deb-issue].

Added packages:
```
nano
software-properties-common
wget
```

## Installation ##
This image will not run as a daemon by default. It will exit immediately as it
does not execute any foreground process. Run this image in interactive mode.
```
docker run -it ghifari160/debian
```

## Tags ##
| Tags                     | Debian Version | Size  |
|--------------------------|----------------|-------|
| `latest` `9.4` `stretch` | 9.4            | *TBA* |
| `8.10` `jessie`          | 8.10           | *TBA* |

[g16-ubuntu]: https://hub.docker.com/r/ghifari160/ubuntu
[g16-deb-issue]: https://github.com/ghifari160/docker-debian/issues
