# JS Auto Test with Selenium on Python

## Requires

- Docker
- Docker Compose

## To run test

`make`

if docker needs sudo, run:

`sudo -E make`

The result will be in `./result/test.txt`

There might be a `Failed to execute script docker-compose` error when run on Docker for Windows via WSL2,
try to open a new terminal window and run again.

Tested okay on Ubuntu 20.04.

## WIP

HTML output via HTMLTestRunner
