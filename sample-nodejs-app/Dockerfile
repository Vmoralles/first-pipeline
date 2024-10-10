FROM node:14
WORKDIR /usr/src/app
COPY sample-nodejs-app/package*.json ./
RUN npm install
COPY sample-nodejs-app/. .  
EXPOSE 3000
CMD ["node", "app.js"]
