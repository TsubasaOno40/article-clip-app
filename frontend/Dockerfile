FROM node:14.18.1-alpine
WORKDIR /usr/src/app/
COPY ./app .
RUN npm install
EXPOSE 3000
ENV CI true
CMD npm start
