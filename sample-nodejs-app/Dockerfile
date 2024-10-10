FROM node:14
WORKDIR /usr/src/app
RUN git clone https://github.com/Vmoralles/first-pipeline.git .
WORKDIR /usr/src/app/sample-nodejs-app
RUN npm install
EXPOSE 3000
CMD ["node", "start"]
