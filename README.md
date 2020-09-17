![Hackazon Logo](https://github.com/rapid7/hackazon/blob/master/web/images/Hackazon.png?raw=true "Hackazon Logo")


## About Hackazon
Hackazon is a vulnerable test application site, that incorporates a realistic e-commerce workflow with full functionality and technology commonly used in today’s mobile and web applications.

This guide will allow you to setup a testing environment, enable you to see problems in action from an attacker’s perspective, and identify the fundamental issues which make such attacks possible.

[Hackazon Hacking Gudie](https://blog.securityevaluators.com/hacking-hackazon-2bda9830ccf0) 

## How to use this project 

Clone this repo 
```shell
git clone https://github.com/aracloud/hackazon/
```

Build and start 
```shell
cd hackazon/
docker-compose up
```

Wait for 10 secondes and contact the server :
```shell
firefox http://127.0.0.1:80

chromium http://127.0.0.1:80
```

## Configure

The project is configured by the files 
- [docker-compose.yml](https://github.com/aracloud/hackazon/blob/master/docker-compose.yml)
- [config/db.sample.php](https://github.com/aracloud/hackazon/blob/master/docker-compose.yml)
