FROM node:alpine

WORKDIR /usr/app

COPY ./ ./

RUN npm install

CMD [ "npm", "start" ]

# docker run -p 8080:8080 {container name (id)}