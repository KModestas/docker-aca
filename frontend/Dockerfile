FROM node:14-alpine

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

# note env vars can also be defined in the docker file which will get hardcoded into the image at build time.
# ENV NAME=VALUE

EXPOSE 3000

CMD [ "npm", "start" ]