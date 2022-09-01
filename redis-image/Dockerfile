# Use an existing docker image as a base
FROM alpine

# Dependency
RUN apk add --update gcc
RUN apk add --update redis

# What to do when start
CMD [ "redis-server" ]