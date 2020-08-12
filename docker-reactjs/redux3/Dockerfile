FROM node:alpine

WORKDIR /usr/app

COPY package*.json ./
RUN npm install
RUN npm install react-scripts -g

COPY . .
CMD ["npm", "start"]