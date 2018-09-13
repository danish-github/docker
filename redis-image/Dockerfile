# use existing docker image as base
FROM alpine

# Download and install dependency
RUN apk add --update redis


# tell imagw what to do when it starts as container
CMD [ "redis-server" ]