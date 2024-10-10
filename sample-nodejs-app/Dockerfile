FROM node:14
WORKDIR /home/ubuntu
RUN git clone https://github.com/Vmoralles/first-pipeline.git .
WORKDIR /home/ubuntu/sample-nodejs-app
RUN npm install
CMD ["npm", "start"]
EXPOSE 8080
