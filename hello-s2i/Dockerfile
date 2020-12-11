FROM registry.redhat.io/rhscl/nodejs-10-rhel7
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD [ "npm", "start" ]
