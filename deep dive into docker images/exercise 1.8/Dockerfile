FROM ubuntu:20.04
WORKDIR /usr/src/app
RUN apt-get update && apt-get -y install curl
COPY script.txt .
RUN chmod +x script.txt
ENTRYPOINT [ "./script.txt" ]