FROM node:20.10.0

#create app directory
WORKDIR /usr/src/app

COPY package*.json ./
RUN npm install

COPY ..

EXPOSE 7777
CMD ["npm","run","start"]
