## Docker Nginx & PHP

Create [docker](https://www.docker.com/what-docker) image using Dockerfile(Add required packages and softwares). Start container using `docker-compose`.

## Create image

1. cd to the directory i.e `cd images/nginx`
1. Create a docker image by name `tutorial/nginx` using Dockerfile `docker build -t tutorial/nginx .`


## Start container

1. Start the container using this image`docker-compose up -d`
2. Stop the container `docker-compose stop`

## Steps

1. Create image from the Dockerfile
1. Start container using `docker-compose` commands

## Reference urls

1. [Docker explained by DigitalOcean](https://www.digitalocean.com/community/tutorials/docker-explained-using-dockerfiles-to-automate-building-of-images)
1. [Docker for php developers](http://www.newmediacampaigns.com/blog/docker-for-php-developers)
