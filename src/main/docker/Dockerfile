FROM alpine:3.5

# Use DOCKER_OPTS to modify the daemon startup options.
DOCKER_OPTS="--insecure-registry ec2-54-208-160-34.compute-1.amazonaws.com:8081"

ADD consumerBanking-1.0-SNAPSHOT.jar  app.jar
CMD "java -jar app.jar"
