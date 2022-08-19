FROM node:alpine
WORKDIR /usr/Jeet/publisher
COPY publisher.js /usr/shital/publisher/
COPY data.json /usr/shital/publisher/
RUN npm install mqtt
CMD ["node", "publisher.js"]