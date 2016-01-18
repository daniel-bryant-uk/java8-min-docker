#"java8-min" Docker Image
A Java 8 Docker image built with Alpine and executing processes via the Yelp! dumb-init Dockerfile

The initial Alpine Java 8 Dockerfile was taken from [Nicola Paolucci's](https://developer.atlassian.com/blog/2015/08/minimal-java-docker-containers/)
great Atlassian Developer blog post, and modified to download the latest version of Java 8.

Yelp!s very useful ['dumb-init'](http://engineeringblog.yelp.com/2016/01/dumb-init-an-init-for-docker.html) init system
for Docker containers was then added.

At the moment the Dockerfile simply executes the command 'java -version', but you can aad you chosen executable JAR
file and execute this.
