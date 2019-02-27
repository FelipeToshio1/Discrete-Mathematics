FROM node:8

WORKDIR /usr/src/app 

COPY package*.json ./
RUN npm install
#RUN cpm ci

COPY . .

EXPOSE 8080

CMD ["npm", "start"]