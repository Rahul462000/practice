# base image for nodejs

FROM node:18-slim

#creating work directory for the container

WORKDIR /app

#copy the application files from local to container direcotry

COPY . .

# installing dependencies 

RUN npm install

#exposing port 

EXPOSE 3000

#serving the app and keep container running

CMD ["npm","run","dev"]
