FROM node:alpine

RUN mkdir -p /usr/src/app
 
WORKDIR /usr/src/app
 
COPY . /usr/src/app/

COPY . .

RUN npm install
 
EXPOSE 5173

CMD ["npm","run","dev"]
