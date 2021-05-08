*Usage:*

1. Build the docker image: `$ docker build -t httpd .`
2. Run the httpd server with the benchmarking command: `$docker run --rm httpd ab -n 100000 -c <target-url>`

