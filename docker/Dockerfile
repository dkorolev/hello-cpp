FROM ubuntu:latest

RUN apt-get update -y
RUN apt-get install -y git g++

ADD docker_run.sh /docker_run.sh
RUN chmod +x /docker_run.sh

ENTRYPOINT ["/docker_run.sh"]
