FROM node:alpine
LABEL maintainer="sshingare3@gmail.com"
WORKDIR /usr/Jeet/publisher
COPY publisher.js /usr/shital/publisher/
COPY data.json /usr/shital/publisher/
RUN npm install mqtt
CMD ["node", "publisher.js"]
