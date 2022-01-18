# Use and existing Docker Image as Base
FROM alpine

# Download an install dependency
RUN apk add --update redis

# Tell the Image what to do when
# Its starts as a container
CMD ["redis-server"]