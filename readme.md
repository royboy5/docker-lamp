# Docker - LAMP

Testing Docker with mysql:5.7 and php:7.0-apache.

## Setup
```
$ git clone https://github.com/royboy5/docker-lamp.git myLamp
$ cd myLamp
$ docker-compose up -d
```

## Docker for Windows Users
Enable Shared Drives
```
In the System Tray, Right Click the Docker Whale, and click Settings
Shared Drives -> <Check Drives that you want to share> -> Apply 
```

## Development
```
The public folder maps to /var/www/html.  All sites should be created in the public folder.
```

## Access

To access the site, goto

`http://localhost/ `