# CHANGELOG

## To do

1. Add application pgAdmin4
2. Fix mongoexpress Authorization Required
3. add https://hub.docker.com/u/collabora
4. codiad/code-server have file permission issues
5. add all containers status in handler

## Logs

### Bug Fixes

* 2020-10-04  add user: "1000:1000" for docker-compose template file and setfacl docker user to app_name folder that can fix the user permission for container
* 2020-09-29  onlyoffice volumes postgresql no permission,delete the volumes ["{{docker_apps_dir}}/{{docker_appname}}/postgresql:/var/lib/postgresql"]
* 2020-09-20  variable docker-applications definde [] replace ''
* 2020-08-14  change pip install docker to yum install docker
* 2020-07-31  add soft link in TASK [role_docker : Install Docker Compose] to correct error "/bin/sh: docker-compose: not found" in CentOS of Azure, AmazonLinux
* 2020-05-15  Portainer port set to 9000
* 2020-03-29  Give up ansible docker module, use docker cli to replace it

### Features

* 2020-09-27  add application Codiad
* 2020-09-19  optimize application installation by apply application template
* 2020-09-16  add create a new network named apps
* 2020-03-14  add application：Portainer, phpMyAdmin, phpPgAdmin, onlyofficedocumentserver, AdminMongo
