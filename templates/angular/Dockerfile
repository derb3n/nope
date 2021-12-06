FROM node:12-alpine

WORKDIR /code


RUN npm install -g @angular/cli

COPY package*.json ./
RUN npm install

CMD ["ng","serve","--host","0.0.0.0"]