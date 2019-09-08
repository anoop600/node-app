FROM node:8
WORKDIR /usr/src/app
COPY . .
#COPY package*.json ./
RUN npm install
EXPOSE 3021
CMD [ "npm", "start" ]
