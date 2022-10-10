## Docker project for PHP7 and Apache2

This is a docker project to create a container with PHP7, Xdebug and Apache2. 

* Create the docker network by running `docker network create app_main_network` 
* docker-compose -f _docker/docker-compose.yml up -d --force-recreate 

    Starts the container 
    - php-app
    - nginx-web 
    - mysql-db

add the following entry to host file 
    127.0.0.1 php.local mysql.local

* Browse to http://php.local

- mysql settings
    - host: mysql.local
    - db name: mydb
    - db username: db_admin
    - db password: devmysql
    - db port: 31003

    A sample employee list page is displayed.

See Dockerfile and docker-compose.yml for configuration details.
