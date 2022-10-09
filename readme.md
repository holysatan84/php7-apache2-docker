## Docker project for PHP7 and Apache2

This is a docker project to create a container with PHP7, Xdebug and Apache2. 

* docker-compose -f _docker/docker-compose.yml up -d --force-recreate 

    Starts the container 
    - php7-apache2
    - mysql-db

* Browse to http://localhost:8002

    A sample employee list page is displayed.

See Dockerfile and docker-compose.yml for configuration details.
