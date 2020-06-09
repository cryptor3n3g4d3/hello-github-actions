FROM debian:9.5-slim

ADD entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/#!/bin/sh -l

sh -c "echo Hello world my name is $INPUT_MY_NAME"]
