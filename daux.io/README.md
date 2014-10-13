# Daux.io Dockerfile

This Dockerfile will download the latest version of daux.io and will deploy it on a apache-php container.

## Usage
````
docker build -t username/my-php-app .
docker run -d -p 80:80 username/my-php-app
````
