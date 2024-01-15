# docker-httpd-proxy

Supported tags and respective `Dockerfile` links:
- [`2.4-1.0.0`](https://github.com/vavyskov/docker-httpd-proxy/tree/master/2.4/alpine3.19)

Build and push custom image example:
```
cd docker-httpd-proxy/2.4/alpine3.19
docker build -t vavyskov/httpd-proxy:2.4-1.0.0 .
docker push vavyskov/httpd-proxy:2.4-1.0.0
```

Get current httpd configuration:
```
docker run -d httpd
docker cp <CONTAINER_ID>:/usr/local/apache2/conf/httpd.conf .
```
