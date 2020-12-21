# IG-Docker
This repo is a docker set up for an Influx and Grafana instance.  
The influx user configuration is managed by the ``/influx/run.sh``, the default set up db=telegraf, user=telegraf, passwd=password. It is recommened that you change these defaults. 

## Requirements

This build requires docker and docker-compose to be installed.  

## Usage

- Clone this repository
- cd to directory of clone
- make changes to defaults in ``influx/run.sh``  
- navigate to the root of the repo
- docker-compose up --build -d
- verify the stack is running by visiting localhost:3000 or docker ps