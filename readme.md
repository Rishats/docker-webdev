# Docker-webdev-php

Contains: php 7.1, mysql 8, nginx
Addons: phpmyadmin, composer

## Installation

Install docker:
[Ubuntu](https://docs.docker.com/install/linux/ubuntu/)
[Mac](https://docs.docker.com/docker-for-mac/install/)
[Windows](https://docs.docker.com/docker-for-windows/install/)

Install docker-compose:
[docker-compose](https://docs.docker.com/compose/install/)

I personally have folder:
```
/home/username/webdev/
```

1)
```
cd /home/username/webdev/
```
2)
```
git clone git@github.com:Rishats/docker-webdev.git .
```
3)
``` 
docker-compose up -d 
```

## Using

File structure:

www - in this folder will be files of our projects, according to the directory for each project;
mysql - this folder will store the files of our databases;
logs - here will compile logs from different images;
hosts - this will store the nginx configuration files for our projects;
images - a folder with our images - components of our system.






