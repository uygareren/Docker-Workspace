FROM ubuntu:20.04
RUN apt-get update
RUN apt-get install curl -y
RUN curl -sL https://deb.nodesource.com/setup_18.x | bash
RUN apt-get install nodejs -y
COPY . /opt/node-app/
WORKDIR /opt/node-app
ENV channelName=test
CMD ["node", "index.js"]
