# drone-python

Python environment for drone, based on Debian Jessie

https://hub.docker.com/r/maze/drone-python/

## Installing

    $ docker pull maze/drone-python

## Usage

In your `.drone.yaml`:

    pipeline:
      build:
        image: maze/drone-python
	commands:
 	  - python setup.py install
