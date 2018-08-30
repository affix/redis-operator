FROM alpine:3.6

RUN adduser -D redis-operator
USER redis-operator

ADD tmp/_output/bin/redis-operator /usr/local/bin/redis-operator
