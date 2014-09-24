# Docker-Nginx

Dockerfile for Nginx default setup on CentOS7

## Usage

> git clone git@github.com:akibe/docker-nginx.git
> cd docker-nginx
> docker build username/nginx .
> docker run -d -p 80:80 username/nginx

## Testing

The above example exposes the Adminer webinterface on port 80, so that you can now browse to:

> http://localhost/
